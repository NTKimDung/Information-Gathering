# Thu thập Google Hacking
Tên tài liệu: Thu thập thông tin từ website 'shopify.com' Thực hiện: Nguyễn Thị Kim Dung Cập nhật lần cuối: 28/07/2025
## 1. Mục tiêu 
Google Hacking (hay Google Dorking) là kỹ thuật sử dụng các toán tử tìm kiếm nâng cao của Google để thu thập thông tin nhạy cảm từ các website.
Mục tiêu của Google Hacking:
Tìm file cấu hình nhạy cảm (config.php, .env, .bak…)
Tìm thông tin đăng nhập rò rỉ (username/password)
Tìm các camera IP, thiết bị IoT mở
Tìm lỗi cấu hình web, backup bị lộ, hoặc directory index bị mở
## 2. Thực hiện truy vấn tìm kiếm trên Google
Khi thực hiện truy vấn:'site:shopify.com'
Kết quả là: Google sẽ trả về các liên kết công khai thuộc miền shopify.com đã được Google lập chỉ mục.
Ý nghĩa của kết quả:
Giúp hiểu được cấu trúc subdomain và thư mục của website.
Hỗ trợ quá trình dò tìm mục tiêu tiềm năng trong quá trình kiểm thử bảo mật (pentest).
Cho thấy Shopify cho phép Google index một số phần nhất định trên website.
Lưu ý: Các kết quả Google trả về không đồng nghĩa với tồn tại lỗ hổng, nhưng cung cấp gợi ý quan trọng để mở rộng điều tra.

