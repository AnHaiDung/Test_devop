Họ và tên : An Hải Dũng
Lệnh dùng để chạy hệ thống :
Mở PowerShell tại thư mục be (nơi có compose.yml), rồi chạy:
docker compose up -d --build
Kiểm tra trạng thái các service:
docker compose ps
Kiểm tra backend:
curl.exe -i http://localhost:8080/actuator/health




