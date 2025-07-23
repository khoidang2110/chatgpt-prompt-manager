# ✨ ChatGPT Prompt Manager

Một tiện ích nhỏ gọn chạy trên Tampermonkey, giúp bạn lưu trữ, quản lý và chèn các prompt yêu thích trực tiếp vào ChatGPT mà không cần nhập lại mỗi lần.

## 🚀 Tính năng

- 🧠 Lưu nhiều prompt với **tiêu đề** và **nội dung** đầy đủ
- 💬 Nút "Chèn Prompt" để nạp nội dung vào ChatGPT ngay
- ➕ Thêm, ✏️ sửa, 🗑️ xóa prompt dễ dàng
- 🔽 Dropdown menu nhỏ gọn, không ảnh hưởng trải nghiệm
- 📦 Lưu trữ toàn bộ prompt trong `localStorage` trên trình duyệt
- 🌗 Giao diện có thể mở rộng/thu gọn tiện lợi
- 🚫 Không chọn prompt nào mặc định — giúp bạn kiểm soát toàn bộ thao tác

## 📷 Giao diện

<img src="screenshot.png" alt="Prompt Manager UI" width="400"/>

## 🛠️ Cài đặt

1. Cài đặt [Tampermonkey](https://www.tampermonkey.net/) cho trình duyệt (Chrome, Edge, Firefox...)
2. Tạo script mới và dán mã từ file `chatgpt-prompt-manager.user.js`
3. Lưu lại, reload trang [ChatGPT](https://chat.openai.com/)

> ⚠️ Script này chỉ chạy tại: `https://chat.openai.com/*`

## 📝 Cách sử dụng

1. Click nút `☰` ở góc phải để mở Prompt Manager
2. Chọn một prompt từ danh sách — bạn sẽ thấy tiêu đề và nội dung hiển thị
3. Muốn thêm/sửa/xoá? Dùng các nút tương ứng:
   - ➕: Thêm prompt mới
   - ✏️: Sửa prompt đang chọn
   - 🗑️: Xóa prompt đang chọn

## 📁 Lưu ý

- Tất cả dữ liệu được lưu trong **localStorage**, không có gửi đi đâu cả
- Nếu muốn reset lại, mở DevTools > `Application` > `LocalStorage` > xoá key `chatgpt_prompts`

## 💡 Ý tưởng tương lai

- Đồng bộ qua GitHub Gist / Google Drive
- Giao diện đẹp hơn (Tailwind hoặc Dark mode)
- Gắn tag cho prompt (ví dụ: `#dev`, `#design`, `#faq`...)

## 👩‍💻 Được phát triển bởi John  
Vì mình dùng ChatGPT mỗi ngày và không muốn lặp lại prompt nữa.

---

