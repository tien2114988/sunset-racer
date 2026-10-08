# 🏁 Đua Xe 3D — Sunset Racer

Game đua xe 3D chạy ngay trên trình duyệt (WebGL / Three.js), chơi được trên **máy tính và điện thoại**.

## 🎮 Chơi ngay

**https://tien2114988.github.io/sunset-racer/**

Hoặc mở `index.html` trực tiếp trong trình duyệt (cần internet để tải Three.js từ CDN).

## 🕹️ Điều khiển

| Thao tác | Máy tính | Điện thoại |
|---|---|---|
| Lái xe | `←` `→` hoặc `A` `D` (kéo chuột cũng được) | Vuốt ngón sang trái/phải, hoặc bấm 2 nút ◀ ▶ |
| Tăng tốc | `↑` / `W` | Xe tự tăng tốc |
| Phanh | `↓` / `S` | — |
| Tắt/bật tiếng | `M` | — |
| Chơi lại | `R` / `Enter` | Bấm **Chơi lại** |

## ✨ Tính năng

- Bầu trời hoàng hôn chuyển sắc, mặt trời lặn, sương mù, bóng đổ, đèn đường & cây cối cuộn vô tận
- Xe giao thông (sedan + xe tải) spawn theo độ khó, tránh làn, nhặt xu, thưởng điểm "SUẤT!" khi vượt xe sát ván
- Tốc độ tối đa 95 đơn vị/giây (~340 km/h), FOV giãn ra khi tăng tốc
- Hiệu ứng rung camera khi va chạm, tiếng động cơ theo vòng tua, tiếng nhặt xu / nổ
- Kỷ lục lưu vào `localStorage`

## 📱 Tối ưu điện thoại

- Điều khiển cảm ứng: vuốt lái + nút bấm, tự tăng tốc
- Giữ khung hình mượt: giới hạn độ phân giải theo thiết bị, **tự hạ pixel ratio** nếu fps < 42
- Bóng đổ 512px, giảm số cây/ bụi/ cột đèn trên mobile
- Hỗ trợ tai thỏ (`safe-area`), chặn zoom double-tap & highlight màu, gợi ý xoay ngang
- Giao diện HUD co giãn theo kích thước màn hình

## 🛠️ Chạy local

```bash
python3 -m http.server 8765
# mở http://localhost:8765/
```

## 📦 Deploy

Trang tĩnh GitHub Pages từ nhánh `main` — chỉ cần commit là cập nhật.
