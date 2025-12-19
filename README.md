## Computational Finance 📈

Dự án này tổng hợp các bài thực hành (Labs) trong khóa học Computational Finance, tập trung vào việc áp dụng toán học thống kê và lập trình Python để phân tích thị trường tài chính và xây dựng chiến lược giao dịch thuật toán.

## 🗂️ Danh mục nội dung các bài Lab
### [CF_Lab1_Lab2_Lab3.ipynb] - Nền tảng & Tín hiệu Alpha

- Thu thập dữ liệu: Tải dữ liệu OHLC và điều chỉnh giá (Adjusted Price) cho các sự kiện doanh nghiệp như chia tách cổ phiếu và cổ tức.

- Lợi nhuận (Returns): Tính toán Raw Returns và Log Returns để chuẩn hóa phân phối dữ liệu.
- Chỉ báo kỹ thuật: Hiện thực hóa các chỉ báo như SMA và Bollinger Bands.
- Chiến lược Momentum: Xây dựng chiến lược Long/Short dựa trên xếp hạng cổ phiếu theo quán tính giá.

### [CF_Lab4.ipynb] - Xử lý dữ liệu nâng cao & Hồi quy
- Xử lý Outliers: Phát hiện và xử lý các giá trị ngoại lai trong dữ liệu giá và lợi nhuận để tránh sai lệch mô hình.

- Kiểm định thống kê: Kiểm tra tính chuẩn (Normality) qua QQ Plot và tính ổn định phương sai (Homoscedasticity).
  
- Mô hình Hồi quy (Regression): Áp dụng OLS Regression để dự đoán mối quan hệ giữa các biến tài chính.

### [CF_Lab5.ipynb] - Mô hình chuỗi thời gian & Biến động

- Time Series Modeling: Thực hiện dự báo với các mô hình ARIMA.
- Phân tích Biến động (Volatility): Tính toán độ lệch chuẩn năm (Annualized Volatility) và sử dụng mô hình GARCH để nắm bắt biến động thị trường.

### [CF_Lab6.ipynb] - Giao dịch cặp & Mean Reversion

- Pairs Trading: Xác định cặp cổ phiếu có liên kết kinh tế và kiểm định tính đồng tích hợp (Cointegration) bằng Engle-Granger/ADF Test.

- Backtesting Nâng cao: Xây dựng hệ thống kiểm thử chiến lược trên tập Test độc lập, tính toán các chỉ số hiệu quả để đánh giá Alpha thực tế.

## 🛠️ Công cụ sử dụng
- Ngôn ngữ: Python
- Thư viện chính: pandas, numpy, statsmodels (phân tích thống kê), matplotlib (trực quan hóa).
