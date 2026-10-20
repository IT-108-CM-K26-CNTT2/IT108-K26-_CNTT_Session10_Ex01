# Session 10 – Ex01: Sửa lỗi Heading Styles và Auto TOC (Smart Food SRS)

## 1. Phân tích

**Vì sao mục lục trống?**
Auto TOC chỉ quét các đoạn có style Heading 1, 2, 3... Mục "1. Giới thiệu" (Normal, 20pt) và "2. Yêu cầu chức năng" (Normal, 18pt) chỉ là chữ thường được phóng to bằng tay nên Word không coi là tiêu đề. Ngoài ra, định dạng tay buộc phải sửa từng trang, còn Style chỉ cần sửa 1 lần.

**Vì sao đoạn văn 5 trang hiện lên mục lục?**
Nam gán Heading 1 cho cả đoạn nội dung dài thay vì chỉ gán cho dòng tiêu đề. TOC lấy mọi đoạn mang Heading 1. Heading chỉ dành cho tiêu đề ngắn, nội dung phải dùng Normal.

## 2. Cách sửa

1. **Gỡ bẫy:** chọn đoạn 5 trang, nhấn `Ctrl + Shift + N` (về Normal).
2. **Gán Heading:** "1. Giới thiệu", "2. Yêu cầu chức năng" dùng `Ctrl + Alt + 1`; các mục con (1.1, 2.1...) dùng `Ctrl + Alt + 2`. Không nhảy cấp.
3. **Chỉnh style 1 lần:** chuột phải Heading 1, chọn Modify.
4. **Chèn TOC:** References, Table of Contents, Automatic Table.
5. **Cập nhật:** bấm vào TOC, nhấn `F9`, chọn Update entire table.

## 3. Checklist

- [ ] Không còn tiêu đề giả (Normal + phóng to)
- [ ] Navigation Pane chỉ hiện tiêu đề ngắn
- [ ] TOC đúng tiêu đề và số trang

## 4. Cấu trúc repo

```
├── README.md
├── SmartFood_SRS_BEFORE.docx
├── SmartFood_SRS_AFTER.docx
└── screenshots/
```
