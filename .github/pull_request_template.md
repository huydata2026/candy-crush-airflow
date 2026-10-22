## Mục đích
<!-- PR này giải quyết yêu cầu nào? Ai cần? Ví dụ: "LiveOps cần bảng riêng cho event booster_use" -->

## Thay đổi
<!-- Liệt kê file / DAG đã sửa -->
-

## Ảnh hưởng dữ liệu
- [ ] Có tạo bảng mới / đổi cột của bảng đang dùng? Bảng nào:
- [ ] Cần chạy lại (backfill) dữ liệu cũ? Từ ngày nào:
- [ ] Dashboard / bảng phía sau bị ảnh hưởng:
- [ ] Đổi `requirements.txt` / `Dockerfile` / `docker-compose.yaml` (deploy sẽ build lại image, Airflow khởi động lại)

## Đã kiểm tra
- [ ] `ruff check .` và `ruff format --check .` sạch
- [ ] `pytest tests/unit` xanh trên máy
- [ ] Đã chạy thử DAG với 1 ngày cụ thể (nếu đổi logic DAG)

## Người review cần xem kỹ
<!-- Chỗ nào bạn chưa chắc? -->
