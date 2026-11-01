# <MSHV>_DataViz_Midterm

Trang web phân tích tương tác bộ dữ liệu Urban Retail Sales – HCMC 2025 (240 giao dịch).
Một file `index.html` duy nhất: HTML + CSS + JavaScript, dữ liệu đã nhúng sẵn, biểu đồ vẽ bằng Plotly.js (CDN).

## Trước khi nộp

1. Mở `index.html`, tìm dòng (gần cuối file):
   `const STUDENT = { name: 'Họ và tên sinh viên', mshv: 'MSHV', course: 'Data Visualization' };`
   và điền họ tên, MSHV của bạn. Tiêu đề trang sẽ tự đổi thành `<MSHV>_DataViz_Midterm`.
2. Đổi tên thư mục này thành `<MSHV>_DataViz_Midterm` (ví dụ `2312001_DataViz_Midterm`).
3. Mở `index.html` bằng trình duyệt để kiểm tra (cần Internet để tải Plotly.js, font và nền bản đồ).

## Deploy lên Vercel

1. Tạo repo GitHub tên `<MSHV>_DataViz_Midterm`, đưa `index.html` (và README này) lên gốc repo.
2. Vào https://vercel.com → Add New → Project → Import repo vừa tạo.
3. Framework Preset: **Other**. Không cần Build Command hay Output Directory. Bấm **Deploy**.
4. Mở URL Vercel cấp (dạng `https://<ten-project>.vercel.app`), kiểm tra lại trên một thiết bị khác.
5. Tạo file `<MSHV>.pdf` gồm họ tên, MSHV và URL (dạng link bấm được) rồi nộp trên Moodle.

## Cấu trúc trang

1. Giới thiệu và tóm tắt điều hành
2. Dữ liệu và phương pháp (từ điển dữ liệu, xử lý giá trị thiếu, cách sử dụng)
3. Tổng quan doanh số (KPI, danh mục, sản phẩm, tỷ trọng, cửa hàng, bản đồ)
4. Xu hướng theo thời gian (tháng/quý, danh mục theo quý, thứ trong tuần)
5. Khách hàng và giao dịch (bản đồ nhiệt, thanh toán, quy mô đơn, giao hàng và đánh giá)
6. Quan hệ và mẫu hình (ma trận tương quan, giảm giá, giao dịch lỗ, tọa độ song song)
7. Tám insight chính
8. Kết luận và khuyến nghị

## Tương tác

Bộ lọc toàn cục (cửa hàng, danh mục, nhóm khách, thanh toán, khoảng tháng) cập nhật 19 biểu đồ và 8 thẻ KPI;
hover, chú giải tương tác, zoom/pan, click liên kết giữa các biểu đồ, brush trên biểu đồ phân tán và tọa độ song song.
