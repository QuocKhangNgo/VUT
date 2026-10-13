# VUT — Bay qua giới hạn

Website tiếng Việt giới thiệu dự án thương hiệu giao hàng bằng drone, kèm tạo và theo dõi đơn mô phỏng. HTML/CSS/JavaScript thuần, không cần cài thư viện.

## Xem website

Mở `index.html` hoặc chạy `python3 -m http.server 8000` trong thư mục này và truy cập `http://localhost:8000`.

## Đưa lên GitHub Pages

1. Tạo repository GitHub, ví dụ `vut-website`.
2. Upload toàn bộ **nội dung** thư mục này vào gốc repository; giữ nguyên thư mục `assets`.
3. Mở **Settings → Pages**, chọn **Deploy from a branch**.
4. Chọn nhánh `main`, thư mục `/ (root)`, bấm **Save**.
5. URL thường là `https://TEN-TAI-KHOAN.github.io/vut-website/`.

## Cấu trúc

- `index.html`: nội dung và bố cục.
- `style.css`: bảng màu, responsive và giao diện.
- `app.js`: menu mobile, tạo đơn demo, theo dõi hành trình.
- `assets/`: logo và poster do người dùng cung cấp.

## Nội dung cần xác nhận trước khi triển khai dịch vụ thật

Trang hiện là đồ án; các thông số 8 kg và 5–10 km là đề xuất. Không có nhận đơn thực tế, thanh toán, vị trí GPS hoặc gửi dữ liệu về máy chủ. Đơn demo lưu trên trình duyệt, tối đa 30 đơn. Không sử dụng số điện thoại, email hoặc website trên poster làm liên hệ dịch vụ khi chưa xác minh quyền sở hữu. Poster giữ nguyên bản người dùng cung cấp.

Nếu triển khai dịch vụ thực tế, cần thay thông số concept bằng thông số đã kiểm chứng, thêm thông tin liên hệ chính thức và hệ thống xử lý đơn phù hợp.
