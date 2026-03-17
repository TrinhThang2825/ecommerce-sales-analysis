
# Nhật ký thực tập - Tuần 3: Thống kê mô tả (Descriptive Statistics)

## 1. Nội dung tìm hiểu (Đọc)
- **Pandas Statistics:** Tìm hiểu các hàm thống kê tích hợp như `.describe()`, `.mean()`, `.std()`.
- **Phân tích nhóm:** Cách sử dụng hàm `.groupby()` để so sánh các thuộc tính giữa các thương hiệu khác nhau.

## 2. Kết quả tìm hiểu (Hiểu)
- Hiểu được ý nghĩa của **Độ lệch chuẩn (Standard Deviation)**: Nếu độ lệch chuẩn của giá bán lớn, chứng tỏ hãng đó có nhiều phân khúc giá từ rẻ đến đắt.
- **Kết quả phân tích từ dữ liệu giả lập:**
    - Sau khi dùng hàm `.describe()`, em thấy giá trung bình của Laptop trong bộ dữ liệu là khoảng **18.500.000 VND**.
    - RAM phổ biến nhất được trang bị là **16GB**.
    - **Hãng Apple** có mức giá trung bình cao nhất (khoảng **27.000.000 VND**) do có cộng thêm chi phí thương hiệu trong logic tạo code.
    - Dòng máy **Gaming** thường đi kèm với RAM lớn (32GB, 64GB) và có mức giá cao hơn hẳn dòng máy **Office**.

## 3. Thực hiện (Làm)
- Chạy code thống kê trên Notebook và lưu lại các bảng dữ liệu kết quả.
- Ghi chú lại các "Insight" (nhận xét) quan trọng để chuẩn bị cho bước trực quan hóa biểu đồ ở tuần tiếp theo.
