Lập trình Socket cơ bản trong Java
date: 2025-12-22


## 📌 Giới thiệu
Lập trình socket là nền tảng của lập trình mạng, cho phép các chương trình giao tiếp với nhau qua mạng.

## 🧩 Socket trong Java
Java cung cấp hai lớp quan trọng:
- `ServerSocket`
- `Socket`

## 🔧 Ví dụ Server

ServerSocket server = new ServerSocket(8080);
Socket client = server.accept();
