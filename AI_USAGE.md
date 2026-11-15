# AI Usage Log

## 1. Công cụ AI

Tên công cụ: OpenAI Codex.

## 2. Mục đích sử dụng

- Phân tích cấu trúc giao diện HTML/CSS.
- Phát hiện và sửa lỗi tên file, đường dẫn stylesheet và đường dẫn ảnh.
- Đề xuất bố cục thẻ sản phẩm responsive.
- Hỗ trợ xây dựng hệ màu, typography, trạng thái hover/focus và khả năng truy cập.
- Tích hợp logo SVG và chuyển ảnh sản phẩm sang tài nguyên cục bộ định dạng JPG.
- Kiểm tra giao diện sau mỗi thay đổi bằng trình duyệt.

## 3. Prompt đã sử dụng

- Cung cấp HTML ban đầu của giao diện thẻ sản phẩm và yêu cầu cải thiện giao diện.
- Cung cấp các đoạn CSS thiết kế mới để tích hợp vào dự án.
- Cung cấp URL ảnh sản phẩm để thay thế ảnh placeholder.
- Yêu cầu dùng logo `concung.com` và tích hợp SVG logo vào trang.
- Yêu cầu kiểm tra thư mục `images` và trích các ảnh đang dùng trong `index.html` ra thư mục này.
- Yêu cầu chuyển các ảnh sản phẩm từ WebP sang JPG.
- Yêu cầu tạo và hoàn thiện tài liệu README và nhật ký sử dụng AI.

## 4. Kết quả AI đề xuất

- Tạo giao diện danh sách sản phẩm với màu thương hiệu CONCUNG.
- Tạo lưới responsive hai cột trên màn hình nhỏ, ba cột ở kích thước trung bình và bốn cột trên màn hình lớn.
- Đồng nhất chiều cao thẻ bằng cách giới hạn tên sản phẩm hai dòng và đặt khối giá ở cuối thẻ.
- Bổ sung giá sale, giá gốc, badge giảm giá và nút hành động.
- Sử dụng logo tại `images/logo-concung.svg`.
- Sử dụng bốn ảnh sản phẩm cục bộ tại `images/product-1.jpg` đến `images/product-4.jpg`.

## 5. Kiểm tra và điều chỉnh

- Kiểm tra tên file HTML và sửa từ phần mở rộng sai thành `index.html`.
- Kiểm tra đường dẫn CSS và sửa thành `css/style.css`.
- Loại bỏ metadata Word/HTML không liên quan khỏi CSS.
- Chuẩn hóa nội dung tiếng Việt bị lỗi mã hóa.
- Điều chỉnh HTML để khớp với các class CSS thực tế.
- Kiểm tra các đường dẫn ảnh cục bộ sau khi chuyển đổi sang JPG.
- Kiểm tra trang bằng trình duyệt và xác nhận logo, bốn ảnh sản phẩm, giá và nút đều hiển thị.
- Không sử dụng JavaScript hoặc framework vì giao diện hiện tại chỉ yêu cầu HTML5 và CSS3.

## 6. Phần tôi hiểu và có thể giải thích

- `product-grid` dùng CSS Grid và media query để thay đổi số cột theo chiều rộng màn hình.
- `product-card` dùng Flexbox để đẩy khối giá và nút xuống vị trí đồng đều.
- `product-name` dùng line clamp để giới hạn tên sản phẩm tối đa hai dòng.
- `price-block` phân biệt giá bán, giá gốc và phần trăm giảm giá.
- Logo được tải từ file SVG cục bộ bằng thẻ `img`.
- Ảnh sản phẩm được lưu trong thư mục `images/` và tham chiếu bằng đường dẫn tương đối.
- `:hover`, `:focus-visible` và `prefers-reduced-motion` giúp giao diện dễ dùng hơn và hỗ trợ khả năng truy cập.
