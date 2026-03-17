# Laptop Market Analysis 2026 (Synthetic Data)

## 👤 Thông tin sinh viên
- **Họ tên:** Trịnh Xuân Thắng
- **MSSV:** B23DCCN757
- **Lớp:** INT13187-20252-21
- **Học phần:** Thực tập Cơ sở
- **Giảng viên hướng dẫn:** Thầy Đặng Ngọc Hùng

---

## 🎯 Mục tiêu dự án
Dự án tập trung vào việc nghiên cứu và phân tích các yếu tố ảnh hưởng đến giá bán máy tính xách tay trong năm 2026. Thay vì sử dụng dữ liệu có sẵn, dự án áp dụng phương pháp **Synthetic Data Generation** (Tạo dữ liệu giả lập) để chủ động xây dựng các kịch bản phân tích, từ đó rèn luyện tư duy xử lý dữ liệu Backend và phân tích thống kê.

### Kỹ năng trọng tâm:
1. **Python (Pandas/Numpy):** Tiền xử lý, làm sạch và biến đổi dữ liệu thô.
2. **Data Visualization (Seaborn/Matplotlib):** Trực quan hóa các Insights thu được từ dữ liệu.

---

## 📂 Cấu trúc Repository
Dự án được tổ chức theo tiêu chuẩn quản lý mã nguồn và tài liệu nghiên cứu:
- `data/`: Chứa file dữ liệu giả lập `laptop_data_2026.csv`.
- `docs/`: Nhật ký thực tập và ghi chú học tập hàng tuần (Quy trình Đọc -> Hiểu -> Làm).
- `notebooks/`: Các file Jupyter Notebook thực hiện code phân tích.
- `src/`: Mã nguồn Python (Script tạo dữ liệu và Pipeline xử lý).
- `reports/`: Lưu trữ các biểu đồ và hình ảnh kết quả phân tích.
- `timeline-08tuan.md`: Kế hoạch chi tiết và cập nhật tiến độ thực hiện.

---

## 🚀 Quy trình thực hiện (Data Pipeline)
1. **Khởi tạo dữ liệu:** Sử dụng Python để giả lập 200 bản ghi dữ liệu với các thuộc tính: Brand, Type, RAM, Storage, Rating và Price.
2. **Xử lý logic:** Thiết lập các mối tương quan thực tế (Ví dụ: RAM cao hoặc dòng máy Gaming sẽ có mức giá cao hơn).
3. **Thống kê mô tả:** Sử dụng Pandas để tính toán các chỉ số xu hướng trung tâm (Mean, Median) và độ phân tán (Std).
4. **Trực quan hóa:** (Đang triển khai) Xây dựng các biểu đồ cột và biểu đồ tán xạ để tìm kiếm Insights.

---

## 📊 Kết quả đạt được (Cập nhật Tuần 3)
- Đã hoàn thành bộ dữ liệu giả lập sạch 100%, sẵn sàng cho các mô hình phân tích nâng cao.
- **Insight sơ bộ:** Dữ liệu cho thấy sự phân hóa rõ rệt giữa các hãng, trong đó Apple chiếm lĩnh phân khúc cao cấp với mức giá trung bình vượt trội.
- Đã thiết lập xong hệ thống ghi chú nghiên cứu (docs) cho 3 tuần đầu tiên.

---

## 🛠 Hướng dẫn sử dụng
1. **Xem tài liệu:** Truy cập thư mục `docs/` để xem quá trình nghiên cứu hàng tuần.
2. **Chạy code:** - Mở các file trong `notebooks/
