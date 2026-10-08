# COVID-19 Vaccination Progress Visualization (`covid19-vaccination-progress-viz`)

Dự án phân tích và trực quan hóa dữ liệu tiến độ tiêm chủng vắc-xin COVID-19 trên toàn cầu

## Tổng quan
Repository này lưu trữ quy trình xử lý dữ liệu chuỗi thời gian (time-series) và xây dựng bảng điều khiển tương tác (interactive dashboard) nhằm theo dõi, so sánh tốc độ và tỷ lệ bao phủ vắc-xin COVID-19 giữa các quốc gia và khu vực[cite: 1].

## Tính năng chính
* **Tiền xử lý & Làm sạch dữ liệu:** Chuẩn hóa dữ liệu tiêm chủng theo thời gian và khu vực địa lý.
* **Trực quan hóa đa chiều:** Phân tích tổng số liều tiêm, tỷ lệ dân số đã tiêm chủng (ít nhất 1 mũi & đầy đủ) và tốc độ tiêm chủng hàng ngày.
* **Dashboard tương tác:** Cung cấp góc nhìn trực quan về sự phân bổ và tiến độ tiêm chủng trên toàn thế giới.

## Công nghệ & Công cụ
* **Xử lý & Phân tích dữ liệu:** Python, R
* **Trực quan hóa:** Tableau / Plotly

## Hướng dẫn sử dụng
1. **Clone repository (nhánh `main`):**
   ```bash
   git clone <repository-url>
   cd covid19-vaccination-progress-viz
   ```
2. Chạy kịch bản xử lý dữ liệu: Thực thi các script tiền xử lý để tạo tập dữ liệu sạch.
3. Xem trực quan hóa: Mở file báo cáo/dashboard hoặc chạy script hiển thị biểu đồ tương ứng.
