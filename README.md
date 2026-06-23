<p align="center">
  <img src="https://img.shields.io/badge/🐝_HTX_OneBee-Hermes_Agent-dc2626?style=for-the-badge&labelColor=0a1628" alt="OneBee Hermes Agent"/>
</p>

<h1 align="center">🏛️ Hermes Agent cho Hành chính công</h1>

<p align="center">
  <strong>AI Copilot — Nâng cấp năng lượng điều hành cho cán bộ xã/phường</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hội_thi-KNĐMST_2026-f4b942?style=flat-square" alt="Contest"/>
  <img src="https://img.shields.io/badge/Giai_đoạn-Ý_tưởng-00d4aa?style=flat-square" alt="Stage"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/badge/HTX_OneBee-MST_1102128064-grey?style=flat-square" alt="Tax ID"/>
  <img src="https://img.shields.io/badge/Tây_Ninh-96_xã/phường-4d8bff?style=flat-square" alt="Coverage"/>
</p>

---

## 🎯 Vấn đề

Cán bộ cấp xã/phường tại Tây Ninh xử lý nhiều công việc hành chính lặp lại: soạn văn bản, tổng hợp báo cáo, thống kê số liệu, truyền thông địa phương. Ước tính **4-5 giờ/ngày** dành cho các tác vụ thủ công lặp lại.

## 💡 Giải pháp

**Hermes Agent** — không chỉ là chatbot, mà là một **lớp vận hành AI** (AI Operational Layer) giúp cán bộ ra lệnh bằng tiếng Việt tự nhiên, hệ thống tự động thực thi và chuẩn bị kết quả. Cán bộ vẫn **duyệt và ký cuối cùng** (Human-in-the-loop).

## 🏗️ Kiến trúc 3 Tầng Hermes Agent

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  ┌─────────────────────────────────────────────────────┐    │
│  │         💬 TẦNG 1: CHAT — Trung tâm chỉ huy         │    │
│  │                                                     │    │
│  │  Giao diện Zalo/Messenger-like                      │    │
│  │  "Tổng hợp báo cáo dân số tháng 6"                 │    │
│  │  "Soạn kịch bản truyền thanh phòng chống SXH"      │    │
│  └─────────────────────┬───────────────────────────────┘    │
│                        │ NLP tiếng Việt                     │
│  ┌─────────────────────▼───────────────────────────────┐    │
│  │         🔧 TẦNG 2: TOOLS — Công cụ thực thi          │    │
│  │                                                     │    │
│  │  📄 Đọc Word/PDF/Excel   🌐 Tra cứu pháp luật      │    │
│  │  📝 Soạn văn bản         🖨️ Chuẩn bị in ấn         │    │
│  │  📊 Tổng hợp số liệu    🔊 TTS giọng đọc           │    │
│  │  📧 Chuẩn bị email       🎨 Tạo ảnh/video          │    │
│  └─────────────────────┬───────────────────────────────┘    │
│                        │                                    │
│  ┌─────────────────────▼───────────────────────────────┐    │
│  │    🧠 TẦNG 3: MEMORY & SKILLS — Bộ nhớ & Kỹ năng    │    │
│  │                                                     │    │
│  │  📋 Skills phòng Địa chính                          │    │
│  │  📋 Skills phòng Tư pháp                            │    │
│  │  📋 Skills Trạm Y tế                                │    │
│  │  📋 Skills Văn hóa - Xã hội                         │    │
│  │  📋 Kho biểu mẫu + Mẫu lệnh + Quy trình           │    │
│  └─────────────────────────────────────────────────────┘    │
│                                                             │
│  🔒 ON-PREMISE │ AI mã nguồn mở │ Phân quyền phòng ban     │
└─────────────────────────────────────────────────────────────┘
```

## 📋 Kịch bản Ứng dụng theo Phòng ban

| Phòng ban | Skills | Ví dụ lệnh Chat |
|-----------|--------|------------------|
| 📊 **Văn phòng - Thống kê** | Báo cáo tháng, tổng hợp số liệu | _"Tổng hợp báo cáo dân số tháng 6"_ |
| ⚖️ **Tư pháp** | Tra cứu luật, soạn văn bản hành chính | _"Tra điều 15 Luật Đất đai 2024"_ |
| 🎭 **Văn hóa - Xã hội** | Bài phát thanh, poster sự kiện | _"Viết bài phát thanh phòng chống SXH"_ |
| 🗺️ **Địa chính** | Tra cứu thửa đất, tạo biên bản | _"Tạo biên bản kiểm tra thửa đất số 123"_ |
| 🏥 **Trạm Y tế** | Thống kê tiêm chủng, báo cáo dịch | _"Tổng hợp tiêm chủng trẻ em quý 2"_ |

## ✨ Tính năng chính

| Tính năng | Mô tả |
|-----------|-------|
| 💬 **Chat tiếng Việt** | Ra lệnh tự nhiên, giao diện quen thuộc như Zalo |
| 🔧 **Công cụ đa năng** | Đọc file, tra cứu luật, xuất văn bản, tạo media |
| 🧠 **Memory & Skills** | Học từ workflow, cải thiện theo thời gian |
| 👤 **Human-in-the-loop** | Cán bộ duyệt cuối cùng, AI chỉ hỗ trợ |
| 🔒 **On-premise** | Dữ liệu không rời mạng nội bộ |
| 📊 **Thinking Log** | Hiện quy trình suy nghĩ từng bước của AI |

## 🛠️ Công nghệ sử dụng

| Lớp | Công nghệ |
|-----|-----------|
| Chat UI | Web interface (Zalo/Messenger-like) |
| AI Engine | LLM mã nguồn mở (Llama 3, Mistral, Gemma) |
| AI Runtime | Ollama, vLLM (on-premise) |
| Tools | Python scripts, Document parsers, TTS |
| Workflow | n8n, custom Skills engine |
| Server | Ubuntu Server, Docker |
| Bảo mật | Phân quyền RBAC, audit log |

## 🚀 Chạy Demo

```bash
# Clone repo
git clone https://github.com/mthien07/da4-hermes-agent-cho-hanh-chinh-cong.git
cd da4-hermes-agent-cho-hanh-chinh-cong

# Mở demo web (không cần cài đặt)
open demo/index.html
```

> 💡 Demo web mô phỏng giao diện **Hermes Agent** với kịch bản phòng Địa chính, Trạm Y tế và Tuyên truyền. Bao gồm Thinking Log animation và Human-in-the-loop approval.

## 📁 Cấu trúc dự án

```
da4-hermes-agent-cho-hanh-chinh-cong/
├── demo/
│   └── index.html          # Web demo Hermes Agent Chat + Approval
├── docs/
│   ├── m02-m03-ho-so-du-thi.md  # Hồ sơ dự thi M-02 & M-03
│   ├── pitch-deck.md            # Pitch Deck (10 slides)
│   └── video-script.md          # Kịch bản video 3 phút
└── README.md
```

## 💰 Mô hình kinh doanh (B2G)

| Nguồn thu | Mô tả | Giá |
|-----------|-------|-----|
| 🔧 **Phí khởi tạo** | Setup Hermes Agent + Training cán bộ | 20-40 triệu/xã |
| 📆 **Thuê bao tháng** | Duy trì + Cập nhật Skills | 3-5 triệu/tháng |
| 🔌 **Mở rộng Tools** | Tính năng mới theo yêu cầu | 5-10 triệu/tool |
| 📚 **Đào tạo** | Workshop chuyên sâu cho cán bộ | 5 triệu/buổi |

## 🎯 Thị trường mục tiêu

- **Tây Ninh:** 96 xã/phường (sau sắp xếp 2025)
- **Toàn quốc:** 3.321 đơn vị cấp xã
- **Người dùng tiềm năng:** ~50.000 - 83.000 cán bộ

## 📌 Trạng thái dự án

- ✅ Hồ sơ dự thi M-02/M-03
- ✅ Pitch Deck
- ✅ Video Script
- ✅ Web Demo tương tác (Chat + Thinking Log + Approval)
- 🔄 Phát triển MVP & Pilot tại 1-2 UBND xã (theo kế hoạch)

## 📞 Liên hệ

**Hợp tác xã OneBee**
- 📍 45 đường số 6, KDC Thái Dương, Phường Long An, Tây Ninh
- 📱 0385 944 909
- 🔢 MST: 1102128064
- 👤 Người đại diện: HUỲNH TRỌNG HIẾU

---

<p align="center">
  <em>Dự án dự thi Hội thi Khởi nghiệp Đổi mới Sáng tạo tỉnh Tây Ninh năm 2026</em><br/>
  <strong>🐝 HTX OneBee — Chuyển đổi số cho cộng đồng</strong>
</p>
