# pt26
# Phong Thủy Lê Gia

Ứng dụng web tra cứu phong thủy và lưu hồ sơ bất động sản.

## Chạy dự án với phân tích AI

1. Cài đặt dependencies:
   ```bash
   npm install
   ```
2. Tạo file `.env` từ mẫu:
   ```bash
   cp .env.example .env
   # chỉnh AI_API_KEY=... với khóa OpenAI của bạn
   ```
3. Khởi động server:
   ```bash
   npm start
   ```
4. Mở trình duyệt tại [http://localhost:3000](http://localhost:3000) và sử dụng nút **Phân tích phong thủy**. Phần “Phân tích AI” sẽ hiển thị lời giải thích từ mô hình ngôn ngữ.

## Ghi chú

- Server sử dụng biến môi trường `AI_API_KEY` để gọi API OpenAI.
- Thư mục `node_modules` và file `.env` đã được bỏ qua khỏi Git (`.gitignore`).
