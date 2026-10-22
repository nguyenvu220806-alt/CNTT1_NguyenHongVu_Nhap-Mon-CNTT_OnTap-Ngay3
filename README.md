# Website Trung Tam Tieng Anh (TTA)

Dự án **website đăng ký khoá học** của trung tâm tiếng Anh TTA, làm trong môn *Nhập môn Công nghệ thông tin*. Repo lưu tài liệu khoá học, lịch học, log hệ thống và bảng học phí tháng 10 chuẩn bị gửi kế toán.

## Cấu trúc thư mục

| Thư mục | Nội dung |
|---------|----------|
| docs | Lịch học của các lớp |
| media | Logo trung tâm và ảnh lớp học |
| data | Danh sách học viên khoá 3, bảng học phí tháng 10 |
| logs | Log truy cập website, log thanh toán và các file báo cáo |
| archive | Bản sao lưu logo và ảnh lớp học |

## Quy trình đăng ký học tại TTA

1. Học viên xem lịch học trong thư mục `docs` để chọn khoá phù hợp.
2. Đăng ký khoá và nhận mã đăng ký (DK001, DK002...).
3. Thanh toán học phí qua cổng thanh toán của trung tâm.
4. Nhận biên lai qua email và chờ ngày khai giảng.

## Lệnh hay dùng

```shell
Get-ChildItem -Recurse -Force
```

## Việc cần làm

- [x] Tổ chức lại thư mục dự án
- [x] Lọc log và tạo báo cáo lỗi, cảnh báo
- [ ] Hoàn thiện bảng học phí tháng 10
- [ ] Chạy chính thức website

> Lưu ý: file `.env` chứa dữ liệu bí mật của dự án, tuyệt đối không upload lên GitHub.