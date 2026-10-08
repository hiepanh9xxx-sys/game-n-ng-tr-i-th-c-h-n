# Nông Trại Ngọc Ánh

Game nông trại 2D vẽ tay, góc nhìn isometric, Chương 1 "Trở về Thác Hàn". Bạn điều khiển Ánh; Hiệp, Cốm và Bánh tự làm việc, nói chuyện và trêu nhau. Chơi bằng cảm ứng trên điện thoại hoặc bằng chuột, bàn phím trên máy tính.

## Đưa game lên GitHub Pages (không cần cài gì)

1. Đăng nhập [github.com](https://github.com), bấm **New repository**. Đặt tên, ví dụ `nong-trai-ngoc-anh`. Chọn **Public**, bấm **Create repository**.
2. Trong repo mới, bấm **uploading an existing file**. Kéo thả **toàn bộ file trong thư mục này** vào: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `.nojekyll`, `README.md`. Bấm **Commit changes**.
   - File `.nojekyll` bị ẩn trên một số máy. Thiếu file này game vẫn chạy.
3. Vào **Settings → Pages**. Ở mục **Build and deployment**, chọn **Source: Deploy from a branch**, **Branch: main**, thư mục **/(root)**, bấm **Save**.
4. Đợi 1–2 phút, tải lại trang Settings → Pages. Địa chỉ game hiện ở đầu trang, dạng `https://<tên-tài-khoản>.github.io/nong-trai-ngoc-anh/`.

### Nếu dùng git

```bash
git init
git add .
git commit -m "Nông Trại Ngọc Ánh – Chương 1"
git branch -M main
git remote add origin https://github.com/<tên-tài-khoản>/nong-trai-ngoc-anh.git
git push -u origin main
```

Sau đó bật Pages như bước 3.

## Chơi trên điện thoại

- Mở địa chỉ GitHub Pages bằng **Safari** (iPhone) hoặc **Chrome** (Android).
- **Thêm vào màn hình chính** để chơi toàn màn hình như một app:
  - iPhone: nút Chia sẻ → **Thêm vào MH chính**.
  - Android: menu ⋮ → **Thêm vào màn hình chính** (hoặc **Cài đặt ứng dụng**).
- Sau lần mở đầu tiên, game chơi được cả khi không có mạng.

## Cách chơi

| Thao tác | Kết quả |
| --- | --- |
| Chạm vào cỏ, đá, ruộng, chuồng gà, thùng gỗ | Ánh tự đi tới và làm, công cụ tự chọn |
| Chạm vào chỗ đất trống | Ánh đi tới đó |
| Chạm vào Hiệp, Cốm, Bánh (trên bản đồ hoặc ở góc phải) | Ánh đến nói chuyện, kể chuyện |
| Chạm vào ngôi nhà | Vào nhà. Trong nhà chạm giường để ngủ, chạm bếp để nấu |
| Nút Menu | Lưu game, sao lưu mã, cách chơi |
| Chụm / mở hai ngón tay, hoặc nút + và − | Thu nhỏ, phóng to bản đồ |
| Kéo một ngón tay | Nhìn quanh nông trại; nút ◎ đưa camera về chỗ Ánh |

Trên máy tính: WASD hoặc phím mũi tên để đi, E hoặc Space để làm việc và nói chuyện, cuộn chuột hoặc phím + và − để zoom, Esc mở Menu.

## Lưu game

- 3 ô lưu ở màn hình chính, tự lưu mỗi sáng khi thức dậy và khi đóng trang.
- Bản lưu nằm trong trình duyệt của từng máy. Muốn chuyển sang máy khác: Menu → **Sao lưu mã**, chép đoạn mã, rồi trên máy mới chọn **Nhập mã lưu**.
- Bản lưu trên GitHub Pages và bản trên claude.ai là riêng biệt. Dùng Sao lưu mã để chuyển qua lại.

## Cập nhật game

Thay file `index.html` trong repo bằng bản mới (Add file → Upload files), commit. Trang tự cập nhật sau 1–2 phút; trên điện thoại có thể cần mở lại app một lần.
