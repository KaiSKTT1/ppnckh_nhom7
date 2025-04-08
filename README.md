## I> Giới thiệu Dataset ETIS-LaribPolyDB

**Mô tả dataset:**  
Dataset ETIS-LaribPolyDB bao gồm hình ảnh polyp đại tràng từ các bệnh nhân khác nhau, được sử dụng để phát triển các thuật toán phát hiện tự động về polyp đại tràng.

**Kích thước dataset:**  
Gồm 196 hình ảnh kích thước 1225x955 pixels, với các nhãn chính xác.

---

**Input:**
1. Hình ảnh nội soi đại tràng có kích thước 1225x955 pixels  
2. Định dạng hình ảnh thường là `.jpg` hoặc `.png`  
3. Mỗi hình ảnh có thể chứa một hoặc nhiều polyp  

**Output:**
1. Mặt nạ nhị phân (binary mask) tương ứng, đánh dấu vị trí của polyp trong hình ảnh  
2. Mỗi pixel trong mặt nạ có giá trị:  
   +) `1` nếu thuộc vùng polyp  
   +) `0` nếu không thuộc vùng polyp

Các bài báo tham khảo:
TÀI LIỆU THAM KHẢO
Tiếng Anh
1.DUCK-Net for Polyp Image Segmentation - Nghiên cứu về mô hình DUCK-Net dùng để phân đoạn hình ảnh polyp, thử nghiệm trên ETIS-LaribPolyDB.

2.Medical Image Segmentation on ETIS-LaribPolypDB - So sánh hiệu suất của 24 nghiên cứu về phân đoạn hình ảnh y tế trên ETIS-LaribPolypDB.

3.Deep Learning for Polyp Detection and Classification in Colonoscopy - AI4PolypNet phát triển thuật toán phát hiện và phân loại polyp đại tràng bằng Deep Learning.

Tiếng Việt
1.Tiềm năng của ứng dụng trí tuệ nhân tạo trong hỗ trợ phát hiện polyp đại tràng qua nội soi - Hệ thống AI hỗ trợ phát hiện polyp thời gian thực.

2.Trí tuệ nhân tạo AI cho vấn đề chẩn đoán polyp và ung thư đại tràng - AI được ứng dụng để phân tích kích thước, hình dạng polyp.

3.Việt Nam sớm ứng dụng trí tuệ nhân tạo trong nội soi phát hiện polyp đại tràng - AI giúp phát hiện sớm tổn thương ở đại tràng.

