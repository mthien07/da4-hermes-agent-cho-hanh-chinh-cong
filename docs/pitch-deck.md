# 📊 PITCH DECK — DA4: Hermes Agent cho Hành chính công
*10 Slides Presentation - Pitching tại Hội thi Khởi nghiệp đổi mới sáng tạo tỉnh Tây Ninh năm 2026*

---

## 🖥️ Slide 1: Trang bìa (Cover Page)
* **Tiêu đề:** HERMES AGENT CHO HÀNH CHÍNH CÔNG
* **Phụ đề:** Trợ lý AI điều phối tác vụ, soạn thảo văn bản và hỗ trợ cán bộ cấp xã/phường
* **Đơn vị thực hiện:** Hợp tác xã OneBee (Tây Ninh)
* **Ý tưởng dự thi:** Xây dựng lớp trợ lý AI có kiểm soát, giúp cán bộ xử lý công việc lặp lại nhanh hơn nhưng vẫn giữ quyền phê duyệt của con người.
* **Hình ảnh minh họa gợi ý:** Giao diện chat Hermes Agent, bảng quy trình công vụ, khung phê duyệt ký số và dashboard tiến độ hồ sơ.

---

## 🖥️ Slide 2: Vấn đề thị trường (The Problem)
* **Tiêu đề Slide:** Khối lượng hành chính tăng, cán bộ cơ sở thiếu công cụ điều phối thông minh
* **Nội dung chính:**
  1. **Nhiều việc lặp lại:** Soạn báo cáo, tổng hợp số liệu, viết thông báo, kiểm tra biểu mẫu và trả lời câu hỏi thường gặp.
  2. **Dữ liệu phân tán:** Văn bản, bảng tính, email, nhóm chat và phần mềm chuyên ngành chưa luôn liền mạch.
  3. **Áp lực thời gian:** Cán bộ phải xử lý hồ sơ, tiếp dân, báo cáo cấp trên và truyền thông cho người dân cùng lúc.
* **Bối cảnh Tây Ninh:** [Inference] Sau sắp xếp đơn vị hành chính, nhu cầu chuẩn hóa quy trình và hỗ trợ cán bộ cấp xã/phường có thể tăng.

---

## 🖥️ Slide 3: Giải pháp đột phá (The Solution)
* **Tiêu đề Slide:** Hermes Agent — AI điều phối công việc có kiểm soát
* **Nội dung chính:**
  * **Giải pháp:** Một giao diện chat tác vụ kết nối với bộ kỹ năng hành chính: soạn văn bản, tổng hợp báo cáo, tra cứu quy trình, nhắc việc và tạo biểu mẫu.
  * **Cách thức:** Cán bộ ra lệnh bằng tiếng Việt → Agent gọi công cụ phù hợp → tạo bản nháp → cán bộ kiểm tra và phê duyệt.
  * **Nguyên tắc vận hành:**
    * **Human-in-the-loop:** AI chỉ tạo nháp và đề xuất; người có thẩm quyền duyệt cuối.
    * **Truy vết:** Mỗi tác vụ có log, nguồn dữ liệu và trạng thái xử lý.
    * **Triển khai linh hoạt:** Có thể chạy nội bộ hoặc hybrid tùy yêu cầu bảo mật.

---

## 🖥️ Slide 4: Sản phẩm & Công nghệ (Product Architecture)
* **Tiêu đề Slide:** 4 lớp: Chat Command, Tools, Memory/Skills, Governance
* **Nội dung chính:**
  1. **Chat Command Center:** Cán bộ giao tiếp bằng tiếng Việt, chọn kịch bản hoặc nhập yêu cầu tự do.
  2. **Tool Layer:** Công cụ soạn thảo, tra cứu biểu mẫu, tổng hợp bảng số liệu, tạo lịch nhắc và gửi thông báo.
  3. **Memory & Skills:** Kho kỹ năng theo phòng ban: tư pháp, địa chính, y tế, văn hóa, văn thư.
  4. **Governance Layer:** Phân quyền, log tác vụ, nhãn cảnh báo, phê duyệt thủ công và xuất bản có kiểm soát.
* **Hình ảnh minh họa gợi ý:** Sơ đồ Agent ở trung tâm, kết nối hồ sơ, văn bản, dữ liệu phòng ban và lớp phê duyệt.

---

## 🖥️ Slide 5: Tiềm năng thị trường (TAM/SAM/SOM)
* **Tiêu đề Slide:** Hạ tầng AI tác vụ cho đơn vị hành chính cơ sở
* **Số liệu phân tích:**
  * **TAM (Thị trường tổng):** [Unverified] Các cơ quan hành chính cấp cơ sở và đơn vị sự nghiệp có nhu cầu số hóa quy trình văn bản, báo cáo, hỗ trợ người dân.
  * **SAM (Thị trường khả dụng):** Tỉnh Tây Ninh có 96 xã/phường mới theo danh sách công bố trên Cổng Thông tin điện tử Chính phủ.
  * **SOM (Thị trường khả đạt năm 1):** [Unverified] 1 - 3 đơn vị pilot, tập trung vào 5 - 10 kỹ năng hành chính có tần suất dùng cao.
* **Ghi chú kiểm chứng:** Số lượng 96 xã/phường cần đối chiếu nguồn khi đưa vào slide chính thức: https://xaydungchinhsach.chinhphu.vn/sap-xep-dvhc-danh-sach-96-xa-phuong-moi-cua-tinh-tay-ninh-11925062308221361.htm

---

## 🖥️ Slide 6: Mô hình kinh doanh (Business Model)
* **Tiêu đề Slide:** Tư vấn quy trình, triển khai Agent và duy trì kỹ năng
* **Cơ cấu doanh thu đề xuất:**
  * **Phí khảo sát & thiết kế quy trình:** 10 - 20 triệu VNĐ cho mỗi đơn vị pilot.
  * **Phí triển khai Hermes Agent:** 20 - 40 triệu VNĐ tùy số phòng ban, số kỹ năng và mức tích hợp.
  * **Phí duy trì/hỗ trợ:** 3 - 5 triệu VNĐ/tháng cho cập nhật kỹ năng, backup, giám sát và hỗ trợ người dùng.
  * **Phí đào tạo:** 5 triệu VNĐ/buổi cho nhóm cán bộ vận hành và nhóm quản trị.
* **Ghi chú:** [Unverified] Giá gói là giả định kinh doanh để trình bày, chưa phải báo giá chính thức.

---

## 🖥️ Slide 7: Phân tích cạnh tranh (Competition)
* **Tiêu đề Slide:** Không thay hệ thống hiện có, mà bổ sung lớp điều phối AI
* **Bảng so sánh:**

| Tiêu chí | Phần mềm quản lý văn bản | Chatbot hỏi đáp đơn lẻ | Hermes Agent OneBee |
|---|---|---|---|
| **Mục tiêu chính** | Luân chuyển và lưu trữ văn bản | Trả lời câu hỏi | **Điều phối tác vụ và tạo bản nháp** |
| **Khả năng thao tác công cụ** | Theo quy trình cố định | Hạn chế | **Có thể gọi tool/workflow theo kịch bản** |
| **Phê duyệt con người** | Có theo luồng văn bản | Thường không rõ | **Thiết kế human-in-the-loop từ đầu** |
| **Tùy biến kỹ năng địa phương** | Cần cấu hình lớn | Khó mở rộng | **Đóng gói skill theo phòng ban** |

---

## 🖥️ Slide 8: Chiến lược Go-To-Market (GTM)
* **Tiêu đề Slide:** Pilot nhỏ, đo hiệu quả thật, nhân rộng theo cụm kỹ năng
* **Chiến lược hành động:**
  1. **Chọn 1 đơn vị pilot:** Ưu tiên nơi có nhu cầu báo cáo và văn bản lặp lại cao.
  2. **Xây 10 kỹ năng đầu tiên:** Báo cáo tuần, thông báo dân cư, biên bản kiểm tra, tổng hợp số liệu, lịch nhắc việc.
  3. **Đo KPI trước/sau:** Thời gian soạn bản nháp, số bước thao tác, tỷ lệ văn bản phải sửa lại, mức hài lòng người dùng.
  4. **Chuẩn hóa tài liệu:** Tạo bộ hướng dẫn vận hành, quy trình phê duyệt và checklist bảo mật.

---

## 🖥️ Slide 9: Lộ trình phát triển (Roadmap)
* **Tiêu đề Slide:** 90 ngày có pilot, 12 tháng chuẩn hóa bộ kỹ năng
* **Nội dung chính:**
  * **Tháng 07/2026:** Khảo sát quy trình, chọn 5 kỹ năng hành chính dùng nhiều nhất và xây demo nội bộ.
  * **Tháng 08/2026:** Tích hợp lớp log, phân quyền, phê duyệt và dashboard theo dõi tác vụ.
  * **Tháng 09/2026:** Pilot tại 1 đơn vị, đo KPI, ghi nhận lỗi và hoàn thiện tài liệu chuyển giao.
  * **Năm 2027:** [Unverified] Mở rộng thành bộ Hermes Agent cho nhiều phòng ban, nhiều xã/phường và đơn vị sự nghiệp.

---

## 🖥️ Slide 10: Đội ngũ & Tác động xã hội
* **Tiêu đề Slide:** AI hỗ trợ cán bộ, phục vụ người dân tốt hơn
* **Nội dung chính:**
  * **Đội ngũ sáng lập:** OneBee Team — nhóm công nghệ tập trung vào AI ứng dụng, tự động hóa quy trình và chuyển giao công cụ cho người dùng phổ thông.
  * **Tác động xã hội:**
    * Giảm thời gian làm việc lặp lại cho cán bộ cơ sở.
    * Chuẩn hóa bản nháp văn bản và quy trình phê duyệt.
    * Tăng khả năng phản hồi nhanh cho người dân nhưng vẫn giữ kiểm soát của con người.
* **Thông điệp kết thúc:** *"Hermes Agent - AI phụ việc hành chính, con người giữ quyền quyết định."*
