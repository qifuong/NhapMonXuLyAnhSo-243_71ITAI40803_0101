# NhapMonXuLyAnhSo-243_71ITAI40803_0101
Nộp Bài + Readme

README – Báo cáo xử lý ảnh (Bài 1–9)
Họ tên: Lê Quý Phương
MSSV: 2174802010072
Lớp: 71ITAI40803
Giảng viên hướng dẫn: Nguyễn Thái Anh

Ngôn ngữ: Python 3
Thư viện: PIL, numpy, matplotlib, scipy, skimage

Bài 1: Tách màu RGB
Chương trình nạp ảnh, tách thành 3 ảnh chỉ hiển thị màu đỏ, xanh lá và xanh dương.
Mỗi ảnh giữ một kênh màu, hai kênh còn lại bằng 0.

Bài 2: Hoán đổi màu RGB
Hoán đổi giá trị kênh màu, ví dụ: đổi R <-> G, hoặc G <-> B.
Lưu các ảnh sau khi đổi để so sánh sự thay đổi màu sắc.

Bài 3: Chuyển hệ màu HSV
Chuyển ảnh từ RGB sang HSV. Lưu 3 ảnh tương ứng với kênh H, S, V.
Giúp hiểu rõ ảnh qua từng thành phần màu.

Bài 4: Thay đổi kênh HSV
Tăng kênh H lên 1/3 lần, giảm độ sáng V xuống 3/4.
Giữ nguyên kênh S. Lưu ảnh mới sau khi chuyển đổi.

Bài 5: Dùng Mean Filter
Áp dụng mean filter cho từng ảnh trong thư mục Exercise.
Giúp làm mờ và giảm nhiễu nhẹ.

Bài 6: So sánh các bộ lọc khử nhiễu
Dùng cả mean filter và median filter để lọc nhiễu cho ảnh trong thư mục Exercise.
Kết luận: Median filter khử nhiễu tốt hơn nếu ảnh nhiễu mạnh (như muối tiêu).

Bài 7: Tìm biên ảnh
Sau khi khử nhiễu, áp dụng Sobel hoặc Canny để xác định cạnh các ảnh trong Exercise.
Giúp thấy rõ ranh giới, chi tiết trong ảnh.

Bài 8: Đổi màu RGB ngẫu nhiên
Sau khi khử nhiễu, chương trình sẽ trộn thứ tự kênh RGB ngẫu nhiên (vd: BGR, GRB, v.v.).
Tạo ảnh mới có màu sắc khác nhưng giữ nội dung.

Bài 9: Đổi màu HSV ngẫu nhiên
Chuyển ảnh sang HSV, đổi ngẫu nhiên thứ tự hoặc giá trị kênh H, S, V nhưng không trùng nhau.
Sau đó chuyển lại RGB và lưu. Áp dụng sau khi khử nhiễu.
