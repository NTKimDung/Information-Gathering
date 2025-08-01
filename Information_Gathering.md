# Information Gathering
Tên tài liệu: Information Gathering - 'shopify.com' Thực hiện: Nguyễn Thị Kim Dung Cập nhật lần cuối: 01/08/2025
# Mục lục
- [A. Thu thập thông tin tên miền - 'shopify.com']
  - [1. Thông tin tổng quan]
  - [2. Trạng thái tên miền (Registrar Status)]
  - [3. Máy chủ tên miền (Name Server)])
  - [4. Thông tin địa chỉ IP]
  - [5. Thông tin kỹ thuật]
- [B. Thu thập website khác cùng máy chủ]
  - [1. Thông số kỹ thuật]
  - [2. Danh sách một số website chia sẻ cùng domain]
- [C. Recon Detect Technologies]
  - [1. Quy trình thực hiện]
  - [2. Điều tra thủ công]
  - [3. Điều tra sử dụng công cụ]
    - [3.1 Wappalyzer]
    - [3.2 nuclei]
    - [3.3 SearchSploit]
- [D. Recon Finding Hidden Content]
  - [1. Khái niệm và phương pháp]
  - [2. Công cụ sử dụng]
    - [2.1 Naabu (Port Scan Tool)]
    - [2.2 Dirsearch/Feroxbuster/Gobuster (File Bruteforcing)]
    - [2.3 Arjun (Parameter Bruteforcing)]
- [E. Recon Subdomain Enumeration và HTTP]
  - [1. Khái niệm và phương pháp]
  - [2. Các công cụ]
    - [2.1 Công cụ thụ động (crt.sh, Google Dork, DNSdumpster)]
    - [2.2 Knockpy (Chủ động bruteforce)]
    - [2.3 HTTPX]
- [F. Recon Wayback Machine Crawling]
    - [1. Giới thiệu Wayback Machine]
    - [2. Công cụ GAU - GetAllUrls]
- [H. Tổng kết]
- [G. Tài liệu tham khảo]

## A. THU THẬP THÔNG TIN TÊN MIỀN - 'shopify.com'
### 1. Thông tin tổng quan
* Tên miền:  shopify.com
* Registrar (Nhà đăng ký): MarkMonitor, Inc. MarkMonitor Inc. (IANA ID: 292)
* Địa chỉ trang web MarkMonitor (trang web đăng ký): http://www.markmonitor.com
* Whois Server: whois.markmonitor.com
* Ngày tồn tại: 7.440 
* Ngày đăng ký lần đầu tiên: 11/03/2005
* Ngày hết hạn tên miền: 11/03/2027
* Ngày cập nhật gần nhất: 29/05/2025
### 2. Registrar Status (Trạng thái bảo vệ tên miền)
* clientDeleteProhibited : Người dùng (chủ sở hữu) không thể xóa tên miền qua giao diện quản lý.
* clientTransferProhibited: Không thể chuyển tên miề sang nhà đăng ký khác
* clientUpdateProhibited: Không thể chỉnh sửa thông tin tên miền (như: DNS, ...)
* serverDeleteProhibited: Registry(cấp trên) ngăn không cho xóa tên miền.
* serverTransferProhibited: Registry cũng cấm chuyển tên miền qua nới khác.
### 3. Name server (Máy chủ tên miền)
* GOLD.FOUNDATIONDNS.COM (has 8,843 domains)
* GOLD.FOUNDATIONDNS.NET (has 5 domains)
* GOLD.FOUNDATIONDNS.ORG (has 4 domains)
### 4. Thông tin địa chỉ IP
* IP Address: 23.227.38.33
* IP Local: Hoa Kỳ – Florida – Miami – Cloudflare Inc.
* ASN (Số hiệu hệ thống tự trị): AS13335 CLOUDFLARENET, US (registered Jul 14, 2010)
* Lịch sử IP: 82 changes on 82 unique IP addresses over 20 years
* Lịch sử hosting:  5 changes on 4 unique name servers over 9 years
* Tình trạng website: Registered And No Website
### 5. Thông tin kỹ thuật
* DNSSEC: unsigned
* Hệ thống quản lý tên miền: MarkMonitor Domain Management(TM) - Bảo vệ các công ty và người tiêu dùng trong thế giới kỹ thuật số.
## B. Thu thập website khác cùng máy chủ
### 1.  Thông số kỹ thuật
* Tên miền chính: 'shopify.com'
* Tổ chức sở hữu domain: Shopify, Inc.
* Tổ chức cung cấp hosting: Cloudflare, Inc.
* Địa chỉ IP công bố: 23.227.38.33
* ASN: AS13335
* Tên hệ thống tự trị (AS Name): CLOUDFLARENET
* Quốc gia đặt máy chủ: Canada
* Thành phố: Ottawa
* Số lượng domain cùng IP: 85 domain
### 2. Danh sách một số website chia sẻ cùng domain
Có tổng cộng 85 tên miền đang sử dụng cùng một máy chủ với 'shopify.com' với IP là: 23.227.38.33 
| STT | Tên miền (Domain)             | Ngày truy vết gần nhất (Last Resolved) |
|-----|-------------------------------|----------------------------------------|
| 1   | 130701.xyz                    | 2025-06-13                             |
| 2   | 61                            | 2025-07-16                             |
| 3   | 161                           | 2025-07-24                             |
| 4   | actualwebstore.com           | 2025-07-24                             |
| 5   | adsgd01.shop                 | 2025-01-04                             |
| 6   | allsheneeds.fr               | 2024-05-25                             |
| 7   | allyouneedonline.online      | 2024-11-23                             |
| 8   | armetshop.com                | 2025-07-24                             |
| 9   | artprintdeckchairs.com      | 2016-10-03                             |
| 10  | aryanshop.dk                 | 2015-12-09                             |
| 11  | bagsplussome.com             | 2025-07-24                             |
| 12  | billyboyshop.com             | 2025-07-24                             |
| 13  | billyboyshop.es              | 2025-07-21                             |
| 14  | blakeshardcider.shop        | 2025-07-19                             |
| 15  | blimyparis.com               | 2025-07-24                             |
| 16  | bluemoontreasures.net       | 2025-07-21                             |
| 17  | boschebikespares.com        | 2025-07-24                             |
| 18  | buou.one                     | 2024-08-30                             |
| 19  | buy4u.at                     | 2025-07-21                             |
| 20  | buyby.fr                     | 2023-09-09                             |
| 21  | cabletiesdirect.net.au      | 2018-03-18                             |
| 22  | cherishcapo.shop            | 2025-05-18                             |
| 23  | connect-dental.co.uk        | 2025-07-18                             |
| 24  | dabbilicious.com            | 2025-07-24                             |
| 25  | dabblicious.com             | 2025-07-24                             |
| 26  | daydreams.cn                 | 2025-07-23                             |
| 27  | dddd1123.club               | 2019-06-16                             |
| 28  | deal-spot.nl                | 2020-08-27                             |
| 29  | dellalondonshop.com         | 2025-07-24                             |
| 30  | dentelle-avenue-uk.store    | 2025-02-22                             |
| 31  | easywine.fr                 | 2024-07-06                             |
| 32  | ezschic.com                 | 2025-07-10                             |
| 33  | fadeshop.at                 | 2025-02-03                             |
| 34  | fembrace.co                 | 2025-07-19                             |
| 35  | getbielli.com               | 2025-07-10                             |
| 36  | gizmosindia.in              | 2025-07-18                             |
| 37  | goblindildoemporium.com     | 2025-05-15                             |
| 38  | holacarrentals.com          | 2025-07-10                             |
| 39  | huahengchi.com              | 2025-07-10                             |
| 40  | iteekone.com                | 2025-07-10                             |
| 41  | ivyblu.co.nz                | 2025-07-19                             |
| 42  | kachboorganics.com          | 2025-07-10                             |
| 43  | karati.com                  | 2025-07-24                             |
| 44  | kftestshop.com              | 2025-07-10                             |
| 45  | lazyneck.fr                 | 2020-01-04                             |
| 46  | legarderobes.com            | 2025-07-10                             |
| 47  | lestissees.com              | 2025-07-10                             |
| 48  | luxprojec.com               | 2024-09-18                             |
| 49  | makeuprevolution.us         | 2025-06-03                             |
| 50  | mantassk.xyz                | 2024-12-15                             |
| 51  | maxabdo.fr                  | 2019-12-07                             |
| 52  | miniworld-sneaker.com       | 2020-02-05                             |
| 53  | orniphilia.com              | 2024-10-09                             |
| 54  | ornipress.com               | 2025-07-10                             |
| 55  | prometeme.com               | 2025-07-10                             |
| 56  | puredier.co.za              | 2025-07-18                             |
| 57  | restoringcrownz.com         | 2025-07-10                             |
| 58  | revalbeauty.com             | 2022-07-04                             |
| 59  | rewclothing.com             | 2025-07-10                             |
| 60  | sandolt.com                 | 2024-11-27                             |
| 61  | sbsliquors.com              | 2025-07-14                             |
| 62  | seltrik.com                 | 2025-07-10                             |
| 63  | shopify.com                 | 2025-07-24                             |
| 64  | shopify.exchange           | 2025-07-19                             |
| 65  | smartworkartwork.com        | 2019-09-02                             |
| 66  | smelleasy.fr               | 2024-10-05                             |
| 67  | solar-center.mx            | 2025-07-23                             |
| 68  | spacemax.fr                | 2019-12-28                             |
| 69  | spellitonthewall.com        | 2020-06-23                             |
| 70  | stilik.store               | 2024-05-25                             |
| 71  | surfculture.fr             | 2025-07-19                             |
| 72  | techpurr.com               | 2025-07-10                             |
| 73  | testfailover.live          | 2019-11-28                             |
| 74  | testfailover.today         | 2019-11-28                             |
| 75  | thac.no                    | 2025-07-24                             |
| 76  | theculturefiends.com       | 2025-07-10                             |
| 77  | theknox.store              | 2025-04-20                             |
| 78  | themargoshop.com           | 2025-07-10                             |
| 79  | thryveclothing.com         | 2025-07-10                             |
| 80  | v23athletics.com           | 2025-07-10                             |
| 81  | velossiti.com              | 2025-07-10                             |
| 82  | wyze.com                   | 2025-07-24                             |
| 83  | yotalife.com               | 2025-07-10                             |
| 84  | yourshoppingcart.co.za     | 2018-06-03                             |
| 85  | yungnrich.com              | 2025-07-10                             |
## C. RECON DETECT TECHNOLOGIES
### 1. Cách thực hiện để recon detect technologies
Định nghĩa: Recon chia thành hai dạng là Active recon và Passive recon.
Với Active recon (điều tra chủ động) chủ động tìm thông tin bằng cách tương tác trực tiếp với trang web, máy chủ hoặc thiết bị mạng mà bạn muốn điều tra. Passive recon (điều tra bị động) khác với điều tra chủ động điều tra bị động không tương tác trực tiếp với đối tượng cần điều tra mà ta tương tác với bên trung gian (bên thứ 3) để tìm hoặc lấy các thông tin mà máy chủ, website hoặc thiết bị mạng đã công bố với bên ngoài.
Recon detect technologies có nghĩa là điều tra các công nghệ mà trang web sử dụng. Quy trình điều tra công nghệ được sử dụng ở phía sau của trang website với cách thức như sau: Bạn gửi request (truy vấn) đến trang website thì website sẽ trả lời bạn bằng cách gửi lại cho bạn một phản hồi lại bao gồm html, http headers, có thể kèm theo mã nguồn, script, ... từ đây ta phân tích phản hồi xem bên trong trang web bao gồm  framework, CMS, công nghệ nào xây dựng lên trang web, ...  
### 2. Điều tra thủ công 
Điều tra detect technologies trực tiếp trên trang web:
Bước 1: Ta gửi request đến trang web
Bước 2: Sau khi trang web phản hồi bằng cách hiện trang nội dung của trang web (thường là trang chủ) ta thực hiện bước điều tra.
Bước 3: Ta điều tra công nghệ của trang web bằng cách nhất chuột trái vào trang web. Ở đây sẽ hiện ra một khung cửa sổ nhỏ ta chọn "View Page source _ Ctrl + U" hoặc thêm "view-source" đằng trước địa chỉ URL để xem mã nguồn của website. Trong source này thường chứa các version mà trang web sử dụng.
### 3. Điều tra sử dụng tool
#### 3.1 Công cụ Wappalyzer
Ta cài đặc Wappalyzer là công cụ tiện ích ở trên trình duyệt web. Ở đây ta điều tra detect technologies của website "shopify.com" ta thấy được có các công cụ HSTS, Cloudflare, HTTP/3 .
#### 3.2 Công cụ nuclei
Đây là công cụ scan. Cơ chế hoạt động đây là công cụ template. Khi chạy tool nuclei thì thì template sẽ load bộ luật này thì sẽ kiểm tra xem trong trang web có dùng công cụ nào thì sẽ hiện ra kết quả.
Công cụ scan hết các bộ luật trong template để kiểm tra các thông tin của website không chỉ điều tra công nghệ mà còn các thông tin khác như whois, subdomain, ... 
Ở đây ta điều tra được kết quả "[tech-detect:cloudflare] [http] [info] https://shopify.com" 
Cloudflare là một công ty công nghệcung cấp nhiều dịch vụ bảo mật, hiệu suất và độ tin cậy trên internetCloudflare hoạt động như một proxy ngược, CDN và nhà cung cấp dịch vụ giảm thiểu DDoS, cùng nhiều chức năng khác. Về cơ bản, Cloudflare đóng vai trò trung gian giữa người truy cập trang web và máy chủ, cung cấp khả năng bảo vệ chống lại các mối đe dọa như tấn công DDoS và cải thiện hiệu suất.
"[mx-service-detector:Google Apps] [dns] [info] shopify.com"
"[dmarc-detect] [dns] [info] _dmarc.shopify.com [""v=DMARC1; p=reject; pct=100; fo=1; rua=mailto:dmarc-aggregate@shopify.com;ruf=mailto:dmarc-reports@shopify.com""]"
"[assetlinks-detect] [http] [info] https://shopify.com/.well-known/assetlinks.json"
#### 3.3 Công cụ SearchSploit
Tool này để ta search các sploit hoặc các framework bạn vừa tìm ra ở trên bằng các công cụ như wappalyzer hoặc công cụ nuclei, ... 
Sau khi điều tra bằng searchsploit cho website "shpoify.com" thì ta không nhận được bất kì kết quả nào. Vậy ta có thể thấy được website shopify là nền tảng lớn ít lỗ hổng công khai.
## D. RECON FINDING HIDDEN CONTECT
### 1. Cách recon finding hidden contents
Thu thập các thông tin ẩn như file, port, parameter,... của website để có thể lợi dụng để tấn công.
Cách tìm scan port:
Port scan có hai kiểu scan là TCP Scan và UDP Scan. Nguyên lý hoạt động bạn gửi một gói tin lên server và server sẽ gửi về cho bạn một gói tin khác. Dựa vào gói tin trả về bạn sẽ xác định được port đang mở và port nào đang đóng. Với TCP Scan thì khi client gửi SYN Scan lên server và cùng với một thông số port xác định thì server gửi về SYN/ACK thì client biết được các port trong server được đang mở còn nếu server gửi lại cho client là RST/SYN thì cleint biết được port server đang đóng. 
### 2. Các tool
#### 2.1 Port Scan Tool _ Naabu
Mục tiêu: list được các tất cả các port và có khả năng thấy được service đang chạy port đó để ta lợi dụng port đó để tấn công.
Lợi ích: công cụ naabu có thể scan khoản port rộng một cách nhanh chóng.
Naabu có thể tích hợp với nmap để khai thác thông tin.
ngoài ra có nhiều định dạng đầu ra như JSON, Fiel, Stdout.
Kết quả khi dùng tích hợp naabu với nmap:
PORT     STATE SERVICE  VERSION
80/tcp   open  http     Cloudflare http proxy
443/tcp  open  ssl/http Cloudflare http proxy
8080/tcp open  http     Cloudflare http proxy
8443/tcp open  ssl/http Cloudflare http proxy
8880/tcp open  http     Cloudflare http proxy
#### 2.2 File Bruteforcing _ disearch, feroxbuster,gobuster
Tool disearch được chạy bằng python dùng wordlist để brute-force URL của server web, nhằm tìm các file ẩn có trong website.
Kết quả sau khi dùng dirsearch: 
"[02:55:47] 200 -  354B  - /.well-known/apple-app-site-association           
[02:55:47] 200 -  606B  - /.well-known/assetlinks.json                      
[02:56:05] 301 -  167B  - /axis//happyaxis.jsp  ->  https://www.shopify.com/axis/happyaxis.jsp
[02:56:05] 301 -  167B  - /axis2-web//HappyAxis.jsp  ->  https://www.shopify.com/axis2-web/HappyAxis.jsp
[02:56:05] 301 -  167B  - /axis2//axis2-web/HappyAxis.jsp  ->  https://www.shopify.com/axis2/axis2-web/HappyAxis.jsp
[02:56:09] 301 -  167B  - /Citrix//AccessPlatform/auth/clientscripts/cookies.js  ->  https://www.shopify.com/Citrix/AccessPlatform/auth/clientscripts/cookies.js
[02:56:15] 301 -  167B  - /engine/classes/swfupload//swfupload.swf  ->  https://www.shopify.com/engine/classes/swfupload/swfupload.swf
[02:56:15] 301 -  167B  - /engine/classes/swfupload//swfupload_f9.swf  ->  https://www.shopify.com/engine/classes/swfupload/swfupload_f9.swf
[02:56:16] 301 -  167B  - /extjs/resources//charts.swf  ->  https://www.shopify.com/extjs/resources/charts.swf
[02:56:20] 301 -  167B  - /html/js/misc/swfupload//swfupload.swf  ->  https://www.shopify.com/html/js/misc/swfupload/swfupload.swf
[02:56:37] 200 -   65B  - /robots.txt   "
Dirsearch tìm được một số tệp .well-known, robots.txt, .swf, .jsp, ... cho thấy vẫn còn tồn tại endpoint cũ, có thể chứa rủi ro bảo mật.
 #### 2.3 Parameter Bruteforcing_Arjun
 Mục đích: Các trang web cho bạn tương tác thì bạn có thể xem được request theo dạng GET/PORT ta biết được các giá trị các biến đưa vào các parameter hoặc vào webserver để xửa lý. Có thể gặp các trang web không biết được parameter thì ta phải bruteforcing thì công cụ để làm việt đó là Arjun. Sau khi điều tra thì ta có thể lợi dụng các tham số ẩn (hidden GET & POST parameters) trong URL để thực hiện các cuộc tấn công như:
XSS (Cross Site Scripting)
SQL Injection
LFI/RFI (File Inclusion)
Command Injection, v.v.
Kết quả sau khi dùng công cụ arjun cho website "shopify.com" là:
Tìm ra được 11 parameters: url, manifestPath, path, mode, parentId, version, module, logo, basename, id, name
Parameters found: version, lang, p, page, sort, ref, name, q, country, mybulletin
## E. RECON SUBDOMAIN ENUMERATION VÀ HTTP
### 1. Cách recon subdomain enumeration và http
Subdomain Enumeration là quá trình thu thập các tên miền phụ (subdomains) của một tên miền chính. Có hai cách để tìm là Active và Passive Enumeration.
### 2. Các công cụ
#### 2.1 Các công cụ khai thác thụ động
Ta có thể sử dụng Certificate transparecy để tìm các subdomain hoặc sử dụng trang https://crt.sh để tìm ra các subdomain của đối tượng mình cần điều tra.
Hoặc ta có thể sử dụng kỹ thuật search engine ta dùng google dork để thu thập thông tin nhạy cảm từ các website. Với mục đích tìm subdomain thì ta dùng câu lệnh "site:shopify.com" để tìm subdomain của website của shopify.
Kỹ thuật DNS: ta dùng trang web "https://dnsdumster.com" để tìm kiếm với kết quả trả về là các subdomain.
Tool Subfinder: Lên internet để tìm tất cả các subdomain trong tất cả các search engine nơi mà các subdomain mà đã, đang và xuất hiện mà không ảnh hưỡng đến các server trang web mà ta muốn thu thập thông tin.
Kết quả sau khi sử dụng công cụ Subfinder: Tìm ra 580 subdomains từ 'shopify.com'.
#### 2.2 Các công cụ khai thác chủ động _ Knockpy
Tool Knockpy: được viết bằng python với mục đích dò tìm subdomain với wordlist, truy vấn các bản ghi dns, ... 
Ngoài sử dụng tool ta có thể bruteforcing.
#### 2.3 Công cụ HTTPX:
Sau khi tìm được các subdomain web service thì ta dùng HTTPX để kiểm tra trạng thái hoạt động và thu hập thông tin từ danh sách miền.
## F. RECON WAYBACK MACHINE CRAWLING
### 1. Wayback machine:
Nó là một trang web chứa các trang web ngày xưa có nghĩa là lưu trữ bản snapshot lịch sử của trang web, giúp bạn thấy các URL, endpoint đã từng tồn tại nhưng có thể đã bị xóa trên live site. Mục đích: Check status của trang web có thay đổi hay không hoặc lấy được dữ liệu crawler của trang web đó hoặc check file cũ có thể vẫn tồn tại ở nơi nào đó.
Trang web mà để điều tra là: "[https://waybackmachine.com](https://web.archive.org/)" trang web này để hiện thị được sự thay đổi của trang web.
Wayback machine dùng cho trang robots.txt để tìm được lỗ hổng để ta có thể tấn công.
Wayback machine mà trả về mà 404 hoặc 403 để lấy được một số thông tin để tấn công. và ngoài ra khi sử dụng waybackmachine thì ta có thể lấy tất cả đường dẫn và parameter có thể là một lợi thế để tấn công.
Kết quả khi sử dụng trang web wayback machine về website "shopify.com" ta có thể thấy được dữ liệu đến từ nhiều nguồn crawling khác nhau, hiện thị được tất cả các thời gian mà trang web thay đổi,....
## 2. Công cụ để list ra các URL lịch sử_gau
GAU (GetAllUrls) là một công cụ dùng để thu thập tất cả các URL đã từng được thu thập từ các dịch vụ như Wayback Machine, Common Crawl, URLScan... dựa trên một tên miền hoặc subdomain.
Kết quả sau khi sử dụng công chụ gau cho website "shopify.com" là: 
Thu được hơn 50 dòng URL. Ta thấy được một số URL chứa tham số truy vấn (query parameters) rất phù hợp để phân tích hoặc khai thác thử như:
"https://shopify.com/10002752/account?locale=en
https://shopify.com/10011279418/account?locale=es&region_country=CO
https://shopify.com/10027190/account?locale=el&region_country=FI". Ngoài ra còn có một số URL sử dụng giao thức http:// hoặc không có www. → giúp phát hiện các cấu hình web server cũ hơn hoặc chưa redirect đúng và nhiều bản ghi lặp lại https://www.shopify.com/ hoặc https://shopify.com/ → cần xử lý loại bỏ trùng (sort -u) để có danh sách sạch.
## G. Tổng kết
Quá trình thu thập thông tin (reconnaissance) đối với domain shopify.com đã được thực hiện toàn diện qua nhiều bước, bao gồm: thu thập thông tin DNS, điều tra công nghệ sử dụng, tìm kiếm subdomain, phát hiện nội dung ẩn, và truy vết lịch sử website thông qua Wayback Machine. Việc sử dụng kết hợp các công cụ như Wappalyzer, Nuclei, Searchsploit, Dirsearch, Arjun, Knockpy, HTTPX, GAU... đã giúp nâng cao hiệu quả và độ chính xác trong quá trình phân tích.
Thông qua đó, một số endpoint nhạy cảm, công nghệ cũ, hoặc tài nguyên ẩn đã được phát hiện – tạo nền tảng vững chắc cho các bước tiếp theo như đánh giá bảo mật, kiểm thử thâm nhập (pentest), hoặc tìm kiếm lỗ hổng.
Phương pháp tiếp cận theo từng lớp từ thụ động đến chủ động, kết hợp các nguồn dữ liệu như crt.sh, Wayback Machine, CommonCrawl cho thấy hiệu quả cao trong việc vạch rõ bề mặt tấn công (attack surface) tiềm năng của một hệ thống. Kết quả này có thể tiếp tục được sử dụng để phục vụ quá trình khai thác, phát hiện lỗ hổng, và báo cáo bảo mật chuyên sâu.
## H. Tài liệu tham khảo
* WHOIS Record (Cập nhật lần cuối: 25/07/2025)
* [MarkMonitor - Nhà đăng ký tên miền](https://www.markmonitor.com)
* [ICANN WHOIS](http://wdprs.internic.net/)
* [EPP Status Codes - ICANN](https://www.icann.org/resources/pages/epp-status-codes)
* https://www.kali.org/tools/dirsearch/
* https://infosecwriteups.com/recon-everything
* https://www.cobalt.io/blog/scope-based-recon-smart-recon-tactics
