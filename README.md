# Phòng Thí Nghiệm Di Truyền Học Lớp 9 - ADN, ARN & 20 Axit Amin

Ứng dụng Web tương tác Single Page hỗ trợ học tập môn **Sinh học lớp 9** (theo chương trình GDPT mới & hiện hành). Ứng dụng chạy hoàn toàn offline ngay trên trình duyệt máy tính và điện thoại.

---

## 🚀 Các Tính Năng Nổi Bật

### 1. 🧬 Mô phỏng Quá trình Dịch mã (ADN ➔ mARN ➔ Axit Amin)
- Nhập chuỗi mạch gốc ADN (3' ➔ 5') hoặc chọn các chuỗi mẫu (Mẫu SGK chuẩn 18 Nu, gen Insulin 30 Nu, hoặc tạo ngẫu nhiên).
- Kiểm tra hợp lệ thời gian thực (chỉ nhận A, T, G, X/C, cảnh báo codon lẻ ở cuối).
- Trực quan hóa 4 luồng song song:
  - **Mạch bổ sung ADN (5' ➔ 3')**
  - **Liên kết Hiđrô (A-T: 2 liên kết `||`, G-X: 3 liên kết `|||`)**
  - **Mạch gốc khuôn ADN (3' ➔ 5')**
  - **Phân tử mARN (5' ➔ 3')** chia theo từng ô bộ ba (Codon).
  - **Chuỗi Polipeptit (Protein)**: Tra cứu 20 axit amin, phân biệt nổi bật bộ ba mở đầu (`AUG` ➔ Met) và bộ ba kết thúc (`UAA, UAG, UGA` ➔ Stop).
- **Mô phỏng Ribosome chuyển động**: Chế độ animation quét qua từng codon và dịch mã từng axit amin.

### 2. 🧮 Máy tính Công thức Sinh học 9 (Giải Bài Tập ADN Chi Tiết)
- **Bài toán Thuận (Biết A, G)**: Tính Tổng Nu ($N$), Liên kết Hiđrô ($H$), Chiều dài ($L$), Khối lượng ($M$), Chu kỳ xoắn ($C$), Liên kết hóa trị ($N-2$ và $2N-2$), Tỉ lệ % từng loại Nu kèm **lời giải từng bước chuẩn tự luận**.
- **Bài toán Ngược (Biết N & H, L & H, C & H, N & %A)**: Tự động thiết lập và giải hệ phương trình đại số tìm số lượng $A, T, G, X$, kiểm tra tính đúng đắn sinh học của đề bài.
- **Cẩm nang công thức SGK**: Tóm tắt trọn bộ công thức cấu trúc gen, nhân đôi ADN, phiên mã và dịch mã.

### 3. 📖 Bảng Tra Cứu Tương Tác 20 Axit Amin
- Tra cứu theo tên tiếng Việt/Anh, mã 3 chữ cái, hoặc **nhập trực tiếp Codon** (ví dụ: gõ `AUG`, `UUU`, `GAG`...).
- Lọc theo nhóm tính chất: Kị nước, Ưa nước, Bazơ (kiềm), Axit, Mã đặc biệt.
- Cửa sổ xem chi tiết cấu trúc, khối lượng (Da), công thức phân tử và vai trò sinh học.

---

## 🛠️ Công Nghệ Sử Dụng
- **HTML5** & **Vanilla JavaScript** (Không phụ thuộc backend, chạy offline 100%).
- **Tailwind CSS** (CDN) & **Font Awesome 6**.
- **Google Fonts**: Inter, Outfit, JetBrains Mono.

---

## 📂 Hướng Dẫn Sử Dụng
1. Tải về file `index.html`.
2. Nhấp đúp chuột để mở trực tiếp trong bất kỳ trình duyệt nào (Chrome, Edge, Safari, Firefox,...).
3. Sử dụng ngay mà không cần cài đặt thêm môi trường lập trình.
