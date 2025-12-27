Lập trình TCP Client – Server trong Java
date: 2025-12-22


## 📌 Giới thiệu
TCP là giao thức hướng kết nối, đảm bảo dữ liệu được truyền đầy đủ và đúng thứ tự giữa Client và Server.

## 🧠 Mô hình TCP
- Server mở cổng và chờ kết nối
- Client chủ động kết nối đến Server

## 💻 Ví dụ Server TCP

ServerSocket server = new ServerSocket(9000);
Socket client = server.accept();
