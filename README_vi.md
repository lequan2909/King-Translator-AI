# King Translator AI - Công Cụ Dịch Thuật AI Đa Năng

![Version](https://img.shields.io/badge/version-4.4-blue)
![Status](https://img.shields.io/badge/status-updated-green)
![License](https://img.shields.io/badge/license-GPL3-orange)

<div align="center">
  <img src="kings.jpg" alt="Logo Translator AI" width="200"/>
  <br>
  <i>Công cụ dịch thuật tích hợp AI thông minh (Google Gemini) cho trình duyệt</i>
  <h3>Nếu bạn thích userscript này, hãy cho kho lưu trữ này một sao!✨</h3>
</div>

## 📖 Mục Lục
- [Giới thiệu](#-giới-thiệu)
- [Ảnh chụp màn hình](#-ảnh-chụp-màn-hình)
- [Tính năng](#-tính-năng)
- [Hướng dẫn cài đặt](#-hướng-dẫn-cài-đặt)
- [Hướng dẫn sử dụng](#-hướng-dẫn-sử-dụng)
- [Cấu hình](#-cấu-hình)
- [Phím tắt](#-phím-tắt)
- [Ghi chú](#-ghi-chú)
- [Đóng góp](#-đóng-góp)
- [Giấy phép](#-giấy-phép)
- [Tải xuống](#-tải-xuống)
- [English Guide](README.md)

## 🌟 Giới thiệu
- Translator AI là một userscript dịch thuật tích hợp AI sáng tạo, cho phép người dùng dễ dàng dịch văn bản, hình ảnh, phương tiện và các trang web trực tiếp trong trình duyệt của họ. Nó sử dụng API Google Gemini để mang lại kết quả dịch chất lượng cao.

## 📸 Ảnh chụp màn hình

### 📱 Di động
<details>
<summary>Nhấn để xem</summary>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="https://i.imgur.com/7pi9USr.jpeg" width="45%" />
  <img src="https://i.imgur.com/3ksRC8R.jpeg" width="45%" />
  <img src="https://i.imgur.com/Wu5jXLv.jpeg" width="45%" />
  <img src="https://i.imgur.com/Bcy8QIu.jpeg" width="45%" />
  <img src="https://i.imgur.com/AcXGewv.jpeg" width="45%" />
  <img src="https://i.imgur.com/KQtCnnk.jpeg" width="45%" />
  <img src="https://i.imgur.com/vmA7OW7.jpeg" width="45%" />
  <img src="https://i.imgur.com/lWDs7Iu.jpeg" width="45%" />
</div>

</details>

### 💻 PC
<details>
<summary>Nhấn để xem</summary>

<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
  <img src="https://i.imgur.com/tZ5NqOG.jpeg" width="45%" />
  <img src="https://i.imgur.com/esxZv9N.jpeg" width="45%" />
  <img src="https://i.imgur.com/4tTFvZW.jpeg" width="45%" />
  <img src="https://i.imgur.com/gIExWnd.jpeg" width="45%" />
  <img src="https://i.imgur.com/X7CG6kk.png" width="45%" />
  <img src="https://i.imgur.com/y0Ym8iX.jpeg" width="45%" />
  <img src="https://i.imgur.com/QcwfvAH.jpeg" width="45%" />
  <img src="https://i.imgur.com/QvUpwfR.jpeg" width="45%" />
</div>

</details>

## ✨ Tính năng

### 📝 Dịch văn bản
- Dịch nhanh khi văn bản được đánh dấu
- Dịch pop-up với giao diện hấp dẫn
- Dịch nâng cao với phân tích từ vựng
- Dịch tự động trong các trường nhập liệu

### 🖼️ Dịch hình ảnh (OCR)
- Dịch các tệp hình ảnh từ máy tính của bạn
- Chụp và dịch ảnh chụp màn hình
- Dịch hình ảnh trên web
- Dịch manga với văn bản phủ lên

### 🎵 Dịch phương tiện
- Hỗ trợ các tệp âm thanh (MP3, WAV, OGG,...)
- Hỗ trợ các tệp video (MP4, WEBM,...)
- Tự động tạo phụ đề SRT

### 🌐 Dịch trang web
- Dịch toàn bộ trang web
- Tự động phát hiện ngôn ngữ
- Dịch các tệp HTML và PDF
- Loại trừ các phần tử cụ thể như tùy chọn

## 🔧 Hướng dẫn cài đặt chi tiết

### Bước 1: Cài đặt tiện ích quản lý script
- **Firefox (Khuyến nghị):**
  - Cài đặt Violentmonkey (Mã nguồn mở, khuyến nghị) hoặc Tampermonkey
  - Mở tiện ích bổ sung của Firefox và nhấn "Thêm vào Firefox"

- **Chrome:**
  - Cài đặt Violentmonkey hoặc Tampermonkey từ Cửa hàng Chrome
  - Nhấn "Thêm vào Chrome"

### Bước 2: Lấy khóa API Gemini
1. Truy cập [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Đăng nhập bằng Google
3. Nhấn "Tạo khóa API"
4. Sao chép khóa API

### Bước 3: Cài đặt script
1. Nhấn vào biểu tượng Violentmonkey
2. Đi đến Bảng điều khiển > Tiện ích
3. Dán liên kết script vào "Cài đặt từ URL" (liên kết script ở cuối tài liệu này)
4. Xác nhận cài đặt

### Bước 4: Cấu hình
1. Mở cài đặt (Alt + S hoặc chạm 4 ngón tay)
2. Chọn Gemini làm nhà cung cấp
3. Nhập khóa API
4. Lưu cài đặt

## 📚 Hướng dẫn sử dụng chi tiết

### Dịch văn bản
1. Đánh dấu văn bản cần dịch
2. Chọn loại dịch:
   - Nhấn đơn: Dịch nhanh
   - Nhấn đôi: Dịch pop-up
   - Nhấn giữ: Dịch nâng cao

### Dịch đầu vào
- 🌐 : Dịch sang ngôn ngữ đích
- 🔄 : Dịch sang ngôn ngữ nguồn
- Alt + T: Dịch nhanh

### Công cụ dịch
Nhấn vào "Công cụ dịch" ở góc dưới bên phải của màn hình:
- Dịch trang
- Dịch hình ảnh/OCR
- Dịch phương tiện
- Dịch tệp

## ⌨️ Phím tắt

| Phím tắt  | Chức năng           |
|-----------|---------------------|
| Alt + F   | Dịch trang          |
| Alt + Q   | Dịch nhanh          |
| Alt + E   | Dịch pop-up         |
| Alt + A   | Dịch nâng cao       |
| Alt + T   | Dịch đầu vào        |
| Alt + S   | Mở cài đặt          |

## 📱 Cảm ứng (Di động)

| Cử chỉ      | Chức năng           |
|-------------|---------------------|
| 2 ngón tay  | Dịch pop-up         |
| 3 ngón tay  | Dịch nâng cao       |
| 4 ngón tay  | Mở cài đặt          |
| 5 ngón tay  | Chuyển đổi công cụ  |

## ⚙️ Cấu hình

### Giao diện
- Chủ đề sáng/tối
- Kích thước phông chữ
- Vị trí của nút dịch

### API & Mô hình
- Nhà cung cấp: Gemini AI
- Khóa API
- Lựa chọn mô hình

### Tùy chỉnh
- Nhắc nhở dịch
- Phím tắt
- Bộ nhớ đệm
- Sao lưu/Khôi phục

## ❗ Ghi chú
- Cần có khóa API Gemini hợp lệ để truy cập dịch vụ dịch thuật
- Giới hạn 5 yêu cầu/10 giây
- Bộ nhớ đệm tăng tốc độ dịch
- Hỗ trợ dịch ngoại tuyến với bộ nhớ đệm
- Tự động phát hiện ngôn ngữ
- Hỗ trợ nhiều ngôn ngữ
- **Ghi chú sử dụng chi tiết:** https://voz.vn/t/script-dung-ai-%C4%91e-dich-moi-thu-text-anh-audio-video.1072947/#-huong-dan-su-dung

## 🤝 Đóng góp

Tất cả các đóng góp đều được hoan nghênh! Vui lòng:
1. Fork dự án
2. Tạo nhánh mới
3. Cam kết thay đổi
4. Đẩy lên nhánh
5. Tạo một Pull Request

## 📄 Giấy phép

Dự án này được phát hành dưới Giấy phép Công cộng GNU v3.0. Xem `LICENSE` để biết thêm chi tiết.

## Donate? Bạn muốn ủng hộ tôi bằng một tách cà phê?
  * Nếu bạn đánh giá cao userscript này, hãy xem xét hỗ trợ tôi bằng một khoản quyên góp!<br>
  * Vui lòng truy cập liên kết sau để biết thông tin quyên góp:<br>
    - Website: [https://kingsmanvn.pages.dev](https://kingsmanvn.pages.dev)
    - Patreon: [https://www.patreon.com/c/king1x32/membership?](https://www.patreon.com/c/king1x32/membership?)<br>

## 🔧 Tải xuống

1. Phiên bản bình thường: [Github](https://github.com/king1x32/UserScripts/raw/main/King_Translator_AI.user.js) hoặc [Greasyfork](https://greasyfork.org/vi/scripts/529348-king-translator-ai)

2. Phiên bản nén (nhẹ hơn, mượt mà hơn): [Github](https://raw.githubusercontent.com/king1x32/compiledUserscripts/release/release/King20Translator20AI.user.js)

---

<div align="center">
  Được thực hiện với ❤️ bởi King1x32
  <br>
  <a href="https://www.patreon.com/c/king1x32/membership?">Patreon</a> •
  <a href="https://discord.gg/8DTwr8QpsM">Discord</a> •
  <a href="https://t.me/king1x32">Telegram</a>
</div>
