# E-commerce UI Improvement

## 1. Giới thiệu

Đây là giao diện danh sách sản phẩm thương mại điện tử dành cho ngành hàng mẹ và bé. Giao diện tập trung vào việc hiển thị sản phẩm, hình ảnh, giá khuyến mãi và phần trăm giảm giá theo bố cục rõ ràng, dễ xem.

## 2. Website tham khảo

- Tên website: Con Cưng
- URL: https://concung.com/
- Khu vực đã khảo sát: nhận diện thương hiệu, thẻ sản phẩm, cách hiển thị hình ảnh và khối giá sản phẩm.

## 3. Chức năng

- Hiển thị danh sách sản phẩm nổi bật.
- Hiển thị hình ảnh sản phẩm từ thư mục cục bộ `images/`.
- Hiển thị tên, giá bán, giá gốc và nhãn giảm giá.
- Hỗ trợ sản phẩm có hoặc không có giảm giá.
- Nút “Thêm vào giỏ” cho từng sản phẩm.
- Liên kết “Xem tất cả” và logo điều hướng về khu vực sản phẩm.
- Bố cục responsive từ 2 cột trên màn hình nhỏ đến 4 cột trên màn hình lớn.
- Hỗ trợ trạng thái hover, focus và `prefers-reduced-motion`.

## 4. Công nghệ

- HTML5
- CSS3
- SVG cho logo thương hiệu
- JPG cho ảnh sản phẩm

## 5. Cách chạy

Mở file [index.html](./index.html) bằng trình duyệt.

Không cần cài đặt package hoặc chạy máy chủ riêng.

## 6. Cải tiến đã thực hiện

Phiên bản ban đầu chỉ có các thẻ sản phẩm cơ bản, đường dẫn CSS chưa đúng và ảnh sử dụng placeholder từ bên ngoài. Các thay đổi đã thực hiện:

- Chuẩn hóa tên file HTML thành `index.html`.
- Liên kết stylesheet đúng tới `css/style.css`.
- Xây dựng hệ màu CONCUNG với nền hồng nhạt, màu thương hiệu, màu giá sale và viền thẻ.
- Thêm logo CONCUNG từ `images/logo-concung.svg`.
- Cải thiện bố cục thẻ, khoảng cách, bo góc, bóng đổ và hiệu ứng hover.
- Chuẩn hóa chiều cao tên sản phẩm bằng line clamp tối đa hai dòng.
- Căn chỉnh khối giá để các thẻ có bố cục đồng đều, kể cả sản phẩm không giảm giá.
- Thêm responsive grid cho nhiều kích thước màn hình.
- Tải ảnh sản phẩm về thư mục `images/` và chuyển sang định dạng JPG để sử dụng cục bộ.
- Bổ sung văn bản thay thế cho ảnh và thuộc tính hỗ trợ khả năng truy cập.

## 7. Hỗ trợ từ AI

AI đã hỗ trợ phân tích cấu trúc HTML/CSS, phát hiện lỗi đường dẫn và tên file, đề xuất bố cục responsive, chuẩn hóa CSS, tích hợp logo và thay thế ảnh placeholder bằng ảnh sản phẩm phù hợp.

Phần đã kiểm tra và điều chỉnh thủ công gồm nội dung tiếng Việt, tên sản phẩm, đường dẫn tài nguyên, định dạng ảnh JPG, bố cục HTML và việc kiểm tra hiển thị trong trình duyệt.
