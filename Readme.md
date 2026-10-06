# Báo cáo Thực hành Bài 3: Cấu hình tường lửa UFW và chẩn đoán cổng mạng

## 1. Thiết lập chính sách mặc định của UFW

Thiết lập chính sách mặc định: chặn toàn bộ kết nối đi vào (deny incoming) và cho phép tất cả kết nối đi ra (allow outgoing):

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing