EDA là một phương pháp phân tích dữ liệu khám phá chủ yếu sử dụng các kỹ thuật về biểu đồ, hình vẽ. Từ đó:
- Hiểu dữ liệu, lấy ngữ cảnh liên quan đến dữ liệu, hiểu các biến và quan hệ giữa các biến, hình thành các giả thuyết có thể hữu ích cho việc xây dựng các mô hình dự báo.
- Trong bài học việc thực hiện EDA sử dụng trực quan dữ liệu với thư viện seaborn
- Phân tích trực quan các biến định lượng dùng histogram
- Phân tích trực quan các biến phân loại dùng count plot
Phân tích trực quan sự tương quan giữa các biến định lượng dùng scatter plot, joint plot, box plot và các complex conditional plot Trực quan hiệu quả các biến và sự tương quan giữa chúng, các nhà khoa học dữ liệu và phân tích dữ liệu nhanh chóng hiểu xu hướng, các ngoại lệ và mẫu (pattern) của dữ liệu. Sự hiếu biết này được sử dụng để kể một câu chuyện, định hướng cho việc ra quyết định hay tạo các mô hình dự báo.
- Các bước để phân tích EDA:
+ Chuẩn bị dữ liệu
+ Xử lý dữ liệu: dữ liệu miss, dữ liệu trùng, dữ liệu bị sai.
+ Import các thư viện của python: seaborn, numpy, panda, matplyplot...
+ Trực quan dữ liệu thông qua các công cụ vẽ biểu đồ của python:
+ Phân tích biến định lượng thường dùng histogram
+ Phân tích biến phân loại: countplot, bar, column,..
+ Phân tích tương quan giữa các biến định lượng:dùng Scatter plot thường được dùng để trực quan sự tương quan giữa 2 biến định lượng
+ Phân tích tương quan giữa biến định lượng và biến phân loại: dùng box plot thường được dùng trong việc trực quan sự tương quan giữa biến định lượng và biến phân loại. 
+ Đọc biểu đồ và đưa ra nhận xét.
+ Từ các dữ liệu xây dựng và định hướng ra các dự báo.
-Complex conditional plots được dùng để trực quan sự tương quan có điều kiện

- Đối với bài KQThiLyThuyet-26.12.2020_ca2 ta làm ở phần thi  thực hành:
+ Trước tiên mở file excel lên và xóa những dòng dữ liệu không cần thiết. Chỉnh sửa lại tên 2 cột điểm là Điểm LT và Điểm TH.
+ Sau đó ta desceribe dữ liệu để có được bảng dữ liệu như là dữ liệu mẫu cho ta được 64 dữ liệu mẫu, điểm trung bình LT của sinh viên là 5.315625, độ lệch chuẩn điểm của sinh viên là 1.205703, số điểm thấp nhất là 0, mốc 25% là 4.725000, trung vị là 5.400000, mốc 75% là 6.3, giá trị điểm cao nhất là 7.
+ Ở đây e dùng biểu đồ histogram để thấy được là đa số sinh viên có điểm lý thuyết nằm trong khoảng từ 4 đến 7. Trung bình các sinh viên có số điểm lớn hơn 3 và 1 trường hợp có điểm 0. Số sinh viên có số điểm 7(số điểm cao nhất ở phần lý thuyết) là 18 sinh viên. Và nhiều thứ 2 là 5 điểm với 15 sinh viên.
+ Tiếp theo ta dùng biểu đổ boxplot để thấy được rằng 1 bạn nam đạt 5.5, chỉ 1 bạn nữ 0 điểm. Tập trung nhiều điểm của các bạn nữ sẽ là 4.7 điểm đến 6.3 điểm với trung vị là 5.4 điểm đạt cao nhất là 7 điểm.



