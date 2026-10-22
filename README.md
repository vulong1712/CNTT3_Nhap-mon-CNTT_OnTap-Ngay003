# Hệ thống quản lý trung tâm tiếng Anh
## Giới thiệu dự án 
Dự án Website Trung tâm Tiếng Anh: Hệ thống học bài **_trực tuyến_**, tra cứu thông tin học viên một cách **nhanh chóng**, **tiện lợi**, phù hợp với **mọi lứa tuổi** 
## Cấu trúc thư mục

| Thư mục | Nội dung |
| :---: | :---: |
| data/ | Chứa danh sách học viên và học phí |
| logs/ | Chứa các file nhật ký access.log và payment.log |
| docs/ | Chứa tài liệu hướng dẫn và lịch học |
|archive/| Lưu trữ dữ liệu sao lưu định kỳ và hồ sơ các khóa đào tạo cũ|

## Quy trình đăng ký học tại TTA
1. Học viên tham khảo danh sách khóa học và nhận tư vấn.
2. Điền thông tin đăng ký và chọn thời gian học.
3. Lựa chọn hình thức thanh toán học phí để hoàn tất đăng ký.

## Lệnh kiểm tra cấu trúc dự án
```powershell
Get-ChildItem -Recurse -Force
```

## Tasklist công việc
- [x] Khởi tạo cấu trúc thư mục dự án và file log
- [ ] Hoàn thiện báo cáo mục tiêu tháng 10
- [ ] Rà soát và cấu hình file `.gitignore` loại trừ file `.env`
