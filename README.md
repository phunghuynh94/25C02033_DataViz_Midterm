# <MSHV>_DataViz_Midterm

Trang web phân tích tương tác bộ dữ liệu Urban Retail Sales – HCMC 2025 (240 giao dịch).
Một file `index.html` duy nhất: HTML + CSS + JavaScript, dữ liệu đã nhúng sẵn, biểu đồ vẽ bằng Plotly.js (CDN).

## Thông tin học viên

Thông tin hiện được điền trong `index.html`: Huỳnh Minh Phụng, MSHV 25C02033. Tiêu đề trang tự đổi theo MSHV thành `25C02033_DataViz_Midterm`.

Trước khi nộp, mở `index.html` bằng trình duyệt để kiểm tra. Cần Internet để tải Plotly.js, font và nền bản đồ.

## Deploy lên Vercel

1. Tạo repo GitHub tên `<MSHV>_DataViz_Midterm`, đưa `index.html` (và README này) lên gốc repo.
2. Vào https://vercel.com → Add New → Project → Import repo vừa tạo.
3. Framework Preset: **Other**. Không cần Build Command hay Output Directory. Bấm **Deploy**.
4. Mở URL Vercel cấp (dạng `https://<ten-project>.vercel.app`), kiểm tra lại trên một thiết bị khác.
5. Tạo file `<MSHV>.pdf` gồm họ tên, MSHV và URL (dạng link bấm được) rồi nộp trên Moodle.

## Các mục phân tích

Điều hướng chia dashboard thành các mục riêng: giới thiệu, phương pháp, tổng quan doanh số, xu hướng theo thời gian, khách hàng, quan hệ giữa các biến, và insight cùng kết luận. Các liên kết từ insight mở đúng mục và biểu đồ liên quan. Bảng dữ liệu có tiêu đề, đơn vị đo, phạm vi và quy tắc sắp xếp.

## Tương tác

Bộ lọc toàn cục (cửa hàng, danh mục, nhóm khách, thanh toán, khoảng tháng) cập nhật 19 biểu đồ và 8 thẻ KPI;
hover, chú giải tương tác, zoom/pan, click liên kết giữa các biểu đồ, brush trên biểu đồ phân tán và tọa độ song song.
