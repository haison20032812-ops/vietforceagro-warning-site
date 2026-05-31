# GitHub Pages deploy package

Trang chính nằm trong file `index.html`.

## Cách đưa lên GitHub Pages

1. Vào GitHub và tạo repository public, ví dụ `warning-site`.
2. Upload file `index.html` trong thư mục này lên repository.
3. Vào `Settings > Pages`.
4. Chọn `Deploy from a branch`.
5. Branch: `main`, folder: `/root`, rồi bấm `Save`.
6. Chờ GitHub tạo link dạng `https://USERNAME.github.io/warning-site/`.

## Gắn tên miền đã mua ở Tenten

Tên miền đang dùng: `vietforceagro.com`

Trong GitHub repository:

1. Vào `Settings > Pages`.
2. Nhập tên miền vào `Custom domain`.
3. Bấm `Save`.
4. Bật `Enforce HTTPS` sau khi DNS đã nhận.

Trong DNS của Tenten:

- Nếu dùng tên miền gốc `vietforceagro.com`, tạo 4 bản ghi `A` cho host `@`:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- Nếu dùng `www.vietforceagro.com`, tạo bản ghi `CNAME`:
  - Host: `www`
  - Value: `USERNAME.github.io`

DNS có thể cần vài phút đến 24 giờ để cập nhật.
