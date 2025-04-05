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
