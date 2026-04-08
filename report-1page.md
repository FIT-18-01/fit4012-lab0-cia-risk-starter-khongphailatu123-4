# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm sinh viên (điểm số, thông tin cá nhân)
- Tài khoản người dùng (giảng viên, sinh viên, admin)
- Hệ thống máy chủ lưu trữ và website quản lý điểm
**CIA mapping:**
- Sự cố A -> Confidentiality (Lộ thông tin điểm hoặc dữ liệu sinh viên)
- Sự cố B -> Integrity (Điểm số bị sửa đổi trái phép)
- Sự cố C -> Availability (Hệ thống không truy cập được khi cần)

**Phân tích sự cố B:**
- Threat: Hacker hoặc người dùng lợi dụng quyền truy cập để chỉnh sửa điểm
- Vulnerability: Hệ thống phân quyền chưa chặt chẽ, thiếu kiểm tra xác thực và không có log theo dõi thay đổi
- Mitigation: Áp dụng phân quyền rõ ràng (RBAC), sử dụng xác thực hai lớp (2FA), ghi log hệ thống và kiểm tra định kỳ, đồng thời sao lưu dữ liệu thường xuyên

### 4. Kết luận ngắn
Qua bài lab này, em hiểu rõ hơn về mô hình CIA gồm bảo mật, toàn vẹn và sẵn sàng của hệ thống thông tin. Việc xác định assets giúp em biết được những thành phần quan trọng cần được bảo vệ. Khi phân tích sự cố, em nhận ra rằng mỗi sự cố đều liên quan đến threat và vulnerability cụ thể. Phần khó nhất là phân biệt rõ giữa các yếu tố trong CIA vì đôi khi chúng khá giống nhau. Bài lab cũng giúp em hiểu tầm quan trọng của các biện pháp bảo mật như phân quyền và xác thực. Đây là kiến thức nền tảng quan trọng trong an toàn thông tin.
