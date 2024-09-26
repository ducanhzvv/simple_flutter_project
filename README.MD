## Các bước thực hiện
### B1: Khởi tạo dự án
1. Tạo thư mục `simple_flutter_project`
2. Tạo thư mục `backend` và `frontend` trong thư mục `simple_flutter_project`
### B2: tạo ứng dụng server cho backend với dart framework
1. Đi đến thư mục backend
    ```bash
    cd backend
    ```
2. Khởi tạo dự án dart mới cho server 
    ```bash
    dart create -t server-shelf . --force
    ```
3. Khởi tạo dự án flutter trong thư mục frontend
    ```bash
    flutter create -e .
    ```
4. Thêm thư viện `http` vào dự án frontend
    ```bash
    flutter pub add http
    ```
