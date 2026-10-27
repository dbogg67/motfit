# MotFit

Ứng dụng web tiếng Việt hỗ trợ lập lịch tập cá nhân, theo dõi thông số cơ thể, tra cứu bài tập, tính 1RM và đồng hồ nghỉ giữa hiệp.

## Chạy ứng dụng

Đây là ứng dụng HTML/CSS/JavaScript thuần. Mở `index.html` trong trình duyệt hoặc triển khai thư mục gốc lên Vercel dưới dạng website tĩnh.

## Lưu trữ dữ liệu hiện tại

Phiên bản hiện tại lưu dữ liệu ở trình duyệt bằng `localStorage`. Dữ liệu không tự đồng bộ giữa thiết bị hoặc tài khoản. Giao diện tài khoản trong ứng dụng chưa được nối với hệ thống xác thực/backend.

## Công nghệ

- HTML, CSS, JavaScript
- Tailwind CSS CDN, Google Fonts, Phosphor Icons, Tone.js CDN
- Vercel (static hosting)
- Neon Postgres project đã tạo; chưa tích hợp vào ứng dụng cho tới khi bổ sung API/backend và schema.

## Triển khai

Deploy thư mục gốc của repository trên Vercel. File entry point là `index.html`.
