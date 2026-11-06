# Portfolio CV - Bùi Tiến Đạt

## Thông tin sản phẩm

- **Tác giả:** Bùi Tiến Đạt
- **Mô tả:** Portfolio cá nhân giới thiệu thông tin, kỹ năng, dự án, quá trình học tập và form liên hệ; được xây dựng bằng HTML và CSS tĩnh.
- **Repository:** [conbocuoi123/K20_Portfolio_CNTT20-04](https://github.com/conbocuoi123/K20_Portfolio_CNTT20-04)
- **Website:** [GitHub Pages](https://conbocuoi123.github.io/K20_Portfolio_CNTT20-04/)
- **Hồ sơ tác giả:** [github.com/conbocuoi123](https://github.com/conbocuoi123)

## Cấu trúc thư mục

```text
.
├── index.html          # Trang portfolio chính
├── ket-qua.html        # Trang kết quả của form liên hệ
├── css/
│   └── style.css       # Giao diện và responsive
├── assets/
│   ├── avatar.jpg      # Ảnh đại diện
│   ├── du-an-1.svg     # Minh họa dự án C++
│   ├── du-an-2.svg     # Minh họa portfolio
│   └── du-an-3.svg     # Minh họa website thực hành
├── AI_LOG.md           # Ghi nhận việc sử dụng AI
├── README.md
└── RELEASE_NOTES.md    # Ghi chú bàn giao v7
```

## Chạy trên máy cá nhân

Không cần cài thư viện hay build. Từ thư mục gốc của repository, mở `index.html` trực tiếp hoặc chạy máy chủ tĩnh:

```bash
python -m http.server 8000
```

Sau đó mở <http://localhost:8000/>. Trang tải font Inter từ Google Fonts nên cần Internet để hiển thị font này; các trang và ảnh còn lại là tệp tĩnh trong repository.

## Xuất bản

Website được cung cấp qua GitHub Pages tại URL ở trên. Mã nguồn hiện nằm ở nhánh `main`, với các trang HTML ở thư mục gốc và không có bước build. Để xác nhận chính xác cấu hình nguồn xuất bản, xem **Settings → Pages** của repository; cấu trúc mã nguồn tự nó không xác nhận cấu hình Pages.

## Kiểm tra các trang và chức năng

1. Mở `index.html` hoặc URL Pages; kiểm tra CSS, ảnh đại diện và ba ảnh dự án tải được.
2. Dùng menu để tới các mục Giới thiệu, Kỹ năng, Dự án, Học tập và Liên hệ; thử nút “Xem dự án”.
3. Ở form liên hệ, thử gửi thiếu trường, email sai định dạng, họ tên ngắn hơn 2 ký tự hoặc lời nhắn ngoài giới hạn 10–500 ký tự để kiểm tra xác thực HTML5.
4. Nhập dữ liệu thử hợp lệ để mở `ket-qua.html`; kiểm tra nút quay lại. Form dùng GET, không gửi email và không lưu dữ liệu; dữ liệu có thể xuất hiện trên URL, vì vậy không nhập thông tin nhạy cảm.
5. Thử ở chiều rộng màn hình máy tính và điện thoại. Nếu kiểm tra trên Pages, mở DevTools → Network và xác nhận các request CSS/ảnh trả về thành công.

## Hồ sơ và minh chứng

- **Hồ sơ:** [GitHub của tác giả](https://github.com/conbocuoi123)
- **Sản phẩm đã xuất bản:** [Portfolio trên GitHub Pages](https://conbocuoi123.github.io/K20_Portfolio_CNTT20-04/)
- **Mã nguồn:** [Trang chính](https://github.com/conbocuoi123/K20_Portfolio_CNTT20-04/blob/main/index.html), [trang kết quả](https://github.com/conbocuoi123/K20_Portfolio_CNTT20-04/blob/main/ket-qua.html), [CSS](https://github.com/conbocuoi123/K20_Portfolio_CNTT20-04/tree/main/css) và [assets](https://github.com/conbocuoi123/K20_Portfolio_CNTT20-04/tree/main/assets)
- **Commit mã nguồn sửa lỗi:** [50e9d34](https://github.com/conbocuoi123/K20_Portfolio_CNTT20-04/commit/50e9d34ee774c299cb96f7865a282a5ac89258f8)
- **Nhật ký AI:** [AI_LOG.md](./AI_LOG.md)
- **Ghi chú bàn giao:** [RELEASE_NOTES.md](./RELEASE_NOTES.md)

Repository hiện không có ảnh chụp màn hình minh chứng riêng; các liên kết trên dẫn tới sản phẩm đang công bố và mã nguồn tương ứng.
