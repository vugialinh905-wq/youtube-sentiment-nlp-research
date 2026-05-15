# 🎯 Nghiên cứu NLP: Xây dựng bộ dữ liệu cảm xúc từ bình luận YouTube

## 📌 Giới thiệu tổng quan
Dự án nghiên cứu các kỹ thuật Xử lý ngôn ngữ tự nhiên (NLP) để 
xây dựng và phân tích bộ dữ liệu cảm xúc từ YouTube. Mục tiêu 
chính là thu thập dữ liệu thô, tiền xử lý tiếng Việt và gán nhãn 
cảm xúc phục vụ bài toán phân loại văn bản.

## 🔄 Các giai đoạn thực hiện

- **Giai đoạn 1 — Thu thập dữ liệu:** Cào bình luận từ các video YouTube đa dạng chủ đề
- **Giai đoạn 2 — Tiền xử lý:** Làm sạch dữ liệu, xử lý Teencode, chuẩn hóa từ ngữ, loại bỏ emoji
- **Giai đoạn 3 — Xây dựng bộ dữ liệu:** Gán nhãn cảm xúc cho tập dữ liệu đã làm sạch
- **Giai đoạn 4 — Phân tích & Đánh giá:** Thống kê và đánh giá chất lượng bộ dữ liệu

## 📁 Cấu trúc dự án

- `crawl_youtube_cmt.ipynb` — Cào bình luận từ YouTube
- `Mining_dataset_TED-comment.ipynb` — Khai thác và phân tích bình luận TED

## 🛠️ Công nghệ sử dụng

- **Ngôn ngữ:** Python
- **Xử lý dữ liệu:** Pandas, NumPy
- **NLP:** NLTK, VnCoreNLP (tách từ tiếng Việt)
- **Học máy:** Scikit-learn

## 📊 Dataset

File CSV quá lớn, tải tại đây:
- [ted_comment.csv](https://drive.google.com/file/d/1FhiGgfdLwu0ku8I29oqS9ooWqr9UBTpT/view?usp=drive_link)
- [sentimentanalysis_output.csv](https://drive.google.com/file/d/19Wn8uZu2sH1_u3kuWTQOMeijziBPaU80/view?usp=drive_link)

## 📈 Kết quả đạt được

- Xây dựng thành công bộ dữ liệu cảm xúc chất lượng cao
- Quy trình tiền xử lý loại bỏ tới **90% dữ liệu nhiễu** từ mạng xã hội
- Hệ thống hóa các phương pháp tiếp cận NLP hiện đại

## 👤 Tác giả
Vũ Gia Linh — Sinh viên Khoa học Dữ liệu @ UTH
