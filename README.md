# ArtGroup

## 1. Giới thiệu dự án

### 1.1 Giới thiệu cửa hàng vật tư nông nghiệp ART GROUP

Cửa hàng ART GROUP đang kinh doanh các loại mặt hàng nông nghiệp như: Phân Bón Lá, Thuốc Trừ Sâu, Thuốc Diệt Cỏ, Thuốc Kích Thích Sinh Trưởng,… Việc quản lý sản phẩm, hóa đơn, dư nợ, khách hàng và doanh thu hiện nay đang thực hiện thông qua Excel. Tuy nhiên, cửa hàng đang gặp khó khăn khi số lượng khách hàng và sản phẩm ngày càng nhiều, dữ liệu ngày càng lớn, dẫn đến các vấn đề:

- Dễ sai sót khi tính toán.
- Khó quản lý kho sản phẩm và hạn sử dụng.
- Khó tra cứu hoặc sửa đổi dữ liệu.

### 1.2 Yêu cầu của cửa hàng

Cửa hàng ART GROUP mong muốn xây dựng một phần mềm để giải quyết các khó khăn trên.

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

## 4. Đóng góp

Chúng tôi luôn hoan nghênh sự đóng góp từ cộng đồng. Để tham gia đóng góp:

1. Fork repository này.
2. Tạo một nhánh mới:
   ```bash
   git checkout -b feature/tinh-nang-moi
   ```
3. Commit các thay đổi của bạn:
   ```bash
   git commit -m "Thêm tính năng mới"
   ```
4. Push nhánh của bạn:
   ```bash
   git push origin feature/tinh-nang-moi
   ```
5. Tạo một Pull Request.

## 5. Giấy phép

Dự án này được phân phối theo giấy phép MIT. Xem chi tiết tại [LICENSE](LICENSE).

## 6. Liên hệ

Nếu bạn có bất kỳ câu hỏi hoặc ý kiến đóng góp nào, vui lòng liên hệ với chúng tôi qua:

- Email: [your-email@example.com](mailto:your-email@example.com)
- GitHub: [PhucVinhDEV](https://github.com/PhucVinhDEV)

Cảm ơn bạn đã quan tâm đến ArtGroup!
