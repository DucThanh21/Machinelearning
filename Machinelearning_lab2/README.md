## Basic Machinelearning 
### MỤC LỤC 

[1. Công Nghệ Sử Dụng](#CongNgheSuDung)

[2. Thuật Toán](#ThuatToan)

[3. Hiển Thị Kết Quả](#hienthiketqua)

<a name ="CongNgheSuDung"></a>
## 1. [Công Nghệ sữ dụng]

## Thư viện python: 
-`pandas`, `sklearn` (scikit-learn)

## Các công cụ chính:
- `CountVectorizer`: Để chuyển đổi văn bản thành các đặc trưng số.
-  `BernoulliNB` và `MultinomialNB`: Áp dụng các phân phối Naive Bayes khác nhau.
-  `train_test_split`: Chia dữ liệu thành tập huấn luyện và kiểm tra.
- `GaussianNB`: Mô hình Naive Bayes với phân phối Gaussian.
- `train_test_split`: Chia dữ liệu thành tập huấn luyện và kiểm tra.
- `LabelEncoder`: Mã hóa các giá trị phân loại thành số.

[2. Thuật Toán](#ThuatToan)

## Thuật toán sử dụng:
- Phân phối Bernoulli Naive Bayes: Áp dụng cho dữ liệu `hị phân (binary)`. Phù hợp khi các đặc trưng chỉ có hai giá trị (0 hoặc 1).
  
- Phân phối Multinomial Naive Bayes: Áp dụng cho `dữ liệu rời rạc (discrete)`, đặc biệt là trong bài toán phân loại văn bản. Phù hợp khi đặc trưng là tần suất xuất hiện từ trong văn bản.
  
- Phân phối Gaussian Naive Bayes: Áp dụng cho dữ liệu liên tục. Phân phối này phù hợp cho các bài toán mà đặc trưng đầu vào là các biến số liên tục như tuổi, tỷ lệ Natri/Kali.



