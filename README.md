# Rò rỉ dữ liệu cá nhân trong hệ sinh thái IoT

- **Đề tài:** Đề tài 32 — Rò rỉ dữ liệu cá nhân trong hệ sinh thái IoT
- **Hình thức:** Cá nhân
- **Tác giả:** Phạm Hoàng Khiêm
- **Mã sinh viên:** 231A010548
- **Học phần:** Bảo mật trong IoT (INT4410)

## Giới thiệu

Đề tài nghiên cứu luồng dữ liệu cá nhân trong hệ sinh thái Smart Home theo chuẩn Matter, từ thiết bị, hub, ứng dụng đến dịch vụ đám mây và bên thứ ba. Mục tiêu là nhận diện nguy cơ rò rỉ, đánh giá rủi ro và đề xuất kiểm soát quyền riêng tư dựa trên OWASP IoT Security Verification Standard cùng quy định bảo vệ dữ liệu cá nhân.

## Cấu trúc thư mục

| Thư mục       | Nội dung                                                                                        |
| --------------- | ------------------------------------------------------------------------------------------------ |
| `report/`     | Báo cáo tiểu luận ở định dạng DOCX hoặc PDF.                                            |
| `slides/`     | Slide trình bày ở định dạng PPTX hoặc PDF.                                                |
| `src/`        | Code demo và file nguồn liên quan.                                                            |
| `configs/`    | File cấu hình như`mosquitto.conf`, `aclfile`, `flow.json`, `manifest.json`.           |
| `data/`       | Dữ liệu giả lập hoặc dữ liệu mẫu như`dataset_gia_lap.csv`, `payload_mau.json`.      |
| `results/`    | Kết quả thực nghiệm như ảnh trong`screenshots/`, log trong `logs/` và `output.csv`. |
| `references/` | Danh sách nguồn tham khảo trong`link_nguon.md`.                                             |

## Clone và sử dụng

```bash
git clone https://github.com/khiem128/INT4410-Detai32-RoRiDuLieuCaNhanTrongHeSinhThaiIOT.git
cd INT4410-Detai32-RoRiDuLieuCaNhanTrongHeSinhThaiIOT
```

Mở `report/Bao_cao_tieu_luan.docx` để đọc báo cáo. Xem `references/link_nguon.md` để tra cứu nguồn; sản phẩm bổ sung được đặt đúng thư mục theo bảng trên.
