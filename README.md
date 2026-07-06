# Nova AI – Trợ lý AI tìm kiếm thông minh

Trợ lý AI tìm kiếm thông tin thời gian thực, tổng hợp câu trả lời kèm **trích dẫn nguồn** để xác minh tính đúng sai — giao diện như ChatGPT/Gemini.

**🔗 Demo:** [Xem tại đây](https://konheodat01.github.io/nova-ai)

---

## Tính năng

- 🔍 **Tìm kiếm web thời gian thực** qua Google Search Grounding
- 📎 **Trích dẫn nguồn** cho từng câu trả lời (click để kiểm tra)
- 💬 **Giao diện chat** như ChatGPT/Gemini với Dark Mode
- 🧠 **Nhớ ngữ cảnh** hội thoại nhiều lượt
- 📝 **Markdown Rendering** đẹp (bảng, code block, heading...)
- 📱 **Responsive** — dùng được trên điện thoại
- 🔑 **API Key lưu local** — không gửi đi đâu ngoài Google

---

## Cài đặt & Sử dụng

### Bước 1: Lấy Gemini API Key miễn phí
1. Truy cập [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Đăng nhập bằng tài khoản Google
3. Nhấn **"Create API key"** → Copy key

**Hạn mức miễn phí:** 1.500 requests/ngày — đủ dùng cá nhân.

### Bước 2: Mở app và nhập API Key
Dán key vào ô hiện ra khi mở app lần đầu. Key được lưu vào `localStorage` của trình duyệt, không bao giờ rời khỏi máy bạn.

---

## Tech Stack

- **Frontend:** HTML5 + CSS3 + Vanilla JS (không framework, không backend)
- **AI Model:** Google Gemini 2.0 Flash (nhanh, miễn phí)
- **Search:** Google Search Grounding API
- **Deploy:** GitHub Pages (static hosting)
