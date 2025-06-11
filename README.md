# NhapMonXuLyAnhSo-243_71ITAI40803_0101
Nộp Bài + Readme (Lab 2)

README – Báo cáo xử lý ảnh (Bài 1–4)

Họ tên: Lê Quý Phương
MSSV: 2174802010072
Lớp: 71ITAI40803
GVHD: Nguyễn Thái Anh

📝 README – Biến Đổi Ảnh Cơ Bản và Nâng Cao
📁 Thư mục: exercise/
Chứa các ảnh đầu vào. Tất cả các kết quả xử lý đều được lưu lại tại đây với tiền tố tương ứng (inverse_, fft_, v.v.).

🔹 Câu 1 – Biến đổi ảnh cơ bản (phím I, G, L, H, C)
Mục tiêu: Thực hiện các phép biến đổi cơ bản trên ảnh xám (grayscale).

Phím	Phép biến đổi	Giải thích ngắn gọn
I	Inverse (âm bản)	Đổi màu mỗi pixel thành 255 - pixel.
G	Gamma Correction	Tăng/giảm độ sáng theo công thức phi tuyến.
L	Log Transformation	Làm sáng vùng tối, nén vùng sáng.
H	Histogram Equalization	Cân bằng độ sáng, tăng tương phản tổng thể.
C	Contrast Stretching	Co giãn độ tương phản dựa trên ngưỡng 2%-98%.

🔹 Câu 2 – Biến đổi ảnh tần số (phím F, L, H)
Mục tiêu: Biến đổi ảnh sang miền tần số với Fourier và lọc Butterworth.

Phím	Phép biến đổi	Giải thích ngắn gọn
F	Fast Fourier Transform (FFT)	Hiển thị biên độ phổ tần số của ảnh.
L	Butterworth Lowpass Filter	Giữ vùng tần số thấp (ảnh mịn hơn).
H	Butterworth Highpass Filter	Giữ vùng tần số cao (làm nổi chi tiết).

🔹 Câu 3 – Hoán đổi RGB + Biến đổi cơ bản ngẫu nhiên
Mục tiêu:

Đổi thứ tự màu kênh RGB ngẫu nhiên (ví dụ: BGR → GBR).

Chuyển sang ảnh xám.

Áp dụng ngẫu nhiên 1 trong 5 phép biến đổi ở Câu 1.

Tác dụng: Kết hợp xử lý không gian màu và biến đổi sáng cơ bản.

🔹 Câu 4 – Hoán đổi RGB + Biến đổi tần số ngẫu nhiên + Lọc nâng cao
Mục tiêu:

Đổi thứ tự kênh RGB ngẫu nhiên.

Chuyển sang ảnh xám.

Áp dụng ngẫu nhiên 1 trong 3 phép biến đổi ở Câu 2.

Thêm bước lọc:

Nếu chọn Butterworth Lowpass → áp dụng Min Filter (làm mịn thêm).

Nếu chọn Butterworth Highpass → áp dụng Max Filter (làm nổi bật chi tiết).
