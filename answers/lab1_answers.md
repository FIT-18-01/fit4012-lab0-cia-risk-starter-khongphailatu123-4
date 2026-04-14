# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đinh Mạnh Tú

**MSSV:** 1871020614

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
- Asset 1: Cơ sở dữ liệu khách hàng (thông tin cá nhân, số điện thoại, địa chỉ)
- Asset 2: Tài khoản người dùng (username, password)
- Asset 3: Hệ thống máy chủ và website của công ty

## 2. Mapping CIA
- Sự cố A -> Confidentiality (Rò rỉ thông tin khách hàng)
- Sự cố B -> Integrity (Dữ liệu bị sửa đổi trái phép)
- Sự cố C -> Availability (Hệ thống bị sập, không truy cập được)

## 3. Phân tích sự cố B
- Threat: Hacker hoặc người dùng nội bộ chỉnh sửa dữ liệu trái phép.
- Vulnerability: Hệ thống thiếu kiểm tra quyền truy cập chặt chẽ và không có cơ chế ghi log.
- Mitigation: Áp dụng phân quyền RBAC, xác thực 2 lớp và thực hiện sao lưu dữ liệu thường xuyên.

## 4. Reflection
Trong bài lab này, em đã học được cách áp dụng mô hình CIA vào thực tế. Em hiểu rằng tính bảo mật giúp ngăn chặn rò rỉ dữ liệu, tính toàn vẹn đảm bảo dữ liệu không bị sửa đổi trái phép và tính sẵn sàng giúp hệ thống luôn hoạt động. Việc phân tích rủi ro giúp em biết cách bảo vệ các tài sản quan trọng của hệ thống một cách hiệu quả hơn thông qua các biện pháp như phân quyền và ghi log.

---

## 5. Bonus Flag
Flag của em: FIT4012{A-C-B-I-C-A}
