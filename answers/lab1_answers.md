# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đinh Mạnh Tú

**MSSV:** 1871020614

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Cơ sở dữ liệu khách hàng (thông tin cá nhân, số điện thoại, địa chỉ)
- Asset 2:Tài khoản người dùng (username, password)
- Asset 3 (nếu có):Hệ thống máy chủ và website của công ty

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality (Rò rỉ thông tin khách hàng)
- Sự cố B ->Integrity (Dữ liệu bị sửa đổi trái phép)
- Sự cố C ->Availability (Hệ thống bị sập, không truy cập được)

---

## 3. Phân tích sự cố B
- Threat:Hacker hoặc người dùng nội bộ chỉnh sửa dữ liệu trái phép
- Vulnerability:Không kiểm tra quyền truy cập, thiếu cơ chế xác thực/ghi log
- Mitigation:
Áp dụng phân quyền (Role-based access control)
Sử dụng xác thực mạnh (2FA)
Ghi log và giám sát thay đổi dữ liệu
Backup dữ liệu thường xuyên

## 4. Reflection
Qua bài Lab 01 này, em đã nắm vững kiến thức về mô hình CIA và cách xác định các tài sản quan trọng (Assets) cần bảo vệ trong hệ thống thông tin. Em cũng hiểu rõ hơn về mối quan hệ giữa các lỗ hổng bảo mật và các mối đe dọa thực tế.
## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:FIT4012{A-C-B-I-C-A}

