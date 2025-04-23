# ⚡ Hourly Energy Consumption Forecasting

Dự án này nhằm mục đích **dự báo lượng tiêu thụ điện năng theo giờ** dựa trên tập dữ liệu của hệ thống điện PJM (Hoa Kỳ). Dự án sử dụng nhiều phương pháp khác nhau từ mô hình thống kê đến deep learning.

## 📁 Cấu trúc thư mục

<pre>
ENERGY_CONSUMPTION/
├── Data_Science/
│   ├── data/                         # Chứa các file CSV đã xử lý từ PJM dataset
│   ├── Energy_consumption.ipynb     # Tổng hợp toàn bộ quá trình phân tích & trực quan hóa
│   ├── LSTM.ipynb                   # Dự báo với LSTM cơ bản
│   ├── LSTM_CONV.ipynb              # Dự báo với LSTM kết hợp CNN
│   ├── LSTM_ATTENTION.ipynb         # LSTM có Attention
│   ├── xgb_model.json               # Mô hình XGBoost đã train và lưu
│   └── energy.jpg                   
</pre>

## ✅ Cách sử dụng
1.	Tải tập dữ liệu từ Kaggle và đặt vào thư mục data/
2.	Mở các file .ipynb bằng Jupyter Notebook hoặc VSCode
3.	Chạy từng cell theo thứ tự để tái hiện kết quả

## 📈 Kết quả
- Mỗi notebook sẽ hiển thị **biểu đồ dự báo** và **chỉ số đánh giá** (RMSE, MAE…)
- Có thể dễ dàng mở từng notebook để chạy lại, sửa đổi, thử nghiệm thêm
