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
Em nhận thấy việc học về mô hình CIA rất quan trọng vì nó là kim chỉ nam cho mọi hoạt động an toàn thông tin. Qua bài Lab 01, em đã hiểu rõ cách phân biệt giữa tính bảo mật, tính toàn vẹn và tính sẵn sàng. Việc thực hành xác định các Assets và đưa ra các biện pháp Mitigation giúp em có cái nhìn thực tế hơn về các lỗ hổng hệ thống. Đây là những kiến thức nền tảng vô cùng hữu ích cho công việc của em sau này.

## 5. Bonus Flag
Flag của em: FIT4012{A-C-B-I-C-A}
