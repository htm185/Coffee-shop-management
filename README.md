# Coffee Shop Management

Ứng dụng **quản lý quán cà phê** viết bằng **Java (Swing)**, kết nối **SQL Server** qua JDBC.

## Chức năng
- Đăng nhập
- Quản lý thức uống, bàn/đặt bàn
- Quản lý khách hàng, nhân viên
- Quản lý hóa đơn

## Công nghệ
- Java (Eclipse project)
- SQL Server + JDBC (`libs/sqljdbc4.jar`)
- Xuất PDF (iText) (`libs/itextpdf-5.5.9.jar`)

## Cài đặt & chạy
1) **Tạo CSDL**: chạy script `sql/SQLQuery1.sql` trên SQL Server (DB: `Quanlyquancaphe`).
2) **Cấu hình kết nối**: sửa `src/connectDB/ConnectDB.java`:
   - `user` / `password` cho SQL Server của bạn
3) **Chạy chương trình**: chạy file `src/main/main.java`.

## Thư mục chính
- `src/gui/`: giao diện
- `src/dao/`: xử lý DB
- `src/entity/`: model dữ liệu
- `sql/`: script database
- `libs/`: thư viện `.jar`
