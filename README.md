#K-Nearest Neighbors (KNN)
Giới thiệu
K-Nearest Neighbors (KNN) là một thuật toán học máy phổ biến được sử dụng cho cả các bài toán phân loại (classification) và dự đoán giá trị (regression). Thuật toán này dựa trên việc phân loại các điểm dữ liệu dựa trên khoảng cách của chúng đến các điểm láng giềng (neighbors) gần nhất trong tập dữ liệu huấn luyện.

KNN từ đầu (KNN from scratch)
Trong phần này, chúng ta sẽ tìm hiểu về cách triển khai thuật toán KNN từ đầu, tức là không sử dụng các thư viện hỗ trợ như scikit-learn. Chúng ta sẽ tự viết mã để tính toán khoảng cách giữa các điểm dữ liệu, tìm ra các điểm láng giềng và thực hiện dự đoán cho các điểm dữ liệu mới.

KNN trong việc chọn K hợp lý
Một thách thức quan trọng trong việc sử dụng thuật toán KNN là việc chọn giá trị của K, tức số lượng điểm láng giềng được sử dụng để quyết định nhãn của một điểm dữ liệu mới. Trong phần này, chúng ta sẽ xem xét vấn đề của việc chọn K và cách chọn K một cách hợp lý.
