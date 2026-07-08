# Docker Compose

## docker-compose.yml

Là file mô tả toàn bộ các service của dự án.

---

## Service

Là một thành phần mà Docker sẽ quản lý.

Ví dụ:
- mysql
- redis
- springboot

---

## Image

Là bản cài (template) để tạo Container.

Ví dụ:

mysql:8.4

---

## Container

Là chương trình đang chạy được tạo từ Image.

---

## Ports

Cú pháp:

HOST_PORT:CONTAINER_PORT

Ví dụ:

3306:3306

Windows sẽ kết nối vào port 3306 của Container.

---

## Environment

Truyền các biến cấu hình vào Container khi khởi động.

Ví dụ:

MYSQL_ROOT_PASSWORD

---

## Volumes

Lưu dữ liệu bên ngoài Container.

Khi xóa Container thì dữ liệu vẫn còn.