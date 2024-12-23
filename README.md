# Phân Loại Email Sử Dụng Học Máy và Học Sâu

## Mô tả dự án

Trong thời đại công nghệ số, email vẫn là một phương thức liên lạc phổ biến nhờ tính tiện lợi, chi phí thấp và khả năng truyền tải nhanh chóng. Tuy nhiên, email rác (spam) đang trở thành vấn đề lớn, gây khó khăn trong giao tiếp và tiềm ẩn nhiều nguy cơ bảo mật. Theo thống kê, khoảng 40% tổng số email trên toàn cầu là thư rác, tương đương 15,4 tỷ email mỗi ngày. Điều này dẫn đến thiệt hại ước tính 355 triệu USD mỗi năm [4].

Dự án này nhằm xây dựng một hệ thống phân loại email hiệu quả và chính xác bằng cách áp dụng các mô hình học máy (Machine Learning) và học sâu (Deep Learning). Hệ thống không chỉ có giá trị học thuật mà còn mang tính ứng dụng cao, góp phần bảo vệ thông tin cá nhân, tổ chức và tối ưu hóa trải nghiệm người dùng trong môi trường số.

---

## Mục tiêu

- Phân loại email thành hai loại: **Spam (thư rác)** và **Ham (thư hợp lệ)**.
- Tăng cường khả năng bảo mật thông tin và cải thiện hiệu quả sử dụng email.
- Ứng dụng các thuật toán học máy và học sâu để đạt độ chính xác cao trong phân loại.

---

## Phương pháp

### 1. **Thu thập và tiền xử lý dữ liệu**
- Thu thập dữ liệu email từ các nguồn đáng tin cậy.
- Tiền xử lý dữ liệu: làm sạch, chuẩn hóa văn bản và tạo tập dữ liệu huấn luyện.

### 2. **Mô hình học máy được sử dụng**
Chúng tôi áp dụng các thuật toán học máy phổ biến để phân loại email:
- **Gaussian Naive Bayes (NB)**
- **XGBoost**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest (RF)**
- **Logistic Regression**

### 3. **Mô hình học sâu được sử dụng**
Các mô hình học sâu hiện đại được đề xuất bao gồm:
- **XLM-Roberta**
- **CNN-BiLSTM**
- **CNN-BiRNN**

---

## Tệp trong dự án

- `mc-final-ML.ipynb`: Triển khai các thuật toán học máy để phân loại email.
- `mc-final-bert-lstm-rnn.ipynb`: Triển khai các mô hình học sâu (Deep Learning) để cải thiện độ chính xác phân loại.
- `README.md`: Tài liệu giới thiệu dự án.

---

## Giá trị và ý nghĩa

- **Học thuật**: Kết hợp các thuật toán Machine Learning và Deep Learning trong giải quyết bài toán thực tiễn.
- **Thực tiễn**: 
  - Nâng cao hiệu quả phân loại email.
  - Bảo vệ thông tin cá nhân và tổ chức khỏi các rủi ro bảo mật.
  - Góp phần xây dựng môi trường số an toàn và hiệu quả hơn.

---

## Các tài liệu tham khảo

1. [2] Định nghĩa và khái niệm về email rác.
2. [3] Các mối nguy hiểm từ email rác: lừa đảo trực tuyến, phát tán phần mềm gián điệp, quảng cáo.
3. [4] Thống kê về tỷ lệ email rác và thiệt hại kinh tế hàng năm.
4. [5], [6], [7] Các thuật toán học máy được ứng dụng trong phân loại email.
5. [8] Các mô hình học sâu tiên tiến: XLM-Roberta, CNN-BiLSTM, CNN-BiRNN.