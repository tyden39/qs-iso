# Đặc tả thân biểu mẫu (47 BM) — nội dung riêng từng file

Bổ sung cho `plan.md`. Mỗi biểu mẫu = khung chung (header/title/footer) + **thân riêng** dưới đây.
Ký hiệu: `[F]` = trường nhập (Word/info đầu Excel); `[T]` = cột bảng; `Σ` = ô có công thức.

---
## KD — Kinh doanh

### 1. ISO.BM-KD-02-01 · Bảng báo giá · **Excel**
- [F] Kính gửi (KH), người liên hệ, ĐT, ngày báo giá, số báo giá, hiệu lực báo giá
- [T] STT | Mã hàng | Tên hàng hóa/dịch vụ | ĐVT | SL | Đơn giá | Thành tiền Σ(=SL×Đơn giá) | Ghi chú
- Σ Cộng tiền hàng (SUM), Thuế VAT 10%, Tổng cộng thanh toán, Bằng chữ
- [F] Điều kiện thanh toán, thời gian giao hàng, bảo hành

### 2. ISO.BM-KD-02-02 · Hợp đồng kinh tế · **Word**
- [F] Số HĐ, ngày; căn cứ pháp lý
- [F] BÊN A (mua) & BÊN B (bán): tên, địa chỉ, MST, đại diện, chức vụ, TK ngân hàng, ĐT
- Điều 1 Hàng hóa [T] STT|Tên hàng|ĐVT|SL|Đơn giá|Thành tiền
- Điều 2 Giá trị HĐ & thanh toán · Điều 3 Giao hàng · Điều 4 Bảo hành
- Điều 5 Quyền & nghĩa vụ · Điều 6 Điều khoản chung
- Chữ ký 2 bên (ĐẠI DIỆN BÊN A / ĐẠI DIỆN BÊN B)

### 3. ISO.BM-KD-03-01 · Phiếu tiếp nhận khiếu nại · **Word**
- [F] Số phiếu, ngày tiếp nhận
- [F] KH: tên, địa chỉ, ĐT, người liên hệ
- [F] SP/DV liên quan, SL, số HĐ/hóa đơn
- [F] Nội dung khiếu nại (ô lớn), hình thức tiếp nhận (ĐT/email/trực tiếp), yêu cầu của KH
- [F] Người tiếp nhận, bộ phận chuyển xử lý → ký: Người tiếp nhận / Trưởng BP

### 4. ISO.BM-KD-03-02 · Phân tích nguyên nhân & hướng xử lý · **Word**
- [F] Phiếu liên quan, ngày, mô tả vấn đề/sự KPH
- [F] Phân tích nguyên nhân (trực tiếp + gốc rễ, gợi ý 5-Why)
- [T] Nguyên nhân | Hành động khắc phục | Trách nhiệm | Thời hạn
- [F] Hành động phòng ngừa → ký: Người phân tích / Trưởng BP / Giám đốc

### 5. ISO.BM-KD-03-03 · Phiếu xác nhận xử lý khiếu nại · **Word**
- [F] Số phiếu, ngày, KH, tóm tắt khiếu nại
- [F] Biện pháp đã thực hiện, kết quả xử lý
- [F] Xác nhận KH (hài lòng/chưa) → ký: Người xử lý / Trưởng BP / Khách hàng

### 6. ISO.BM-KD-04-01 · Danh sách tiếp nhận bảo hành · **Excel**
- [T] STT | Ngày tiếp nhận | Tên KH | SĐT | Sản phẩm | Số seri/model | Tình trạng lỗi | Ngày hẹn trả | Trạng thái | Người tiếp nhận | Ghi chú

### 7. ISO.BM-KD-04-02 · Phân tích nguyên nhân & hướng xử lý bảo hành · **Word**
- [F] Phiếu BH liên quan, ngày, sản phẩm, số seri, mô tả lỗi, phân tích nguyên nhân
- [T] Nguyên nhân | Biện pháp xử lý | Linh kiện thay thế | Trách nhiệm | Thời hạn
- [F] Kết luận trong/ngoài BH, chi phí → ký 3 cấp

### 8. ISO.BM-KD-04-03 · Phiếu xác nhận bảo hành · **Word**
- [F] Số phiếu, ngày, KH, sản phẩm, số seri, nội dung lỗi & biện pháp đã thực hiện
- [T] Linh kiện thay thế: STT|Tên|ĐVT|SL
- [F] Kết quả, thời hạn BH tiếp theo, xác nhận KH → ký

---
## KT — Xuất kho thành phẩm

### 9. ISO.BM-KT-05-01 · Phiếu xuất kho thành phẩm · **Excel**
- [F] Số phiếu, ngày, người nhận, bộ phận liên quan, lý do xuất, xuất tại kho
- [T] STT|Mã hàng|Tên thành phẩm|ĐVT|SL yêu cầu|SL thực xuất|Đơn giá|Thành tiền Σ|Ghi chú
- Σ Tổng cộng · ký: Người lập / Người nhận / Thủ kho / KT trưởng / Giám đốc

### 10. ISO.BM-KT-05-02 · Phiếu giao hàng · **Excel**
- [F] Số phiếu, ngày giao, KH/người nhận, địa chỉ giao, số HĐ/đơn hàng, phương tiện
- [T] STT|Mã hàng|Tên hàng|ĐVT|SL|Quy cách/đóng gói|Ghi chú
- ký: Người giao / Người nhận / Thủ kho

---
## MH — Mua hàng

### 11. ISO.BM-MH-06-01 · Phiếu yêu cầu mua hàng · **Excel**
- [F] Số phiếu, ngày, bộ phận yêu cầu, người yêu cầu, mục đích, ngày cần hàng
- [T] STT|Tên vật tư/hàng hóa|Quy cách/kỹ thuật|ĐVT|SL|Mức ưu tiên|Ghi chú
- ký: Người yêu cầu / Trưởng BP / P.Mua hàng / Giám đốc duyệt

### 12. ISO.BM-MH-06-02 · Hợp đồng/Đơn đặt hàng mua (PO) · **Excel**
- [F] Số PO, ngày; NCC: tên, địa chỉ, MST, người LH, ĐT; điều kiện giao hàng & thanh toán
- [T] STT|Mã VT|Tên hàng|ĐVT|SL|Đơn giá|Thành tiền Σ|Ghi chú
- Σ Tổng, VAT, tổng cộng, bằng chữ · ký: Bên mua / Bên bán

### 13. ISO.BM-MH-07-01 · Phiếu thông tin nhà cung cấp mới · **Word**
- [F] Tên NCC, tên giao dịch, địa chỉ, MST, website
- [F] Đại diện (chức vụ, ĐT, email); người liên hệ (ĐT, email)
- [F] Lĩnh vực/sản phẩm chính; TK ngân hàng
- [F] Năng lực: năm thành lập, quy mô, chứng chỉ (ISO…); điều kiện thanh toán/giao hàng
- [F] Đánh giá ban đầu → ký: Người lập / P.Mua hàng / Giám đốc

### 14. ISO.BM-MH-07-03 · Sổ theo dõi, đánh giá nhà cung cấp · **Excel**
- [T] STT|Tên NCC|Mặt hàng|Chất lượng(đ)|Giá cả(đ)|Giao hàng(đ)|Dịch vụ(đ)|Tổng điểm Σ|Xếp loại|Kỳ ĐG|Người ĐG|Ghi chú
- Chú thích thang điểm + quy ước xếp loại A/B/C

### 15. ISO.BM-MH-08-01 · Phiếu nhập kho vật tư · **Excel**
- [F] Số phiếu, ngày nhập, NCC, số HĐ/PO, người giao, nhập tại kho
- [T] STT|Mã VT|Tên vật tư|ĐVT|SL theo CT|SL thực nhập|Đơn giá|Thành tiền Σ|Ghi chú
- Σ Tổng · ký: Người lập / Người giao / Thủ kho / Kế toán / Giám đốc

### 16. ISO.BM-MH-08-02 · Biên bản kiểm tra hàng hóa · **Word**
- [F] Số BB, ngày, địa điểm, thành phần (bên giao/nhận/QC)
- [F] Lô hàng: NCC, số HĐ/PO
- [T] STT|Tên hàng|ĐVT|SL|Tiêu chuẩn KT|Kết quả (Đạt/Không)|Ghi chú
- [F] Kết luận: chấp nhận/trả lại/xử lý → ký các bên

---
## KHO

### 17. ISO.BM-KHO-09-01 · Phiếu xuất kho vật tư · **Excel**
- [F] Số phiếu, ngày, người nhận, bộ phận sử dụng, mục đích/lệnh SX, xuất tại kho
- [T] STT|Mã VT|Tên vật tư|ĐVT|SL yêu cầu|SL thực xuất|Đơn giá|Thành tiền Σ|Ghi chú
- Σ Tổng · ký: Người lập / Người nhận / Thủ kho / KT trưởng / Giám đốc

### 18. ISO.BM-KHO-10-01 · Phiếu nhập kho thành phẩm · **Excel**
- [F] Số phiếu, ngày, từ bộ phận SX/lệnh SX, người giao, nhập tại kho
- [T] STT|Mã TP|Tên thành phẩm|ĐVT|SL|Quy cách|Kết quả QC|Ghi chú
- ký: Người lập / Người giao / Thủ kho / QC

### 19. ISO.BM-QC-10-02 · Phiếu kiểm tra chất lượng thành phẩm · **Word**
- [F] Số phiếu, ngày, lệnh SX/lô, tên TP, mã, SL kiểm
- [T] STT|Hạng mục kiểm tra|Tiêu chuẩn/Yêu cầu|Phương pháp|Kết quả đo|Đánh giá(Đạt/Không)|Ghi chú
- [F] Kết luận chung Đạt/Không → ký: NV QC / Trưởng QC

---
## NS — Nhân sự

### 20. ISO.BM-NS-11-01 · Mẫu yêu cầu tuyển dụng · **Word**
- [F] Số phiếu, ngày, bộ phận; vị trí tuyển, SL, lý do (thay thế/bổ sung/mở rộng)
- [F] Mô tả công việc; yêu cầu (trình độ, kinh nghiệm, kỹ năng, tuổi, giới tính)
- [F] Mức lương dự kiến, hình thức (chính thức/thời vụ), thời gian cần
- ký: Người yêu cầu / Trưởng BP / P.Nhân sự / Giám đốc duyệt

### 21. ISO.BM-NS-11-02 · Đánh giá ứng viên & kết quả thử việc · **Word**
- Phần 1 — Đánh giá phỏng vấn: [F] họ tên ƯV, vị trí, ngày PV
  - [T] Tiêu chí (trình độ/kinh nghiệm/kỹ năng/thái độ/ngoại hình)|Điểm|Nhận xét → kết luận Đạt/Không
- Phần 2 — Kết quả thử việc: [F] thời gian thử việc
  - [T] Tiêu chí kết quả công việc|Điểm|Nhận xét → kết luận ký HĐ chính thức/không
- ký: Người ĐG / Trưởng BP / Giám đốc

### 22. ISO.BM-NS-12-01 · Kế hoạch đào tạo · **Excel**
- [F] Năm/kỳ kế hoạch, bộ phận
- [T] STT|Nội dung/khóa ĐT|Mục tiêu|Đối tượng|SL|Hình thức (nội bộ/ngoài)|Giảng viên/Đơn vị|Thời gian dự kiến|Chi phí dự kiến|Ghi chú
- Σ Tổng chi phí · ký: Người lập / P.Nhân sự / Giám đốc

### 23. ISO.BM-NS-12-02 · Đánh giá sau đào tạo · **Word**
- [F] Họ tên, bộ phận, khóa ĐT, thời gian, giảng viên
- [T] Tiêu chí (nội dung/giảng viên/tài liệu/tổ chức)|Điểm|Nhận xét
- [F] Mức độ tiếp thu/áp dụng, kết quả kiểm tra, đề xuất → ký: Học viên / Quản lý trực tiếp / P.Nhân sự

---
## QC — Sản phẩm không đạt

### 24. ISO.BM-QC-13-01 · Phiếu kiểm soát sản phẩm không đạt · **Word**
- [F] Số phiếu, ngày, nơi phát hiện, SP/bán TP, mã, SL không đạt, lệnh SX/lô
- [F] Mô tả lỗi/sự KPH, phân loại lỗi
- [F] Đề xuất xử lý (sửa/loại bỏ/nhân nhượng/trả NCC) → ký: Người lập / Trưởng QC / Giám đốc

### 25. ISO.BM-QC-13-02 · Biên bản xử lý sản phẩm không đạt · **Word**
- [F] Số BB, ngày, thành phần; tham chiếu phiếu kiểm soát số…; SP, SL, mô tả lỗi
- [F] Phân tích nguyên nhân
- [T] Biện pháp xử lý | Trách nhiệm | Thời hạn
- [F] Kết quả xử lý, chi phí, hành động phòng ngừa → ký các bên

---
## RD — Thiết kế thiết bị điện tử

### 26. ISO.BM-RD-14-01 · Lệnh thiết kế sản phẩm điện tử · **Word**
- [F] Số lệnh, ngày, người yêu cầu/KH, tên SP, mã dự án
- [F] Yêu cầu kỹ thuật/thông số đầu vào, mục tiêu thiết kế, tiêu chuẩn áp dụng
- [F] Người phụ trách/nhóm, tiến độ (bắt đầu–hoàn thành) → ký: Người lập / Trưởng RD / Giám đốc

### 27. ISO.BM-RD-14-02 · Bản vẽ thiết kế & danh sách linh kiện (BOM) · **Excel**
- [F] Tên SP, mã dự án, phiên bản, người thiết kế, ngày; vùng tham chiếu bản vẽ
- [T] STT|Mã linh kiện|Tên linh kiện|Thông số/Giá trị|Package/Footprint|ĐVT|SL|NSX/NCC|Ghi chú
- Σ Tổng số linh kiện · ký: Người thiết kế / Kiểm tra / Phê duyệt

### 28. ISO.BM-RD-14-03 · Quy trình công nghệ sản xuất · **Word**
- [F] Tên SP, mã, phiên bản; sơ đồ các bước công nghệ
- [T] Bước|Tên công đoạn|Nội dung thực hiện|Thiết bị/Dụng cụ|Thông số kỹ thuật|Tiêu chuẩn kiểm tra|Ghi chú
- [F] Yêu cầu an toàn → ký: Người lập / Kiểm tra / Phê duyệt

### 29. ISO.BM-KD-03-00 · Phiếu tiếp nhận yêu cầu · **Word**
- [F] Số phiếu, ngày tiếp nhận, KH/người yêu cầu, ĐT, email
- [F] Nội dung yêu cầu (SP/DV/thiết kế), yêu cầu kỹ thuật, SL, thời gian mong muốn
- [F] Hình thức tiếp nhận, bộ phận chuyển xử lý → ký: Người tiếp nhận / Trưởng BP

---
## KEHO — Kế hoạch sản xuất / thi công

### 30. ISO.BM-KEHO-15-01 · Lệnh sản xuất · **Word**
- [F] Số lệnh SX, ngày, ngày giao hàng, tên SP, mã, SL, đơn hàng/HĐ
- [T] Định mức VT: STT|Mã VT|Tên VT|ĐVT|Định mức|SL cần|Ghi chú
- [F] Bộ phận thực hiện, người phụ trách, tiến độ, yêu cầu chất lượng → ký: Người lập / Trưởng KH / Giám đốc

### 31. ISO.BM-QC-15-02 · Phiếu kiểm tra chất lượng SP (dùng chung TBĐT + Máy) · **Word**
- [F] Số phiếu, ngày, lệnh SX/lô, tên SP, mã, SL
- [T] STT|Hạng mục kiểm tra|Tiêu chuẩn/Yêu cầu|Phương pháp/Thiết bị đo|Kết quả|Đánh giá(Đạt/Không)|Ghi chú
- [F] Kết luận Đạt/Không → ký: NV QC / Trưởng QC

### 32. ISO.BM-KEHO-16-01 · Lệnh thi công · **Word**
- [F] Số lệnh, ngày, công trình/dự án, địa điểm, KH, HĐ liên quan
- [F] Nội dung/hạng mục thi công, đội/người phụ trách
- [T] Vật tư/thiết bị cần: STT|Tên|ĐVT|SL
- [F] Tiến độ, yêu cầu an toàn/chất lượng → ký: Người lập / Trưởng KH / Giám đốc

### 33. ISO.BM-UD-16-02 · Biên bản nghiệm thu công trình · **Word**
- [F] Số BB, ngày, công trình, địa điểm; Bên A (CĐT/KH), Bên B (thi công)
- [T] STT|Hạng mục|Khối lượng/Quy cách|Tiêu chuẩn|Kết quả(Đạt/Không)|Ghi chú
- [F] Kết luận nghiệm thu, tồn tại & hướng khắc phục → ký: Đại diện bên A / bên B

---
## SX-UD — Quản lý máy móc thiết bị

### 34. SX.BM-UD-01-01 · Danh sách máy móc thiết bị · **Excel**
- [T] STT|Mã thiết bị|Tên máy/thiết bị|Model/Hãng|Thông số kỹ thuật|Năm SX|Ngày đưa vào SD|Vị trí/Bộ phận|Tình trạng|Ghi chú

### 35. SX.BM-UD-01-03 · Kế hoạch bảo trì bảo dưỡng · **Excel**
- [F] Năm kế hoạch
- [T] STT|Mã TB|Tên máy/thiết bị|Nội dung bảo trì|Chu kỳ|T1…T12 (đánh dấu lịch)|Người thực hiện|Ghi chú

### 36. SX.BM-UD-01-04 · Kết quả bảo trì bảo dưỡng · **Excel**
- [T] STT|Ngày thực hiện|Mã TB|Tên máy|Nội dung bảo trì/sửa chữa|Linh kiện thay thế|Chi phí|Kết quả|Người thực hiện|Người kiểm tra|Ghi chú

---
## QC-UD — Quản lý thiết bị đo lường

### 37. ISO.BM-QC-01-01 · Danh sách thiết bị đo lường · **Excel**
- [T] STT|Mã TB|Tên thiết bị đo|Model/Hãng|Phạm vi đo|Độ chính xác/Cấp CX|Vị trí SD|Chu kỳ hiệu chuẩn|HC gần nhất|HC kế tiếp|Tình trạng|Ghi chú

### 38. QC.BM-01-02 · Hướng dẫn hiệu chuẩn nội bộ · **Word**
- [F] Thiết bị áp dụng, mã HD, mục đích, phạm vi, tài liệu tham chiếu/tiêu chuẩn
- [F] Thiết bị chuẩn, điều kiện môi trường
- [T] Bước|Nội dung|Yêu cầu
- [F] Tiêu chí chấp nhận, xử lý kết quả & dán tem → ký: Người lập / Kiểm tra / Phê duyệt

### 39. QC.BM-01-03 · Kế hoạch hiệu chuẩn/kiểm định · **Excel**
- [F] Năm kế hoạch
- [T] STT|Mã TB|Tên thiết bị|Chu kỳ|HC gần nhất|Kế hoạch (tháng)|Đơn vị thực hiện (nội bộ/ngoài)|Chi phí dự kiến|Ghi chú

### 40. QC.BM-01-04 · Báo cáo hiệu chuẩn/kiểm định · **Word**
- [F] Số báo cáo, ngày; thiết bị: tên, mã, model, phạm vi đo; thiết bị chuẩn; điều kiện môi trường
- [T] Điểm đo|Giá trị chuẩn|Giá trị đọc|Sai số|Sai số cho phép|Đánh giá
- [F] Kết luận Đạt/Không, hạn HC tiếp → ký: Người hiệu chuẩn / Kiểm tra / Phê duyệt

---
## GC — Gia công CNC

### 41. ISO.BM-GC-18-01 · Bản vẽ thiết kế gia công CNC · **Word**
- Title block: [F] tên chi tiết, mã, vật liệu, SL, tỷ lệ, phiên bản
- Vùng bản vẽ (placeholder hình)
- [T] Dung sai/yêu cầu kỹ thuật + ghi chú gia công → ký: Người vẽ / Kiểm tra / Phê duyệt

### 42. ISO.BM-GC-18-02 · Phiếu kiểm tra thành phẩm CNC · **Word**
- [F] Số phiếu, ngày, lệnh SX/lô, tên chi tiết, mã, SL
- [T] STT|Kích thước/Hạng mục|Yêu cầu (danh nghĩa ± dung sai)|Dụng cụ đo|Kết quả đo|Đánh giá(Đạt/Không)|Ghi chú
- [F] Kết luận → ký: NV QC / Trưởng QC

### 43. ISO.BM-KEHO-18-03 · Lệnh sản xuất (CNC) · **Word**
- [F] Số lệnh, ngày, ngày giao, tên chi tiết/SP, mã, SL, đơn hàng
- [T] Vật liệu: Mã|Tên|ĐVT|Định mức|SL
- [F] Máy CNC, chương trình NC, người phụ trách, tiến độ → ký: Người lập / Trưởng KH / Giám đốc

---
## TK — Thiết kế / Chế tạo máy

### 44. ISO.BM-TK-19-01 · Bản vẽ thiết kế máy đã phê duyệt (DMF) · **Word**
- Title block: [F] tên máy, mã dự án/DMF, phiên bản, khách hàng
- Vùng bản vẽ tổng thể (placeholder)
- [T] Danh mục bản vẽ chi tiết: STT|Số bản vẽ|Tên|Phiên bản
- [F] Thông số kỹ thuật chính, trạng thái phê duyệt → ký: Người thiết kế / Kiểm tra / Phê duyệt (đã duyệt)

### 45. ISO.BM-KEHO-19-02 · Kế hoạch thời gian thi công máy · **Excel**
- [F] Tên máy/dự án, khách hàng
- [T] STT|Hạng mục công việc|Người phụ trách|Bắt đầu|Kết thúc|Số ngày Σ|Tiến độ %|Tuần 1…n (đánh dấu)|Ghi chú

### 46. ISO.BM-KEHO-20-01 · Lệnh chế tạo máy · **Word**
- [F] Số lệnh, ngày, ngày giao, tên máy, mã dự án, SL, KH/đơn hàng, bản vẽ tham chiếu (DMF)
- [T] Vật tư/linh kiện chính: STT|Mã|Tên|ĐVT|SL|Ghi chú
- [F] Các bộ phận tham gia, người phụ trách, tiến độ tổng → ký: Người lập / Trưởng KH / Giám đốc

### 47. ISO.BM-TK-20-02 · Phiếu kiểm tra NVL đầu vào · **Word**
- [F] Số phiếu, ngày, NCC, số HĐ/PO, lô
- [T] STT|Tên NVL|ĐVT|SL|Tiêu chuẩn/Yêu cầu|Phương pháp KT|Kết quả|Đánh giá(Đạt/Không)|Ghi chú
- [F] Kết luận: nhập kho/trả lại → ký: NV KCS / Thủ kho / Trưởng QC

---
**Tổng: 47 biểu mẫu** — 27 Word + 20 Excel. Thân mỗi biểu mẫu khác nhau như trên; chỉ header/title/footer dùng chung.
