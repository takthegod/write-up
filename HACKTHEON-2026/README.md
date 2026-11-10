# HACKTHEON SEJONG CTF 2026

Tài liệu phân tích hai thử thách của **HACKTHEON SEJONG 2026** (Hàn Quốc), đội **VSL_go0n**.

| Thử thách | Mảng | Nội dung chính | Tài liệu |
| :--- | :---: | :--- | :--- |
| **immutable** | Pwn | Stack buffer overflow 144 byte, `scanf("%s", buf)` không giới hạn độ dài → ghi đè luồng thực thi | [immutable.docx](<immutable.docx>) |
| **Recover It!** | Reverse | ELF 64-bit, phân tích tĩnh với IDA, gỡ nhiễu `ror8`/`rol8` để lần ra logic thật | [Recover It!.docx](<Recover It!.docx>) |

## Ghi chú

- Tài liệu gốc ở định dạng DOCX (có ảnh chụp màn hình minh họa từng bước).
- Nội dung phục vụ học tập; cờ (flag) thuộc về giải đấu đã kết thúc.
