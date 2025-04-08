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

### 📖 Tiếng Anh

1. [DUCK-Net for Polyp Image Segmentation](https://pubmed.ncbi.nlm.nih.gov/37328572/)  
   Nghiên cứu mô hình DUCK-Net cho bài toán phân đoạn ảnh polyp, đánh giá trên ETIS-LaribPolypDB.

2. [Medical Image Segmentation on ETIS-LaribPolypDB](https://paperswithcode.com/sota/medical-image-segmentation-on-etis)  
   So sánh hiệu suất của 24 phương pháp phân đoạn y tế hiện đại trên dataset này.

3. [Deep Learning for Polyp Detection and Classification in Colonoscopy (AI4PolypNet)](https://github.com/sing-group/deep-learning-colonoscopy)  
   Ứng dụng deep learning để phát hiện và phân loại polyp đại tràng.

---

### 📗 Tiếng Việt

1. ['Bác sĩ' AI - cuộc cách mạng trong phòng nội soi tiêu hóa](https://vnexpress.net/bac-si-ai-cuoc-cach-mang-trong-phong-noi-soi-tieu-hoa-4866955.html)  
   Giới thiệu hệ thống AI hỗ trợ phát hiện polyp thời gian thực.

2. [Trí tuệ nhân tạo AI cho vấn đề chẩn đoán polyp và ung thư đại tràng](https://www.vinmec.com/vie/bai-viet/tri-tue-nhan-tao-ai-cho-van-de-chan-doan-polyp-va-ung-thu-dai-trang-vi)  
   Ứng dụng AI phân tích hình dạng, kích thước polyp.

3. [Nội soi ứng dụng AI có phát hiện sớm ung thư dạ dày?](https://vnexpress.net/noi-soi-ung-dung-ai-co-phat-hien-som-ung-thu-da-day-4825946.html)  
   AI giúp phát hiện sớm các tổn thương ở dạ dày (có liên quan đến phương pháp nội soi tương tự đại tràng).


---

> 📂 *Dataset ETIS-LaribPolyDB là một trong những bộ dữ liệu tiêu chuẩn cho các nghiên cứu liên quan đến phát hiện và phân đoạn polyp trong nội soi tiêu hóa.*
