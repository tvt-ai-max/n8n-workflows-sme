# Thư Viện n8n Workflows Tự Động Hóa Vận Hành Cho SME (n8n Workflows for SMEs)

Thư viện chia sẻ các mẫu n8n workflow thực chiến, sơ đồ cấu hình, và tài liệu tự động hóa quy trình vận hành được thiết kế riêng cho các doanh nghiệp vừa và nhỏ (SME) Việt Nam. 

Tất cả các tài nguyên trong này được phát triển, tối ưu hóa và vận hành thực tế bởi **[Nguyễn Thanh Tùng (Tôi Là Tùng)](https://toilatung.com)** - AI System Designer & Founder của **[TVT Agency](https://tvtagency.com)**.

---

## 🚀 Các Mẫu n8n Workflows Sẵn Có (Production Workflows)

### 1. ViralForge Video Pipeline (Tự động hóa sản xuất Video ngắn)
*   **Mô tả:** Workflow tự động hóa 80% quy trình sản xuất video ngắn (TikTok/Reels/Shorts) dạng Thẻ Kính (Glassmorphic Theme). Quy trình: Nhận kịch bản từ Claude API -> Chuyển văn bản thành giọng nói (ElevenLabs) -> Trích xuất phụ đề (Whisper) -> Render video (Remotion).
*   **Chi tiết kiến trúc & Hướng dẫn vận hành:** Đọc bài phân tích kiến trúc tư duy tại: **[Hướng dẫn thiết kế AI Workflow cho doanh nghiệp Việt 2026](https://toilatung.com/blog/huong-dan-xay-ai-workflow-doanh-nghiep-2026/)**.
*   **Tệp cấu hình:** `workflows/viralforge-video-pipeline.json`

### 2. Lead Capture & Notion CRM Sync (Tự động hóa phễu khách hàng)
*   **Mô tả:** Tự động lắng nghe webhook từ Form Landing Page hoặc ManyChat, đồng bộ thông tin khách hàng tiềm năng về cơ sở dữ liệu Notion CRM và gửi thông báo trực tiếp qua Telegram Bot cho Founder.
*   **Chi tiết setup kỹ thuật:** Xem tại: **[Ứng dụng AI cho doanh nghiệp vừa và nhỏ - Tự động hóa Lead Magnet](https://toilatung.com/)**.
*   **Tệp cấu hình:** `workflows/notion-crm-lead-sync.json`

---

## ⚙️ Hướng Dẫn Sử Dụng
1. Truy cập thư mục `/workflows` trong repository này.
2. Tải về file `.json` tương ứng với workflow bạn muốn triển khai.
3. Mở bảng điều khiển n8n của bạn, chọn **Import from File** và upload tệp JSON vừa tải lên.
4. Cấu hình thông tin API Keys (Credentials) của bạn (Google, Claude/Anthropic, Telegram, Notion) theo hướng dẫn chi tiết tại các bài viết hướng dẫn trên website của chúng tôi.

---

## 📝 Giấy Phép (License)
Dự án được phân phối dưới giấy phép MIT License. Bạn hoàn toàn có thể sử dụng, chỉnh sửa và triển khai thương mại trong doanh nghiệp của mình. 

Bản quyền sở hữu trí tuệ và quyền tác giả thuộc về **[Nguyễn Thanh Tùng](https://toilatung.com)** (AI System Designer & Founder TVT Agency).
