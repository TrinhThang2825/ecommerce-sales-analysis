# Phân tích Dữ liệu Thị trường Laptop 2026 (Synthetic Data)

## 👤 Thông tin sinh viên
- **Họ tên:** Trịnh Xuân Thắng
- **MSSV:** B23DCCN757
- **Lớp:** INT13187-20252-21
- **Học phần:** Thực tập Cơ sở
- **Giảng viên hướng dẫn:** Thầy Đặng Ngọc Hùng

---

## 🎯 Mục tiêu dự án
Dự án này tập trung vào việc áp dụng kỹ năng **Data Analysis** để nghiên cứu các yếu tố ảnh hưởng đến giá bán máy tính xách tay. Thay vì sử dụng dữ liệu có sẵn, dự án sử dụng phương pháp **Synthetic Data Generation** (Tạo dữ liệu giả lập) để chủ động xây dựng các kịch bản phân tích và kiểm chứng quy trình (Pipeline) xử lý dữ liệu.

### Kỹ năng trọng tâm:
- **Ngôn ngữ:** Python (Pandas, Numpy).
- **Phân tích:** Thống kê mô tả (Descriptive Statistics), Phân tích khám phá (EDA).
- **Công cụ:** Google Colab, GitHub, Markdown.

---

## 📂 Cấu trúc Repository
Dự án được tổ chức theo tiêu chuẩn để quản lý cả mã nguồn và tài liệu nghiên cứu:
- `data/`: Chứa file dữ liệu giả lập `laptop_data_2026.csv`.
- `docs/`: Nhật ký thực tập và ghi chú nghiên cứu hàng tuần (Đọc -> Hiểu -> Làm).
- `notebooks/`: Các file Jupyter Notebook thực hành trên Google Colab.
- `src/`: Mã nguồn Python tạo dữ liệu và các hàm xử lý.
- `reports/`: Các biểu đồ trực quan hóa và kết quả phân tích.
- `timeline-08tuan.md`: Kế hoạch và cập nhật tiến độ chi tiết.

---

## 🚀 Quy trình thực hiện (Pipeline)
1. **Khởi tạo dữ liệu:** Sử dụng Python để giả lập 200 bản ghi dữ liệu với các thuộc tính: Hãng, Loại máy, RAM, Storage, Rating và Price.
2. **Tiền xử lý:** Chuẩn hóa định dạng số, kiểm tra logic giữa các cột (ví dụ: RAM cao thì giá cao).
3. **Phân tích thống kê:** Tính toán các chỉ số xu hướng trung tâm (Mean, Median) và độ phân tán (Std).
4. **Trực quan hóa:** Xây dựng biểu đồ tương quan để rút ra Insights thị trường.

---

## 📊 Kết quả đạt được (Cập nhật Tuần 3)
- Đã xây dựng thành công bộ dữ liệu giả lập sạch 100%.
- Kết quả thống kê sơ bộ cho thấy sự phân hóa giá mạnh giữa các dòng Gaming và Office.
- Apple được giả lập là phân khúc cao cấp nhất với mức giá trung bình vượt trội.

---

## 🛠 Hướng dẫn chạy dự án
1. Clone repository: 
   ```bash
   git clone [https://github.com/TrinhThang2825/ThucTapCoSo_DataAnalysis_B23DCCN757.git](https://github.com/TrinhThang2825/ThucTapCoSo_DataAnalysis_B23DCCN757.git)
