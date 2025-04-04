# 💧 Dự đoán chất lượng nước bằng các mô hình học máy

## 📌 Giới thiệu

Dự án này nhằm mục tiêu xây dựng một hệ thống phân loại chất lượng nước dựa trên các chỉ số hóa học và vật lý trong mẫu. Sử dụng các mô hình học máy khác nhau, nhóm thực hiện đánh giá độ chính xác và hiệu quả của từng thuật toán để lựa chọn mô hình phù hợp nhất.

---

## 📊 Xử lý dữ liệu

- **Tiền xử lý**:
  - Kiểm tra và xử lý giá trị thiếu
  - Chuẩn hóa/chuẩn bị dữ liệu (nếu có)
  - Phân chia dữ liệu huấn luyện và kiểm tra bằng `train_test_split`
  
  Hình ảnh Thống kê mô tả các biến
![Ảnh chụp màn hình 2025-04-04 230016](https://github.com/user-attachments/assets/4a9858d5-d2f6-42c0-af06-d7126fd275b3)

---

## 🧠 Mô hình sử dụng

Các mô hình học máy được huấn luyện và so sánh bao gồm:

- **Support Vector Machine (SVC)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **XGBoost**

### 🎯 Đánh giá mô hình

- Sử dụng kỹ thuật **cross-validation**
- Đo lường hiệu quả qua độ chính xác (`accuracy_score`)
- Trực quan hóa kết quả bằng biểu đồ boxplot

---
