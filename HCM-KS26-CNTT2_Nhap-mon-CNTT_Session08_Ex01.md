# Bài 1 : Chuẩn hóa tài liệu Markdown cho dự án
--- 
## **Phần 1. Phân tích:** 
Lỗi cú pháp:
- Nhảy cấp độ tiêu đề (H1 nhảy xuống H3) mà bỏ qua H2 
Lý do kết quả render không như ý: Theo quy tắc , các cấp độ tiêu đề tiếp theo phải tuân theo thứ tự tuần tự (H1 $\rightarrow$ H2 $\rightarrow$ H3...).
- Lỗi cú pháp hình ảnh có thể bị thêm ký tự thoát `\` ở cuối `([Logo Dự án\])` hoặc có khoảng trắng giữa cặp ngoặc vuông `[]` và ngoặc tròn `()`
Lý do kết quả render không như ý: Markdown không nhận diện đây là cú pháp hình ảnh chuẩn `![Alt text](url)`, dẫn đến việc ảnh không hiển thị mà chỉ hiện dưới dạng văn bản thô hoặc liên kết lỗi.
- Lỗi in đậm văn bản:
**Lỗi:** Chỉ dùng 1 dấu sao đơn `*Rất quan trọng*` thay vì 2 dấu sao `**Rất quan trọng**`
Lý do kết quả render không như ý: Một dấu sao chỉ có tác dụng tạo chữ nghiêng

---

## Phần 2. Hoàn thiện mã nguồn Markdown:
# Lợi ích của rau sạch
## Danh sách các loại rau
![Logo Dự án](https://greentech.vn/logo.png)
**Rất quan trọng**