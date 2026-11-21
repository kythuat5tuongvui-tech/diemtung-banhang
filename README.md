# Diêm Tùng Bán Hàng – Android

## Có trong bản khởi đầu
- Quét mã vạch bằng camera (ML Kit + CameraX).
- Tạo sản phẩm với mã, tên, giá nhập, giá bán.
- Ghi nhận nhập hàng và bán hàng, cập nhật tồn kho.
- Xem danh sách tồn kho, lịch sử bán, báo cáo doanh thu và lợi nhuận gộp.
- Dữ liệu lưu cục bộ bằng SQLite, dùng được không cần mạng.

## Tạo APK
1. Cài Android Studio bản mới trên máy tính.
2. Giải nén thư mục dự án.
3. Mở Android Studio > Open > chọn thư mục `DiemTungBanHang`.
4. Chờ Gradle đồng bộ và tải thư viện (cần Internet ở lần đầu).
5. Chọn Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK debug nằm tại `app/build/outputs/apk/debug/app-debug.apk`.

## Lưu ý trước khi dùng bán hàng thật
Đây là bản khởi đầu để thử quy trình, chưa phải bản phát hành thương mại. Báo cáo hiện là số liệu lũy kế; chưa có lọc theo ngày/tháng, hóa đơn in, quản lý khách hàng/nhà cung cấp, hoàn trả, xuất/nhập CSV và cơ chế sao lưu/khôi phục bên trong app. Cần kiểm thử kỹ trên điện thoại và hoàn thiện các mục này trước khi dùng làm sổ sách chính thức.
