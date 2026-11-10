# bai6.3
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.3: HỆ THỐNG QUẢN LÝ CÔNG VIỆC & TIẾN ĐỘ DỰ ÁN (PROJECT & TASK MANAGEMENT)
---

## KẾT QUẢ THỰC HÀNH
1. Màn hình Chính / Tổng quan hệ thống:<img width="1345" height="1016" alt="GD" src="https://github.com/user-attachments/assets/eee6ca7c-f1e7-4520-8ee8-1a08c50959e7" />

2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):<img width="1345" height="1015" alt="CN1" src="https://github.com/user-attachments/assets/5a486428-812f-4494-bfc3-334af679f1c4" />

3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):<img width="1347" height="1015" alt="CN2" src="https://github.com/user-attachments/assets/cab1ec8a-eddb-4c1e-b8f4-84423d276274" />

4. Màn hình Báo cáo - Thống kê:<img width="1330" height="1015" alt="CN3" src="https://github.com/user-attachments/assets/1070f3cc-180d-4dbf-9da7-da84a2e6d86b" />

5. Minh họa An toàn Dữ liệu (Phòng chống SQL Injection / Báo lỗi Transaction Rollback):<img width="1346" height="1016" alt="KQ" src="https://github.com/user-attachments/assets/50075bf5-9bfd-42ce-ad10-8c2811b56ddb" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
