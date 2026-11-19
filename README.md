# Nectar Chinese – My Vocabulary Garden

## Mở thử nhanh
- Giải nén thư mục.
- Mở `index.html` bằng trình duyệt hiện đại để dùng các chức năng cơ bản. IndexedDB cần trình duyệt hỗ trợ.
- Để cài PWA/offline ổn định, cần phục vụ thư mục qua HTTPS hoặc localhost (ví dụ GitHub Pages, Netlify, hoặc máy chủ local). Service Worker không chạy từ `file://`.

## Triển khai miễn phí
1. Tạo repository GitHub và tải toàn bộ 3 file/thư mục lên.
2. Vào Settings → Pages → Deploy from branch → chọn nhánh `main`, thư mục `/root`.
3. Mở URL HTTPS trên Chrome Android. Chọn menu ⋮ → Cài đặt ứng dụng/Thêm vào màn hình chính.

## Lưu trữ
- Dữ liệu lưu trong IndexedDB của trình duyệt trên thiết bị.
- Vào Cài đặt → Xuất JSON để sao lưu; dùng Nhập JSON để hợp nhất/khôi phục.
- CSV chỉ xuất bảng từ vựng.
- Không xóa dữ liệu website/trình duyệt khi chưa có bản sao lưu.
- Không có đồng bộ đám mây trong bản cá nhân offline-first này.

## Tính năng
Kho từ vựng CRUD, HSK 1–5, tìm kiếm/lọc, nhập nhanh, flashcard, 7 dạng trò chơi cơ bản, sổ ngữ pháp, thống kê, lịch ôn đơn giản, JSON/CSV, Light/Dark Mode, chủ đề màu và PWA cache.
