# StudyBuddy Studio — Web Edition

Phiên bản web thuần (HTML/CSS/JS) chuyển thể từ ứng dụng Desktop CustomTkinter `studybuddy_studio_ng_d_ng_customtkinter.py`.

## Tính năng giữ nguyên & nâng cấp
- **6 chế độ gia sư chuyên biệt** (gồm cả chế độ **Gia sư gợi mở** khóa cứng chống chép bài hộ).
- **Streaming SSE trực tiếp** qua Gemini 2.5 Flash / Flash-Lite (`thinkingBudget: 0`), tự động fallback model và hỗ trợ cả key Google AI Studio (`AIzaSy...`) lẫn Vertex AI Express (`AQ...`).
- **Phát âm bản xứ 1.0x & 0.75x** bằng Web Speech API tích hợp sẵn trong trình duyệt.
- **Lịch sử buổi học & Flashcard Studio** tự động lưu bền vững vào `localStorage` của trình duyệt (không mất thẻ khi tải lại trang).
- **Hai giao diện Sáng / Tối** (Midnight Studio & Nordic Crisp).

## Cách chạy & Lấy link nộp bài
1. **Chạy trực tiếp trên máy:** Mở file `index.html` bằng trình duyệt (Chrome/Edge), hoặc chạy `python -m http.server 8080` trong thư mục này rồi mở `http://localhost:8080`.
2. **Đưa lên mạng để lấy link nộp Phase 3 (miễn phí):** Kéo thả thư mục `StudyBuddy-Web` lên [Netlify Drop](https://app.netlify.com/drop) hoặc đẩy lên GitHub Pages để nhận URL `https://...` và dán vào 3 vị trí trong file PowerPoint thuyết trình.
