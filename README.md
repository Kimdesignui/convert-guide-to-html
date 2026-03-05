# 📄 DocFlow Builder v4.4
> Công cụ soạn thảo & xuất tài liệu — NXB Quân đội Nhân dân

## 🌐 Truy cập Online
**👉 [Mở App tại đây](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME)**
> *(Thay YOUR_USERNAME và YOUR_REPO_NAME sau khi deploy)*

---

## 🚀 Hướng dẫn Deploy lên GitHub Pages (5 phút)

### Bước 1 — Tạo Repository
1. Đăng nhập [github.com](https://github.com)
2. Bấm **"New repository"** (nút dấu `+` góc trên phải)
3. Đặt tên repo, ví dụ: `docflow-builder`
4. Chọn **Public** → Bấm **"Create repository"**

### Bước 2 — Upload Files
1. Trong trang repo vừa tạo, bấm **"uploading an existing file"**
2. Kéo thả toàn bộ file trong thư mục này vào (index.html + README.md)
3. Bấm **"Commit changes"**

### Bước 3 — Bật GitHub Pages
1. Vào tab **Settings** của repo
2. Menu trái → chọn **Pages**
3. Mục *Branch* → chọn **main** → **/root** → Bấm **Save**
4. Chờ ~1 phút → GitHub cấp link: `https://YOUR_USERNAME.github.io/docflow-builder`

---

## ✨ Tính năng

| Tính năng | Mô tả |
|---|---|
| 📄 Upload DOCX | Đọc và hiển thị file Word |
| 📦 Upload ZIP | Hỗ trợ Google Docs export |
| 🎨 Định dạng đề mục | Font/cỡ/màu cho A / 1. / 1.1 / 1.1.1 |
| 🖌 Copy định dạng | Format Painter — áp dụng 1 cấp sang nhiều heading |
| 📋 Mục lục Accordion | Sidebar TOC 2 cấp, cuộn tới đâu sáng tới đó |
| 📤 Xuất HTML | File xuất có sidebar TOC + scroll spy |
| 🖨 In/PDF | Mở tab sạch, in không bị cắt |

---

## 🛠 Công nghệ
- **Mammoth.js** — Chuyển đổi DOCX → HTML
- **JSZip** — Giải nén Google Docs ZIP
- **Vanilla JS + CSS** — Không cần framework, chạy offline được

---
*Phát triển cho NXB Quân đội Nhân dân · DocFlow Builder v4.4*
