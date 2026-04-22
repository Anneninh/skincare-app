# 📱 Hướng dẫn cài SkinCare App lên điện thoại

## Bước 1 — Tạo tài khoản GitHub (miễn phí)
1. Vào **github.com** → Click **Sign up**
2. Nhập email, tạo password, chọn username
3. Xác nhận email

---

## Bước 2 — Tạo Repository mới
1. Sau khi đăng nhập, click nút **"+"** góc trên phải → **New repository**
2. Đặt tên repository: `skincare-app` *(hoặc bất kỳ tên nào)*
3. Chọn **Public**
4. Tick vào **"Add a README file"**
5. Click **Create repository**

---

## Bước 3 — Upload các file
Trong repository vừa tạo:
1. Click **"Add file"** → **"Upload files"**
2. Upload các file sau (kéo thả cả thư mục hoặc chọn từng file):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - Thư mục `icons/` (chứa `icon-192.png` và `icon-512.png`)
3. Kéo xuống → Click **"Commit changes"**

---

## Bước 4 — Bật GitHub Pages
1. Trong repository, click tab **Settings** (góc trên)
2. Kéo xuống mục **"Pages"** ở thanh bên trái
3. Mục **Source**: chọn **"Deploy from a branch"**
4. Branch: chọn **main**, folder: **/ (root)**
5. Click **Save**
6. Đợi ~1-2 phút → GitHub sẽ hiển thị link dạng:
   `https://[username].github.io/skincare-app/`

---

## Bước 5 — Cài lên điện thoại

### Android (Chrome):
1. Mở link trên Chrome
2. Chờ app load xong
3. Nhấn menu **⋮** (3 chấm) góc trên phải
4. Chọn **"Add to Home screen"** hoặc **"Install app"**
5. Xác nhận → App xuất hiện trên màn hình chính ✅

### iPhone (Safari):
1. Mở link trên **Safari** (bắt buộc dùng Safari, không dùng Chrome)
2. Nhấn nút **chia sẻ** 📤 (ở thanh dưới)
3. Kéo xuống → chọn **"Add to Home Screen"**
4. Đặt tên → **Add** ✅

---

## ✅ Sau khi cài xong
- App mở **toàn màn hình** như app thật (không có thanh địa chỉ)
- **Dùng được offline** hoàn toàn
- Dữ liệu lưu trên điện thoại của bạn
- Icon xuất hiện trên màn hình chính

---

## ⚠️ Lưu ý
- GitHub Pages **miễn phí vĩnh viễn** cho repo Public
- Dữ liệu routine, ảnh, nhật ký lưu trong bộ nhớ điện thoại (không đồng bộ cloud)
- Nếu xóa app và cài lại, dữ liệu sẽ mất → export nhật ký thủ công nếu cần
