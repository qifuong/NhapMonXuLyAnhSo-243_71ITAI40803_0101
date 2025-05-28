# NhapMonXuLyAnhSo-243_71ITAI40803_0101
Nộp Bài + Readme

README – Báo cáo xử lý ảnh (Bài 1–9)
Họ tên: Lê Quý Phương
MSSV: 2174802010072
Lớp: 71ITAI40803
Giảng viên hướng dẫn: Nguyễn Thái Anh

Ngôn ngữ: Python 3
Thư viện: PIL, numpy, matplotlib, scipy, skimage

Bài 1: Tách ảnh RGB
Tách ảnh thành 3 ảnh riêng: kênh đỏ, xanh lá và xanh dương. Mỗi ảnh chỉ hiển thị một kênh màu.

Bài 2: So sánh hai ảnh
Dùng filecmp.cmp() để kiểm tra hai ảnh có giống hệt nhau hay không.

Bài 3: Hiển thị ảnh
Hiển thị ảnh bằng matplotlib để có thể thêm tiêu đề hoặc xử lý nâng cao.

Bài 4: Chuyển ảnh sang xám
Chuyển ảnh màu sang ảnh xám bằng .convert("L"), dùng để xử lý cạnh và lọc.

Bài 5: Mean filter
Làm mờ ảnh bằng bộ lọc trung bình (3x3), giúp giảm nhiễu nhẹ.

Bài 6: Median filter
Khử nhiễu bằng bộ lọc trung vị, giữ chi tiết biên tốt hơn mean.

Bài 7: Sobel edge detection
Dò biên ảnh bằng thuật toán Sobel, phát hiện các ranh giới trong ảnh xám.

Bài 8: Canny edge detection
Dò biên bằng thuật toán Canny, kết quả rõ và chính xác hơn Sobel.

Bài 9: Lọc nhiều ảnh
Lọc toàn bộ ảnh trong thư mục Exercise bằng cả mean và median filter. So sánh kết quả: median lọc tốt hơn nếu ảnh có nhiễu mạnh.
