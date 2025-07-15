# Cham-Cong

## Chức năng chính

- Đăng nhập cho nhân viên và admin (mã nhân viên, mật khẩu/PIN)
- Tạo tài khoản mới (chỉ admin)
- Danh sách nhân viên (chỉ admin, có thể sửa/xóa)
- Chấm công: Check-in, Check-out cho nhân viên
- Chấm công bù: Admin có thể thêm công cho nhân viên (chọn mã nhân viên, nhập thời gian)
- Bảng chấm công: Hiển thị chi tiết từng ca làm, tổng số giờ/tháng
- Xuất Excel: Admin xuất báo cáo chấm công chi tiết theo tháng
- Tổng hợp giờ làm/tháng cho từng nhân viên
- Lịch sử đăng nhập (chỉ admin)
- Giao diện responsive, dễ sử dụng trên máy tính và điện thoại

## Hướng dẫn sử dụng

1. **Đăng nhập**

   - Nhân viên và admin đăng nhập bằng mã nhân viên và mật khẩu.
   - Tài khoản admin mặc định: mã `admin`, mật khẩu `admin`.

2. **Chấm công**

   - Nhân viên: Bấm Check-in khi bắt đầu làm, Check-out khi kết thúc ca.
   - Không thể check-in mới nếu chưa check-out ca trước.

3. **Chấm công bù (chỉ admin)**

   - Bấm nút "Chấm công bù cho nhân viên".
   - Chọn mã nhân viên, nhập thời gian check-in/check-out, bấm Lưu.

4. **Quản lý nhân viên (chỉ admin)**

   - Tạo, sửa, xóa tài khoản nhân viên.

5. **Xuất báo cáo**

   - Admin chọn tháng và bấm Xuất Excel để tải file báo cáo chi tiết.

6. **Tổng hợp giờ làm**

   - Xem tổng số giờ làm trong tháng ở cuối bảng chấm công (nhân viên) hoặc bảng tổng hợp (admin).

7. **Lịch sử đăng nhập**
   - Admin xem lịch sử đăng nhập của nhân viên (thời gian, vị trí).

## Lưu ý

- Dữ liệu lưu trữ qua SheetDB (Google Sheet).
- Đảm bảo nhập đúng mã nhân viên và mật khẩu khi đăng nhập.
