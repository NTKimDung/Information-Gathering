# Thu thập các tệp nhạy cảm - Discovering Sensitive Files
Tên tài liệu: Thu thập các tệp nhạy cảm của website - 'shopify.com' Thực hiện: Nguyễn Thị Kim Dung Cập nhật lần cuối: 28/07/2025
## 1. Mục tiêu thu thập 
Mục tiêu của Discovering Sensitive Files:
* Tiết lộ thông tin nội bộ của hệ thống, như:
Username, mật khẩu (database, API key, email SMTP,...)
Cấu hình hệ thống (thư mục, cổng, dịch vụ đang chạy)
Địa chỉ IP nội bộ, tài khoản admin
Các API endpoint chưa công khai
* Khai thác tấn công sâu hơn, ví dụ:
Chiếm quyền truy cập vào cơ sở dữ liệu
Dùng token hoặc key tìm được để truy cập các dịch vụ nội bộ
Sử dụng bản backup hoặc source code để tìm lỗi logic, RCE
* Phân tích sai sót lập trình viên / sysadmin:
Để lại file .bak, .old, .zip, debug.log,…
Commit nhầm .env, key bí mật vào repo Git
* Dò tìm điểm yếu để hỗ trợ các bước tấn công tiếp theo, như:
Privilege escalation
Local File Inclusion (LFI), Remote Code Execution (RCE)
## 2. Thu thập các file ẩn bằng công cụ dirsearch
kết quả cho thấy:                                                                                                                                                                                                                                                                                          
Extensions: php, aspx, jsp, html, js | HTTP method: GET | Threads: 25 | Wordlist size: 11460
Output File: /home/kali/reports/_shopify.com/_25-07-28_05-39-43.txt
Target: https://shopify.com/
                                                                                                                                   
[05:39:49] 200 -  606B  - /.well-known/assetlinks.json                      
[05:39:49] 200 -  354B  - /.well-known/apple-app-site-association           
[05:39:56] 301 -  167B  - /axis2-web//HappyAxis.jsp  ->  https://www.shopify.com/axis2-web/HappyAxis.jsp
[05:39:56] 301 -  167B  - /axis2//axis2-web/HappyAxis.jsp  ->  https://www.shopify.com/axis2/axis2-web/HappyAxis.jsp
[05:39:56] 301 -  167B  - /axis//happyaxis.jsp  ->  https://www.shopify.com/axis/happyaxis.jsp
[05:39:58] 301 -  167B  - /Citrix//AccessPlatform/auth/clientscripts/cookies.js  ->  https://www.shopify.com/Citrix/AccessPlatform/auth/clientscripts/cookies.js
[05:40:01] 301 -  167B  - /engine/classes/swfupload//swfupload_f9.swf  ->  https://www.shopify.com/engine/classes/swfupload/swfupload_f9.swf
[05:40:01] 301 -  167B  - /engine/classes/swfupload//swfupload.swf  ->  https://www.shopify.com/engine/classes/swfupload/swfupload.swf
[05:40:02] 301 -  167B  - /extjs/resources//charts.swf  ->  https://www.shopify.com/extjs/resources/charts.swf
[05:40:03] 301 -  167B  - /html/js/misc/swfupload//swfupload.swf  ->  https://www.shopify.com/html/js/misc/swfupload/swfupload.swf
[05:40:17] 200 -   65B  - /robots.txt  

Giải thích:

[05:39:49] 200 -  606B  - /.well-known/assetlinks.json
[05:39:49] 200 -  354B  - /.well-known/apple-app-site-association
→ Status 200 = tồn tại, có thể truy cập
→ Các file .well-known là chuẩn dùng cho mobile app linking hoặc xác minh

* Các dòng: 
301 - ... - /axis2-web//HappyAxis.jsp  -> https://www.shopify.com/axis2-web/HappyAxis.jsp
→ 301 là chuyển hướng → URL tồn tại nhưng chuyển sang link mới

*Dòng:
[05:40:17] 200 -   65B  - /robots.txt
→ File robots.txt thường chứa danh sách các thư mục mà crawler (bot) không nên truy cập → nhưng pentester thì ngược lại, hay soi kỹ file này.
