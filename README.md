# NhapMonXuLyAnhSo-243_71ITAI40803_0101
Nộp Bài + Readme

README – Báo cáo xử lý ảnh (Bài 1–9)

Họ tên: Lê Quý Phương
MSSV: 2174802010072
Lớp: 71ITAI40803
GVHD: Nguyễn Thái Anh

Ngôn ngữ: Python 3
Thư viện: PIL, numpy, matplotlib, scipy, skimage

Bài 1: Tách màu RGB
Tách ảnh thành 3 ảnh chỉ hiển thị màu Đỏ (R), Xanh Lá (G), và Xanh Dương (B).

✅ Ưu điểm: Dễ nhìn thấy sự phân bố từng kênh màu.
❌ Nhược điểm: Không hiển thị đầy đủ nội dung ảnh khi chỉ giữ một kênh.

Bài 2: Hoán đổi màu RGB
Hoán đổi thứ tự các kênh màu trong ảnh, ví dụ: R ↔ B.

✅ Ưu điểm: Giúp hiểu ảnh thay đổi như thế nào khi kênh màu bị đổi.
❌ Nhược điểm: Không có ứng dụng trực tiếp trong thực tế.

Bài 3: Chuyển hệ màu HSV
Chuyển ảnh RGB sang HSV, và hiển thị riêng từng kênh H, S, V.

✅ Ưu điểm: HSV phản ánh rõ hơn màu sắc (Hue), độ bão hòa (Saturation), độ sáng (Value).
❌ Nhược điểm: Phải chuyển đổi thủ công, tốn thời gian tính toán.

Bài 4: Thay đổi kênh HSV
Chỉnh H tăng 1/3, V giảm 3/4, giữ nguyên S.

✅ Ưu điểm: Làm thay đổi màu ảnh một cách có kiểm soát.
❌ Nhược điểm: Có thể gây ảnh bị tối quá hoặc lệch màu.

Bài 5: Dùng Mean Filter
Dùng mean filter để làm mờ ảnh trong thư mục Exercise.

✅ Ưu điểm: Giảm nhiễu nhẹ, làm mượt hình ảnh.
❌ Nhược điểm: Làm mờ chi tiết và biên ảnh.

Bài 6: So sánh các bộ lọc khử nhiễu
So sánh Mean và Median Filter.

✅ Ưu điểm: Median filter xử lý tốt nhiễu muối tiêu.
❌ Nhược điểm: Mean filter yếu trong môi trường nhiễu mạnh.

Bài 7: Tìm biên ảnh
Sau khi khử nhiễu, dùng Sobel/Canny để phát hiện biên.

✅ Ưu điểm: Xác định ranh giới vật thể rõ ràng.
❌ Nhược điểm: Nhạy cảm với nhiễu nếu không khử trước.

Bài 8: Đổi màu RGB ngẫu nhiên
Trộn thứ tự kênh RGB ngẫu nhiên sau khi khử nhiễu.

✅ Ưu điểm: Tạo ảnh mới thú vị, dễ quan sát ảnh hưởng màu.
❌ Nhược điểm: Không phù hợp với xử lý ảnh thực tế.

Bài 9: Đổi màu HSV ngẫu nhiên (không trùng)
Chuyển sang HSV, đổi hue khác nhau cho mỗi ảnh (không trùng), rồi chuyển lại RGB.

✅ Ưu điểm: Tạo các phiên bản ảnh màu sắc khác biệt rõ ràng.
❌ Nhược điểm: Phải kiểm tra trùng hue, tốn thêm bước xử lý.

