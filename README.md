# Shopee-statistics
Thêm Bookmark vào Trình duyệt
Bước 1: Tạo Bookmark
Mở trình duyệt (Chrome, Firefox, Edge, v.v...).

Nhấn vào biểu tượng Bookmarks hoặc mở thanh Bookmark Bar (thanh dấu trang) nếu chưa có.

Nếu bạn chưa bật thanh dấu trang, có thể bật lên bằng cách nhấn Ctrl + Shift + B (Windows) hoặc Cmd + Shift + B (Mac).
Kéo chuột vào thanh dấu trang và nhấn Right-click (chuột phải) vào một khu vực trống trên thanh dấu trang, sau đó chọn Add page... hoặc Add bookmark....

Bước 2: Thêm Bookmark với Đoạn Mã JavaScript
Trong hộp thoại hiện lên, điền thông tin như sau:

Name: Tên bookmark mà bạn muốn (Ví dụ: "Chạy Mã Shopee").
URL: Dán đoạn mã JavaScript sau vào ô URL:
javascript:(function(){
  fetch("https://raw.githubusercontent.com/s4ngnm/Shopee-statistics/refs/heads/main/thong-ke-chi-tieu-shopee.js")
  .then(r => r.text())
  .then(eval)
  .catch(e => console.error("Lỗi:", e));
})();
Nhấn Save hoặc Add để lưu bookmark.

Bước 3: Chạy Đoạn Mã
Để chạy đoạn mã JavaScript, chỉ cần nhấn vào bookmark mà bạn vừa tạo.
