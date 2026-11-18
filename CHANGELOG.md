# Reverse: 1999 Việt Hóa — Nhật Ký Cập Nhật

## [v3.9.3] — 2026-11-18
- Nâng cấp toàn bộ gói dữ liệu dịch sang định dạng mã hóa gọn nhẹ (`viethoa.dat`) 
- Cập nhật bộ cài đặt tự động & thủ công tương thích đầy đủ với gói dữ liệu mới (chuẩn `x86_64` tương thích mọi CPU Intel/AMD và Steam).

## [v3.9.2.1] — 2026-11-18
- Cải thiện chất lượng bản dịch, rà soát sửa các đoạn lỗi dấu, sót chữ và chưa tự nhiên.

## [v3.9.2] — 2026-11-18
- Sửa lỗi văng game ở đoạn mở đầu / màn hình nhập tên cho người chơi mới (đặc biệt bản Steam).
- Cải thiện độ ổn định khi chạy trên nhiều máy khác nhau.

## [v3.9.1] — 2026-11-18
- Sửa lỗi `UnityCrashHandler64.exe (0xc0000142)` và tình trạng cài xong vẫn ra tiếng Anh trên các CPU không hỗ trợ AVX-512 (build lại `version.dll` theo chuẩn `x86_64` phổ thông).
- Lọc tiến trình chỉ gắn hook vào `reverse1999.exe` và chuyển khởi tạo hook ra thread riêng để tránh xung đột lúc khởi chạy.
- Bổ sung bản dịch cho phần cốt truyện nhân vật, phụ bản, khám phá và sự kiện phụ còn sót.
- Xóa các file log / config thừa trong gói tải về.

## [v3.9] — 2026-11-15
- **Tương thích phiên bản game 3.9**.
- **100% Cốt truyện toàn diện:** Đạt 165.378/165.378 câu trên toàn bộ 2.281 file cốt truyện (Cốt truyện chính, Sự kiện, Truyện nhân vật, Mùa giải, Phụ bản).
- **100% Giao diện & Dữ liệu:** 152.850 dòng dịch (Menu, Kỹ năng, Kho đồ, Hồ sơ nhân vật, Trang phục, Dữ liệu thẻ bài).
- **100% Thoại nhân vật:** 7.274 câu phụ đề tiếng Việt (sảnh chính, tương tác, trận đấu).
- **100% Tài liệu & Cutscene:** 367 tài liệu lore, video mở đầu và toàn bộ hoạt cảnh trong game.
- **Cài đặt 1-Click an toàn:** Proxy hook in-memory, không can thiệp server, không sửa file gốc của game.
