# Session 05 - Bài 1: API Gateway và định tuyến tĩnh

Project `api-gateway` chạy ở cổng `8080` và chuyển tiếp mọi request
`/api/v1/customers/**` tới `customer-service` tại `http://localhost:8081`.

## Chạy và kiểm tra

1. Chạy `customer-service` ở cổng `8081`.
2. Chạy Gateway:

   ```bash
   cd api-gateway
   gradle bootRun
   ```

3. Gọi thử:

   ```bash
   curl http://localhost:8080/api/v1/customers/1
   ```

