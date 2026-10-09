# 404-bduiovn

Trang thông báo **"Hệ thống đang bảo trì"** — HTML/CSS/JS thuần, 1 file duy nhất.

Live: https://sv.bdu.io.vn/

## Nội dung

- Logo & màu chủ đạo lấy theo nhận diện Trường Đại học Bình Dương (đỏ `#ad171c`, logo hào quang).
- Tiêu đề: **Hệ thống đang bảo trì**
- Dòng hướng dẫn: *"Nếu muốn tra cứu thông tin, vui lòng sử dụng https://sv.bdu.edu.vn/public/ để tra cứu."*
- Nút **"Đến trang tra cứu"** + nút **"Sao chép liên kết"** (copy vào clipboard, có fallback).
- Favicon chính là logo trường (16/32px + apple-touch-icon 180px).

## Cấu trúc

```
index.html                  Trang bảo trì
assets/
├── logo.png                512×512 — logo hiển thị trên trang
├── favicon-16.png / favicon-32.png
├── apple-touch-icon.png    180×180
└── logo-nguon.png          ảnh gốc 1254×1254 do trường cung cấp
```

## Chạy thử

Mở trực tiếp `index.html`, hoặc:

```bash
python3 -m http.server 8080   # http://localhost:8080
```

## Tuỳ chỉnh

| Việc | Ở đâu |
| --- | --- |
| Đổi dòng chữ / link tra cứu | `index.html` (`.lead`, `href`) và biến `URL` trong `<script>` |
| Thay logo | đổi ảnh trong `assets/` (nên là PNG nền trong suốt, vuông) |
