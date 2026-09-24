# AI ĐỂU — Local Brain

Bản GitHub-only không dùng Gemini API key. Model chạy ngay trong trình duyệt bằng WebLLM/WebGPU.

## Dùng
1. Upload `index.html` lên GitHub.
2. Bật GitHub Pages.
3. Mở website bằng Chrome/Edge mới.
4. Bấm **Tải AI**. Lần đầu trình duyệt phải tải model về máy.
5. Dữ liệu học/memory lưu trong `localStorage` của trình duyệt.

## Có gì
- Chat local, không API key.
- Chọn model nhẹ/mạnh hơn.
- Dạy AI và lưu memory.
- Tự test kiến thức.
- Chế độ tự test mỗi 5 phút khi trang đang mở.
- Sinh mẫu project web.
- Xuất memory JSON.

## Giới hạn thật
- Đây không phải server 24/7. Tab phải mở để model chạy và tự test.
- Đây là self-learning bằng memory + self-test; nó không tự huấn luyện lại toàn bộ trọng số LLM.
- Mỗi máy/người dùng có memory riêng vì GitHub Pages không có database dùng chung.

WebLLM chạy LLM trực tiếp trong trình duyệt bằng WebGPU và có các model prebuilt. Model list của WebLLM gồm SmolLM2, Llama 3.2 và nhiều model khác.
