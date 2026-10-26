# OpenClaw 🦞 — Trợ lý AI cá nhân của bạn

OpenClaw là một trợ lý AI mã nguồn mở có thể chạy trên máy tính của bạn và kết nối với các ứng dụng nhắn tin quen thuộc như Telegram, WhatsApp, Discord, Slack và nhiều nền tảng khác. Dự án hướng đến việc giúp bạn tương tác với AI, sử dụng công cụ và tự động hóa một số công việc ngay trong môi trường của mình.

> Đây là bản giới thiệu bằng tiếng Việt của dự án OpenClaw. OpenClaw là dự án mã nguồn mở do cộng đồng phát triển; repository này dựa trên dự án gốc.

## ✨ Tính năng chính

- **Trợ lý AI cá nhân:** trò chuyện với trợ lý qua giao diện web hoặc các kênh nhắn tin được hỗ trợ.
- **Hỗ trợ nhiều nền tảng:** có các phương án sử dụng trên macOS, Windows, Linux và thiết bị di động theo hướng dẫn chính thức.
- **Kết nối mô hình AI:** hỗ trợ các nhà cung cấp mô hình được OpenClaw tích hợp, bao gồm một số mô hình chạy trên máy cá nhân.
- **Mở rộng bằng công cụ và tiện ích:** bổ sung khả năng thông qua tools, skills và plugins.
- **Tự quản lý:** cấu hình, thông tin phiên làm việc và thông tin xác thực được quản lý theo cách triển khai của bạn.

## 📚 Tài liệu chính thức

- [Trang chủ OpenClaw](https://openclaw.ai)
- [Tài liệu hướng dẫn](https://docs.openclaw.ai)
- [Bắt đầu sử dụng](https://docs.openclaw.ai/start/getting-started)
- [Hướng dẫn cài đặt](https://docs.openclaw.ai/install)
- [Câu hỏi thường gặp](https://docs.openclaw.ai/help/faq)
- [Cộng đồng Discord](https://discord.gg/clawd)

## 💻 Cài đặt trên Windows

Mở **PowerShell** và chạy lệnh cài đặt chính thức sau:

```powershell
iwr -useb https://openclaw.ai/install.ps1 | iex
```

Lệnh trên tải và chạy trình cài đặt từ trang chính thức của OpenClaw. Chỉ chạy khi bạn đã xem xét và tin tưởng nguồn lệnh. Làm theo các bước mà trình cài đặt hiển thị trên màn hình.

Nếu OpenClaw đã được cài đặt, hãy mở terminal và kiểm tra trạng thái:

```powershell
openclaw gateway status
```

Mở giao diện điều khiển bằng:

```powershell
openclaw dashboard
```

Nếu gặp lỗi, hãy xem [hướng dẫn cài đặt](https://docs.openclaw.ai/install) và [hướng dẫn bắt đầu](https://docs.openclaw.ai/start/getting-started). Các lệnh và yêu cầu hệ thống có thể thay đổi theo phiên bản.

## 🧩 OpenClaw hoạt động như thế nào?

- **Gateway:** thành phần điều phối phiên làm việc, công cụ và kết nối với các kênh.
- **Giao diện điều khiển:** nơi bạn trò chuyện và quản lý trợ lý.
- **Kênh nhắn tin:** kết nối trợ lý với các dịch vụ nhắn tin được hỗ trợ.
- **Mô hình AI:** xử lý yêu cầu và tạo câu trả lời.
- **Tools, Skills và Plugins:** mở rộng những việc trợ lý có thể thực hiện.

Tìm hiểu thêm trong tài liệu về [Gateway](https://docs.openclaw.ai/gateway), [các kênh](https://docs.openclaw.ai/channels), [mô hình AI](https://docs.openclaw.ai/concepts/model-providers) và [công cụ](https://docs.openclaw.ai/tools).

## 🔐 Lưu ý bảo mật

- Chỉ kết nối các tài khoản và kênh mà bạn tin tưởng.
- Không chia sẻ API key, mật khẩu, mã xác thực hoặc thông tin đăng nhập trong mã nguồn công khai.
- Cẩn thận với tin nhắn từ người lạ và yêu cầu thực thi lệnh.
- Công cụ có thể được cấp quyền truy cập vào máy tính tùy cấu hình. Hãy đọc [hướng dẫn bảo mật](https://docs.openclaw.ai/gateway/security) trước khi mở quyền truy cập cho người khác hoặc kết nối Gateway ra Internet.
- Kiểm tra kỹ các lệnh trước khi chạy, đặc biệt là lệnh tải và thực thi nội dung từ Internet.

## 🛠️ Phát triển dự án

OpenClaw sử dụng workspace dựa trên **pnpm**. Không nên dùng `npm install` ở thư mục gốc của repository.

Các lệnh phát triển cơ bản:

```bash
pnpm install
pnpm build
pnpm ui:build
```

Để thiết lập môi trường phát triển đầy đủ, hãy xem [hướng dẫn thiết lập mã nguồn](https://docs.openclaw.ai/start/setup) và [hướng dẫn đóng góp](CONTRIBUTING.md).

## 🤝 Đóng góp

OpenClaw được phát triển công khai với sự tham gia của cộng đồng. Bạn có thể báo lỗi, đề xuất tính năng hoặc đóng góp mã nguồn thông qua [GitHub Issues](https://github.com/openclaw/openclaw/issues).

Vui lòng đọc [CONTRIBUTING.md](CONTRIBUTING.md) trước khi gửi đóng góp. Nếu phát hiện lỗ hổng bảo mật, hãy làm theo hướng dẫn trong [SECURITY.md](SECURITY.md).

## 📄 Giấy phép

Dự án OpenClaw sử dụng giấy phép [MIT](LICENSE). Xem thêm [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) để biết thông tin về mã nguồn bên thứ ba.

---

Dự án gốc: [openclaw/openclaw](https://github.com/openclaw/openclaw)  
Trang web: [openclaw.ai](https://openclaw.ai)
