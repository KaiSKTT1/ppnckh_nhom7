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
-  Hình ảnh nội soi đại tràng (colonoscopy images) chứa polyp. Các
 hình ảnh này có thể đên từ các bộ dữ liệu như Kvasir-SEG hoặc
 CVC-ClinicDB.
- Hình ảnh có thể có độ phân giải khác nhau và có thể chứa nhiêu
 polyp hoặc các câu trúc khác trong đại tràng.

---

### 📤 Output
- Các mặt nạ phân đoạn (segmentation masks) cho từng hình
 ảnh đâu vào, cho biêt vị trí và hình dạng của polyp trong hình ảnh.
- Mỗi pixel trong mặt nạ:
  - `1` nếu thuộc vùng polyp
  - `0` nếu không thuộc vùng polyp

---

### 📊 Kết quả
- Đề xuất mô hình Attention-based Multi-scale Nested Network (AMNNet) kết
 hợp cơ chế chú ý (attention) và kết nối tổ chim (nested skip connections)
 nhằm nâng cao hiệu quả phân đoạn ảnh y sinh.
-  Mô hình cho kết quả vượt trội trên nhiều bộ dữ liệu chuẩn như ISIC2018,
 CVC-ClinicDB, CVC-ColonDB, BUSI và GlaS, cả về chỉ số định lượng (Dice,
 IoU) lẫn chất lượng trực quan.
-  Cấu trúc mạng linh hoạt, có khả năng mô hình hóa thông tin không gian 
ngữ nghĩa ở nhiêu câp độ.

### Hướng phát triển tương lai
-  Tối ưu hóa mô hình để phù hợp với thiết bị y tế có tài nguyên hạn chế
 (lightweight version).
- Ứng dụng mở rộng cho các bài toán phân đoạn khác trong ảnh y sinh như X
quang, MRI, CT

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
