# Kế hoạch tạo biểu mẫu ISO (BM) theo ds.bm.md

Status: PLANNED — chưa thực thi
Ngày: 2026-06-14
Nguồn: `ds.bm.md` (48 dòng, 47 biểu mẫu duy nhất — 1 trùng)
Tham khảo: 3 file mẫu hiện có (2 .docx + 1 .xlsx)

## 1. Mục tiêu
Tạo toàn bộ biểu mẫu trong `ds.bm.md` dưới dạng `.docx` (Word) hoặc `.xlsx` (Excel),
đồng bộ theo "khung biểu mẫu ISO" rút ra từ 3 file mẫu.

## Quyết định đã chốt (2026-06-14)
1. Tên công ty header: **QS Technology**.
2. Ngày ban hành: **15/06/2026** (ngày mai); Lần ban hành: **01**.
3. Chuẩn hóa mã: **kiểu toàn dấu gạch ngang** `<ORG>.BM-<DEPT>-<NN>-<NN>` (dễ nhìn, đồng bộ
   với phần lớn mã sẵn có). Đổi 7 mã dùng dấu chấm/thừa dấu (xem cột "Mã chuẩn hóa" mục 3).
4. `ISO.BM-QC-15-02` (dòng 31 & 48) = **1 biểu mẫu dùng chung** → sinh 1 file. Kiểm tra NVL
   đầu vào là biểu mẫu riêng `ISO.BM-TK-20-02` (#47). ⇒ tổng vẫn 47 file.
5. Giữ nguyên phân loại Word/Excel (đã duyệt).
6. Tên file: **`<mã chuẩn hóa> <tên tiếng Việt>.<ext>`** (mã trước, tên sau, có dấu).
   Xuất theo thư mục bộ phận: `bm/<DEPT>/`.
7. Ghi 7 mã chuẩn hóa **ngược lại vào `ds.bm.md`** khi chạy.
8. `ISO.BM-QC-15-02` = **1 file dùng chung** (không tách).
9. Header **chỉ chữ** `CÔNG TY QS TECHNOLOGY`, không cần logo ảnh.

## 2. Khung chuẩn rút ra từ file mẫu (áp dụng cho MỌI biểu mẫu)
- **Header (bảng 2 ô):**
  - Ô trái: `CÔNG TY QS TECHNOLOGY`
  - Ô phải: `Mã số: <mã BM>` / `Ngày ban hành: 15/06/2026` / `Lần ban hành: 01`
- **Tiêu đề:** căn giữa, IN HOA, đậm = tên biểu mẫu.
- **Thân:** trường nhập + bảng dữ liệu tùy loại biểu mẫu.
- **Footer chữ ký:** `Người lập | Kiểm tra | Giám đốc` (3 cột).
- Font: Times New Roman 11–13, khổ A4. Word có thể landscape nếu bảng rộng.

## 3. Phân loại Word vs Excel (47 biểu mẫu)
Quy tắc: log/danh sách/kế hoạch nhiều dòng + tính toán → **Excel**;
chứng từ một-lần (phiếu/biên bản/hợp đồng/lệnh/báo cáo/quy trình) → **Word**.

| # | Mã | Tên | Loại |
|--|----|-----|------|
| 1 | ISO.BM-KD-02-01 | Bảng báo giá | Excel |
| 2 | ISO.BM-KD-02-02 | Hợp đồng kinh tế | Word |
| 3 | ISO.BM-KD-03-01 | Phiếu tiếp nhận khiếu nại | Word |
| 4 | ISO.BM-KD-03-02 | Phân tích nguyên nhân & hướng xử lý | Word |
| 5 | ISO.BM-KD-03-03 | Phiếu xác nhận xử lý khiếu nại | Word |
| 6 | ISO.BM-KD-04-01 | Danh sách tiếp nhận bảo hành | Excel |
| 7 | ISO.BM-KD-04-02 | Phân tích nguyên nhân & hướng xử lý bảo hành | Word |
| 8 | ISO.BM-KD-04-03 | Phiếu xác nhận bảo hành | Word |
| 9 | ISO.BM-KT-05-01 | Phiếu xuất kho thành phẩm | Excel |
| 10 | ISO.BM-KT-05-02 | Phiếu giao hàng | Excel |
| 11 | ISO.BM-MH-06-01 | Phiếu yêu cầu mua hàng | Excel |
| 12 | ISO.BM-MH-06-02 | Hợp đồng/Đơn đặt hàng mua (PO) | Excel |
| 13 | ISO.BM-MH-07-01 | Phiếu thông tin nhà cung cấp mới | Word |
| 14 | ISO.BM-MH-07-03 | Sổ theo dõi, đánh giá nhà cung cấp | Excel |
| 15 | ISO.BM-MH-08-01 | Phiếu nhập kho vật tư | Excel |
| 16 | ISO.BM-MH-08-02 | Biên bản kiểm tra hàng hóa | Word |
| 17 | ISO.BM-KHO-09-01 | Phiếu xuất kho vật tư | Excel |
| 18 | ISO.BM-KHO-10-01 | Phiếu nhập kho thành phẩm | Excel |
| 19 | ISO.BM-QC-10-02 | Phiếu kiểm tra chất lượng thành phẩm | Word |
| 20 | ISO.BM-NS-11-01 | Mẫu yêu cầu tuyển dụng | Word |
| 21 | ISO.BM-NS-11-02 | Đánh giá ứng viên & kết quả thử việc | Word |
| 22 | ISO.BM-NS-12-01 | Kế hoạch đào tạo | Excel |
| 23 | ISO.BM-NS-12-02 | Đánh giá sau đào tạo | Word |
| 24 | ISO.BM-QC-13-01 | Phiếu kiểm soát sản phẩm không đạt | Word |
| 25 | ISO.BM-QC-13-02 | Biên bản xử lý sản phẩm không đạt | Word |
| 26 | ISO.BM-RD-14-01 | Lệnh thiết kế sản phẩm điện tử | Word |
| 27 | ISO.BM-RD-14-02 | Bản vẽ thiết kế & danh sách linh kiện (BOM) | Excel |
| 28 | ISO.BM-RD-14-03 | Quy trình công nghệ sản xuất | Word |
| 29 | ISO.BM-KD-03-00 | Phiếu tiếp nhận yêu cầu | Word |
| 30 | ISO.BM-KEHO-15-01 | Lệnh sản xuất | Word |
| 31 | ISO.BM-QC-15-02 | Phiếu kiểm tra chất lượng SP | Word |
| 32 | ISO.BM-KEHO-16-01 | Lệnh thi công | Word |
| 33 | ISO.BM-UD-16-02 | Biên bản nghiệm thu công trình | Word |
| 34 | SX.BM-UD-01-01 *(gốc: SX.BM-UD.01.01)* | Danh sách máy móc thiết bị | Excel |
| 35 | SX.BM-UD-01-03 *(gốc: SX.BM-UD-.01.03)* | Kế hoạch bảo trì bảo dưỡng | Excel |
| 36 | SX.BM-UD-01-04 *(gốc: SX.BM-UD-.01.04)* | Kết quả bảo trì bảo dưỡng | Excel |
| 37 | ISO.BM-QC-01-01 *(gốc: ISO.BM-QC.01.01)* | Danh sách thiết bị đo lường | Excel |
| 38 | QC.BM-01-02 *(gốc: QC.BM.01.02)* | Hướng dẫn hiệu chuẩn nội bộ | Word |
| 39 | QC.BM-01-03 *(gốc: QC.BM.01.03)* | Kế hoạch hiệu chuẩn/kiểm định | Excel |
| 40 | QC.BM-01-04 *(gốc: QC.BM.01.04)* | Báo cáo hiệu chuẩn/kiểm định | Word |
| 41 | ISO.BM-GC-18-01 | Bản vẽ thiết kế gia công CNC | Word |
| 42 | ISO.BM-GC-18-02 | Phiếu kiểm tra thành phẩm CNC | Word |
| 43 | ISO.BM-KEHO-18-03 | Lệnh sản xuất (CNC) | Word |
| 44 | ISO.BM-TK-19-01 | Bản vẽ thiết kế máy đã phê duyệt (DMF) | Word |
| 45 | ISO.BM-KEHO-19-02 | Kế hoạch thời gian thi công máy | Excel |
| 46 | ISO.BM-KEHO-20-01 | Lệnh chế tạo máy | Word |
| 47 | ISO.BM-TK-20-02 | Phiếu kiểm tra NVL đầu vào | Word |
| — | ISO.BM-QC-15-02 | (dòng 48 = dùng chung với #31 TBĐT + Máy) | gộp vào #31 |

**Tổng:** 27 Word + 20 Excel = 47 file.

## 3b. Đặc tả thân từng biểu mẫu
Thân (trường nhập + cột bảng + công thức) của cả 47 biểu mẫu — mỗi cái KHÁC nhau —
xem file: [`bm-body-specification.md`](./bm-body-specification.md).

## 4. Cách thực thi (DRY)
1. **Helper dùng chung** (1 file Python, dùng venv skill `docx`/`xlsx`):
   - `add_iso_header(doc, ma_so)` — bảng header 2 ô.
   - `add_title(doc, ten)` — tiêu đề căn giữa in hoa.
   - `add_signature_footer(doc)` — 3 cột chữ ký.
   - bản Excel tương đương (openpyxl): header ở góc phải, tiêu đề merge, freeze panes, viền.
2. **Config từng biểu mẫu**: 1 dict `{ma, ten, loai, fields[], columns[]}` cho 47 biểu mẫu.
3. Sinh hàng loạt → xuất ra thư mục `bm/` (hoặc theo bộ phận: `bm/KD`, `bm/MH`...).
4. Kiểm tra: mở lại 3–5 file đại diện bằng python-docx/openpyxl, xác nhận header/tiêu đề/bảng đúng.

## 5. Khuyến nghị Model & Effort (chạy ở session khác)
Công việc = sinh tài liệu theo khuôn mẫu, lặp lại nhiều, độ phức tạp THẤP nhưng KHỐI LƯỢNG LỚN.

- **Bước thiết kế khung + helper + duyệt 2–3 mẫu đầu:** `Opus 4.8` hoặc `Sonnet 4.6`, **effort: high** — cần quyết định layout từng nhóm biểu mẫu cho chuẩn.
- **Bước sinh hàng loạt 47 file + kiểm tra:** `Sonnet 4.6`, **effort: medium** — tiết kiệm chi phí, đủ năng lực cho việc lặp.
- Nếu muốn làm 1 lượt gọn trong 1 session: `Sonnet 4.6`, **effort: high** (cân bằng chi phí/chất lượng). Tránh Opus cho cả 47 file vì lãng phí.
- Bật skill `docx` và `xlsx` (đã có sẵn venv) thay vì tự cài thư viện.

## 6. Câu hỏi còn lại
Không còn — tất cả đã chốt. Sẵn sàng thực thi ở session khác.
