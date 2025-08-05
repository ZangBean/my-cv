# My CV - HTML & CSS

Dự án tạo CV cá nhân bằng HTML/CSS.

## Kiến thức HTML đã áp dụng

### 1. Cấu trúc cơ bản của tài liệu HTML
- Sử dụng `<!DOCTYPE html>` để khai báo loại tài liệu.
- Thẻ `<html>`, `<head>`, `<title>`, `<body>` để xây dựng bố cục trang chuẩn.

### 2. Các thẻ văn bản
- Sử dụng các thẻ tiêu đề như `<h1>` đến `<h3>` để hiển thị tên, chức danh, và tiêu đề các mục.
- Thẻ `<p>` để mô tả thông tin cá nhân, giới thiệu bản thân.
- Thẻ `<strong>` và `<em>` để làm nổi bật nội dung.

### 3. Thẻ danh sách
- `<ul>` và `<li>` để liệt kê kỹ năng.

### 4. Thẻ liên kết và hình ảnh
- `<a href="mailto:..." >` để tạo email liên hệ.
- `<a href="tel:..." >` để tạo link gọi điện.
- `<img src="..." alt="..." />` để chèn ảnh đại diện.
  
---

## Kiến thức CSS đã áp dụng

### Kiểu viết CSS
- CSS viết trong file `style.css` và liên kết qua `<link rel="stylesheet" href="style.css">`.

### Bố cục trang
- **Flexbox**: Sử dụng `display: flex` để chia bố cục 2 cột: ảnh bên trái và nội dung bên phải.
- **Căn giữa nội dung**: Dùng `justify-content`, `align-items`, `margin: 0 auto`.

### Màu sắc và font chữ
- Dùng `color`, `background-color` để phối màu dễ nhìn.
- Chọn font từ Google Fonts (ví dụ: `Roboto`, `Open Sans`).
- Áp dụng `font-size`, `font-weight`, `line-height` để dễ đọc hơn.

### Trang trí và nhấn mạnh
- Tô viền ảnh avatar bằng `border-radius`, `box-shadow`.
- Gạch chân tiêu đề phần bằng `border-bottom`.
- Dùng `hover` để tạo hiệu ứng khi rê chuột vào link hoặc nút.

### Responsive (cơ bản)
- Dùng `max-width` và `media queries` đơn giản để trang hiển thị tốt hơn trên điện thoại.

---

## Cấu trúc thư mục

```plaintext
my-cv/
├── index.html
├── style.css
└── responsive.css
