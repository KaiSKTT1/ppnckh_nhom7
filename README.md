## 🧬 Giới thiệu Dataset ETIS-LaribPolyDB

### 📌 Mô tả Dataset
Dataset **ETIS-LaribPolyDB** bao gồm hình ảnh polyp đại tràng thu thập từ nhiều bệnh nhân khác nhau, được sử dụng trong các nghiên cứu và phát triển thuật toán **phát hiện và phân đoạn tự động polyp đại tràng** trong ảnh nội soi.

---

### 📊 Kích thước Dataset
- **Tổng số ảnh:** 196 ảnh  
- **Kích thước ảnh:** 1225 x 955 pixels  
- **Định dạng:** `.jpg`, `.png`  
- **Chú thích:** Mỗi ảnh đi kèm một mặt nạ nhị phân chính xác

---

### 📥 Input
- Hình ảnh nội soi đại tràng với kích thước **1225 x 955 pixels**
- Mỗi ảnh có thể chứa **một hoặc nhiều polyp**

---

### 📤 Output
- **Mặt nạ nhị phân (binary mask)** tương ứng cho mỗi ảnh
- Mỗi pixel trong mặt nạ:
  - `1` nếu thuộc vùng polyp
  - `0` nếu không thuộc vùng polyp

---

### 📚 Tài liệu tham khảo

#### 📖 Tiếng Anh:
1. **Using DUCK-Net for polyp image segmentation - PubMed**  
   - Nghiên cứu mô hình DUCK-Net cho bài toán phân đoạn ảnh polyp, đánh giá trên ETIS-LaribPolyDB.

2. **Medical Image Segmentation on ETIS-LaribPolypDB**  
   - So sánh hiệu suất của 24 phương pháp phân đoạn y tế hiện đại trên dataset này.

3. **Deep Learning for Polyp Detection and Classification in Colonoscopy (AI4PolypNet)**  
   - Ứng dụng deep learning để phát hiện và phân loại polyp đại tràng.

#### 📗 Tiếng Việt:
1. **Tiềm năng của ứng dụng trí tuệ nhân tạo trong hỗ trợ phát hiện polyp đại tràng qua nội soi**  
   - Giới thiệu hệ thống AI hỗ trợ phát hiện polyp thời gian thực.

2. **Trí tuệ nhân tạo AI cho vấn đề chẩn đoán polyp và ung thư đại tràng**  
   - Ứng dụng AI phân tích hình dạng, kích thước polyp.

3. **Việt Nam sớm ứng dụng trí tuệ nhân tạo trong nội soi phát hiện polyp đại tràng**  
   - AI giúp phát hiện sớm các tổn thương ở đại tràng.

---

> 📂 *Dataset ETIS-LaribPolyDB là một trong những bộ dữ liệu tiêu chuẩn cho các nghiên cứu liên quan đến phát hiện và phân đoạn polyp trong nội soi tiêu hóa.*
