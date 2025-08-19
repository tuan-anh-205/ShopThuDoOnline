# ShopThuDoOnline
Ứng Dụng Thử Đồ Trực Tuyến với AI
Giới thiệu
Đây là một ứng dụng web đơn giản nhưng mạnh mẽ, sử dụng trí tuệ nhân tạo (AI) để cho phép người dùng thử trang phục trực tuyến. Bằng cách tải lên ảnh cá nhân và ảnh một món đồ, ứng dụng sẽ tạo ra một bức ảnh mới, ghép trang phục đó lên người dùng một cách chân thực nhất. Ứng dụng này mang lại trải nghiệm mua sắm và thử đồ thú vị, tiện lợi ngay tại nhà.

Công nghệ sử dụng
Dự án này được xây dựng hoàn toàn trên các công nghệ web cơ bản, không yêu cầu môi trường phát triển phức tạp:

HTML5: Cấu trúc chính của trang web.

CSS3 & Tailwind CSS: Tạo kiểu và thiết kế giao diện hiện đại, phản hồi tốt trên mọi thiết bị.

JavaScript: Xử lý logic phía client, tương tác với người dùng và gọi API.

Gemini API: Sử dụng mô hình AI đa phương thức gemini-2.0-flash-preview-image-generation để xử lý và tạo ảnh. Đây là trái tim của ứng dụng.

Các tính năng chính
Thử đồ ảo: Dễ dàng ghép trang phục từ một bức ảnh vào một người trong bức ảnh khác.

Xem trước ảnh: Cho phép người dùng xem ngay ảnh cá nhân và ảnh quần áo đã tải lên trước khi xử lý.

Tải ảnh về: Sau khi có kết quả, người dùng có thể tải bức ảnh đã được xử lý về máy.

Giao diện người dùng thân thiện: Thiết kế đơn giản, trực quan và hiện đại, giúp người dùng dễ dàng thao tác.

Hướng dẫn sử dụng
Mở tệp index.html trong trình duyệt của bạn.

Tải lên ảnh cá nhân: Nhấp vào nút "Chọn ảnh của bạn" và chọn một bức ảnh cá nhân có chứa người.

Tải lên ảnh trang phục: Nhấp vào nút "Chọn ảnh quần áo" và chọn một bức ảnh có trang phục bạn muốn thử.

Nhấn "Thử đồ ngay!": Ứng dụng sẽ gửi yêu cầu đến mô hình AI để xử lý. Vui lòng chờ một chút để quá trình hoàn tất.

Xem và tải kết quả: Bức ảnh kết quả sẽ hiển thị. Bạn có thể nhấp vào nút "Tải ảnh về" để lưu lại.

Ghi chú
Ứng dụng này yêu cầu kết nối internet để hoạt động.

Mã nguồn sử dụng một API key mẫu. Để sử dụng trong môi trường thực tế, bạn cần thay thế const apiKey = "YOUR_API_KEY_HERE"; bằng API key của riêng bạn.
