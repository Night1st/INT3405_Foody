# Báo cáo bài tập lớn nhóm 16 - Sentiment Analysis Foody

---

## Thành viên

- Ngô Đức Mạnh
- Nguyễn Phú Đức
- Phan Đức Việt

## Đề tài nhóm
- Tiêu đề: Phân tích cảm xúc(Sentiment Analysis)
- Mô tả: Phân tích cảm xúc dựa trên các review của khách hàng qua ứng dụng Foody.

## Model và thư viện mà nhóm sử dụng:
- Nhóm em đã thống nhắt sử dụng model CNN-LSTM
- Ngoài các thư viện cần thiết như numpy, pandas, tensorflow, bọn em cũng sử dụng thư viện pyvi từ Việt Nam để tách từ Tiếng Việt
- Bọn em sử dụng kaggle để chạy code vì kaggle có lượng RAM đủ để train maodel so với colab.
- Link kaggle: 

## Cách chạy để có mô hình submit
- Bọn em tạo ra 2 mảng, 1 mảng chứa revId từ file test, 1 mảng chứa rating của các comment trên file test
- Bọn em lấy dữ liệu model sau khi train 10 epochs, sau đó test từ file test. Với mỗi rating của mỗi comment mà máy cho ra được, nó sẽ lưu theo thứ tử vào mảng rating.
