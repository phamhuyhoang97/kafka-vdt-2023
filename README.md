# VDT 2023 - Thực hành Kafka

> Required: Máy cần cài đặt sẵn Docker. Cấu hình máy cần RAM >= 8GB

## 1. Chuẩn bị trước
Chạy lệnh dưới đây để khởi chạy docker compose project 
```sh
cd ${thư mục clone về}
docker compose -f docker-compose.zk-kafka.yml -p vdt-kafka-zk up -d
docker compose -f docker-compose.zkless-kafka.yml -p vdt-kafka-kraft up -d
```
