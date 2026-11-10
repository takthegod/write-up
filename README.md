# 🛡️ S133p CTF Write-ups

Bộ sưu tập **write-up, exploit script và tài liệu phân tích** của team **S133p** — Câu lạc bộ An toàn thông tin **VSL**, Trường Đại học Công nghệ Thông tin và Truyền thông Việt – Hàn (VKU), Đà Nẵng.

Repo ghi lại quá trình thi đấu, phân tích lỗ hổng và khai thác thực tế của team qua các giải CTF 2026.

---

## 👥 Thành viên

- **Trần Văn Hoàng**
- **Nguyễn Anh Kiệt**
- **Lê Ngọc Hải Yến**
- **Hoàng Lê Gia Bảo**

---

## 🏆 Thành tích

| Giải đấu | Kết quả | Ghi chú |
| :--- | :---: | :--- |
| **DDC CTF 2026** | **Top 4** | Vòng chung kết — 17 thử thách thuộc Web, Pwn, Reverse, Crypto, Misc |
| **PwnSec CTF 2026** | **Top 30** | Hoàn thành 5/5 thử thách Web: ReadOnce, Easy Leak, Neon Skies, Phault, Pickle in the Middle |
| **HACKTHEON SEJONG CTF 2026** | Tham gia | Đội VSL_go0n — 2 write-up (Pwn, Reverse) |

---

## 📂 Cấu trúc repo

```
S133p-CTF-Writeups/
├── DDC-2026/            # DDC CTF 2026 — 17 bài (web, pwn, reverse, crypto, misc)
├── PwnSec-2026/         # PwnSec CTF 2026 — 5 bài web + exploit scripts + hình ảnh
├── HACKTHEON-2026/      # HACKTHEON SEJONG 2026 — 2 tài liệu DOCX
└── Other-CTF/           # Các bài lẻ: web, reverse, forensics, crypto
```

Mỗi thư mục đều có `README.md` riêng, liệt kê thử thách, điểm số, kỹ thuật và link tới write-up chi tiết.

---

## 🔍 Kỹ thuật nổi bật

**Web**
- GraphQL introspection & mutation không xác thực
- WebSocket prototype pollution → leo thang đặc quyền
- CSP bypass, cookie tossing, request smuggling
- Python pickle deserialization → RCE
- SQL injection (UNION, blind/error oracle), PostgreSQL file read

**Pwn**
- Format string leak & GOT overwrite
- Stack buffer overflow → ret2win
- Heap UAF + tcache poisoning
- Integer overflow

**Reverse**
- Go binary, ELF tự giải mã, VM interpreter
- Vulkan SPIR-V shader & giải hệ phương trình tuyến tính
- Windows kernel driver

**Crypto / Forensics**
- AES-CBC padding oracle
- RSA Hastad broadcast attack (e = 3)
- PRNG seed prediction
- FAT32 deleted-file carving, LSB steganography

---

## 🚀 Cách đọc write-up

1. Mở thư mục giải đấu tương ứng.
2. Đọc `README.md` để xem bảng tổng hợp thử thách.
3. Mở file `.md` của từng bài để xem phân tích, payload và script khai thác.

---

## ⚖️ Ghi công & miễn trừ

- Nội dung chuyên môn trong repo là công sức của **team S133p** trong quá trình luyện tập và thi đấu CTF.
- Toàn bộ cờ (flag) đều thuộc các giải đấu đã kết thúc; tài liệu chỉ phục vụ mục đích học tập và nghiên cứu bảo mật.

---

## 📬 Liên hệ

**Nguyễn Anh Kiệt** — Sinh viên An toàn thông tin, VKU Đà Nẵng

- Email: nguyenanhkiet1012@gmail.com
- Điện thoại: 0948 411 207
- Website: [094928.xyz](https://094928.xyz)
