# 🎬 VIDEO SCRIPT — DA4: Hermes Agent cho Hành chính công
**Thời lượng:** ≤ 3 phút | **Định dạng:** Screen recording dashboard + voice-over

---

## [00:00 – 00:20] Mở đầu — Đặt vấn đề
**Hình ảnh:** Montage nhanh: cán bộ mở nhiều file Word/Excel, trả lời tin nhắn, tìm mẫu văn bản, tổng hợp số liệu báo cáo.

**Lời thoại:**
> "Ở cấp cơ sở, một cán bộ phải xử lý rất nhiều việc lặp lại: soạn thông báo, tổng hợp báo cáo, kiểm tra biểu mẫu, nhắc lịch và phản hồi người dân."
> "Vấn đề không chỉ là thiếu phần mềm, mà là thiếu một lớp điều phối thông minh giữa con người, dữ liệu và quy trình."

---

## [00:20 – 00:40] Giới thiệu giải pháp
**Hình ảnh:** Logo OneBee và giao diện Hermes Agent xuất hiện.

**Lời thoại:**
> "Hermes Agent là trợ lý AI cho hành chính công: cán bộ ra lệnh bằng tiếng Việt, hệ thống gọi đúng công cụ, tạo bản nháp và chờ con người phê duyệt."
> "AI phụ việc. Cán bộ vẫn là người kiểm tra và quyết định cuối cùng."

---

## [00:40 – 01:35] Demo luồng chính
**Hình ảnh:** Mở `demo-da4/index.html` trên Chrome, quay màn hình:
1. Chọn một phòng ban/kịch bản ở thanh bên trái.
2. Bấm chạy tác vụ soạn văn bản hoặc tổng hợp báo cáo.
3. Quan sát Hermes Agent hiển thị từng bước xử lý.
4. Bản nháp văn bản xuất hiện ở khung bên phải.
5. Bấm phê duyệt/ký số trong demo.

**Lời thoại:**
> "Trong demo này, cán bộ chọn một kịch bản có sẵn."
> "Hermes Agent bắt đầu chạy: lấy ngữ cảnh, chọn biểu mẫu, điền dữ liệu, kiểm tra thiếu sót và tạo bản nháp."
> "Toàn bộ quá trình được ghi log để người quản trị biết AI đã làm gì."
> "Khi bản nháp hoàn thành, cán bộ đọc lại, chỉnh nếu cần, rồi mới phê duyệt."

---

## [01:35 – 02:05] Kiến trúc & kiểm soát rủi ro
**Hình ảnh:** Zoom vào các khối: Chat Command, Tools, Memory/Skills, Governance.

**Lời thoại:**
> "Hermes Agent có bốn lớp: chat điều phối, công cụ xử lý, bộ kỹ năng theo phòng ban và lớp quản trị."
> "Lớp quản trị rất quan trọng: phân quyền, log tác vụ, cảnh báo và phê duyệt thủ công."
> "Thiết kế này giúp AI hỗ trợ công việc nhưng không tự ý ban hành quyết định."

---

## [02:05 – 02:30] Mô hình triển khai
**Hình ảnh:** Infographic: khảo sát quy trình → xây 10 kỹ năng → pilot → đo KPI → nhân rộng.

**Lời thoại:**
> "OneBee triển khai theo hướng nhỏ và đo được: bắt đầu với một đơn vị pilot, chọn 5 đến 10 tác vụ lặp lại nhiều nhất."
> "Sau đó đo thời gian soạn bản nháp, số lần sửa, số bước thao tác và mức hài lòng của người dùng."
> "[Unverified] Các mức phí trong pitch là giả định kinh doanh, cần khảo sát và phê duyệt trước khi báo giá."

---

## [02:30 – 02:50] Giá trị xã hội
**Hình ảnh:** Cán bộ thao tác trên dashboard, người dân nhận thông báo rõ ràng hơn, bảng KPI thời gian xử lý giảm.

**Lời thoại:**
> "Hermes Agent không thay cán bộ. Hermes Agent giảm việc lặp lại để cán bộ có thêm thời gian xử lý việc cần phán đoán và tiếp xúc người dân."
> "Mục tiêu là hành chính công nhanh hơn, rõ hơn và vẫn có trách nhiệm giải trình."

---

## [02:50 – 03:00] Kết — Call to Action
**Hình ảnh:** Logo OneBee + tagline "AI phụ việc hành chính, con người giữ quyền quyết định".

**Lời thoại:**
> "Hermes Agent cho Hành chính công — từ HTX OneBee. AI phụ việc, quy trình rõ ràng, phục vụ người dân tốt hơn."

---

## 📌 Ghi chú sản xuất
- **Demo:** Mở `demo-da4/index.html` trên Chrome, quay screen recording
- **Nhấn mạnh:** AI chỉ tạo bản nháp và đề xuất, không tự ban hành văn bản
- **Cảnh báo số liệu:** KPI, giá và quy mô thị trường cần xác minh bằng pilot hoặc nguồn chính thức trước khi trình chiếu chính thức
- **Nhạc nền:** Corporate/technology nhẹ, tiết tấu rõ
