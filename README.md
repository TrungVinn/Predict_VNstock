# Dự Đoán Cổ Phiếu VNstock Bằng Linear Regression và LSTM

## Mô tả dự án

Dự án này sử dụng hai phương pháp phổ biến trong dự đoán giá cổ phiếu: **Linear Regression** và **LSTM (Long Short-Term Memory)** để dự đoán giá cổ phiếu VNstock. Cả hai phương pháp đều được sử dụng để phân tích dữ liệu thời gian và dự đoán xu hướng giá trong tương lai dựa trên dữ liệu lịch sử.

## Mục tiêu

- Sử dụng **Linear Regression** để xây dựng một mô hình đơn giản cho dự đoán giá cổ phiếu.
- Sử dụng **LSTM**, một loại mạng neural phù hợp với dữ liệu chuỗi thời gian, để cải thiện khả năng dự đoán.
- So sánh và đánh giá hiệu suất của hai phương pháp này.

## Các bước thực hiện

1. **Thu thập dữ liệu**: Dữ liệu giá cổ phiếu VNstock được thu thập bằng thư viện VNstock của python.
2. **Tiền xử lý dữ liệu**: Làm sạch dữ liệu, chuẩn hóa, và tách thành các tập huấn luyện và kiểm tra.
3. **Xây dựng mô hình Linear Regression**:
   - Sử dụng thư viện Scikit-learn để xây dựng mô hình Linear Regression.
   - Huấn luyện mô hình trên dữ liệu lịch sử.
   - Dự đoán giá và đánh giá hiệu suất mô hình bằng cách tính các chỉ số như MSE, RMSE, MAE.
4. **Xây dựng mô hình LSTM**:
   - Sử dụng thư viện Keras/TensorFlow để xây dựng mô hình LSTM.
   - Xử lý dữ liệu chuỗi thời gian để phù hợp với mô hình LSTM.
   - Huấn luyện mô hình và thực hiện dự đoán.
   - Đánh giá mô hình tương tự như Linear Regression.
5. **So sánh kết quả**: So sánh các mô hình về độ chính xác và hiệu suất dựa trên các chỉ số đánh giá.

## Yêu cầu hệ thống

- Python 3.x
- Các thư viện cần cài đặt:
  - pandas
  - numpy
  - scikit-learn
  - tensorflow (Keras)
  - matplotlib
  - seaborn

Cài đặt các thư viện thông qua pip:

```bash
pip install pandas
....

```


## Kết quả

- Đồ thị so sánh giữa giá thực tế và giá dự đoán sẽ được vẽ ra để bạn có thể dễ dàng quan sát.
- Hiệu suất giữa hai phương pháp Linear Regression và LSTM sẽ được so sánh.

## Tác giả

Dự án được thực hiện bởi Trung Vĩnh, dự án cuối kì môn Machine Learning.



