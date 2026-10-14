# Bài kiểm tra — Đóng gói và chạy Campus Hub với Docker

## Thông tin sinh viên
* Họ tên: Hà Quang Huy
* Mã sinh viên: B24DTCN112

## Lệnh dùng để chạy hệ thống
docker compose up -d

## Cổng kiểm tra
* URL: http://localhost:8080/actuator/health

## Minh chứng kết quả
1. Docker Image đã build thành công (docker images)
2. Trạng thái service (docker compose ps)
3. Kết quả health check (/actuator/health trả về status UP)
