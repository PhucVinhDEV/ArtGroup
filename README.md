# ArtGroup


#### Yêu cầu chức năng nghiệp vụ:

- Quản lý nhân viên.
- Quản lý nhà cung cấp.
- Quản lý phân loại sản phẩm.
- Quản lý sản phẩm.
- Quản lý nhập hàng.
- Quản lý xuất hàng.
- Quản lý danh mục sản phẩm.
- Thống kê hóa đơn nhập, xuất.
- Thống kê hàng hóa tồn kho, hạn sử dụng.
- Thống kê dư nợ, lợi nhuận.

#### Yêu cầu về bảo mật:

- Tất cả mọi thành viên phải đăng nhập mới sử dụng được phần mềm.
- Quản lý được phép thực hiện tất cả các chức năng.
- Nhân viên không được phép:
  - Xóa dữ liệu.
  - Xem thông tin về lợi nhuận.
  - Thêm nhân viên hoặc xem danh sách nhân viên.
  - Thêm nhà phân phối.

#### Yêu cầu về môi trường công nghệ:

- Ứng dụng phải được thực hiện với công nghệ Swing và JDBC.
- Sử dụng JDK 1.8 trở lên.
- Hệ quản trị cơ sở dữ liệu SQL Server 2008 trở lên.

## 2. Công nghệ sử dụng

- **Backend**: Java Swing, JDBC.
- **Database**: SQL Server.
- **Hosting**: Local hoặc mạng nội bộ.

## 3. Hướng dẫn cài đặt và chạy dự án

### Yêu cầu hệ thống

- JDK 1.8 hoặc cao hơn.
- SQL Server 2008 hoặc cao hơn.

### Cài đặt

1. **Clone repository**:
   ```bash
   git clone https://github.com/PhucVinhDEV/ArtGroup.git
   cd ArtGroup
   ```

2. **Cấu hình database**:
   - Tạo một cơ sở dữ liệu SQL Server mới.
   - Cập nhật thông tin kết nối trong file cấu hình của ứng dụng.

3. **Chạy ứng dụng**:
   - Biên dịch và chạy ứng dụng Java qua IDE hoặc dòng lệnh.



