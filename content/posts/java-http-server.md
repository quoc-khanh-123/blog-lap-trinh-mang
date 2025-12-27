Tạo HTTP Server đơn giản bằng Java
date: 2025-12-22


## 📌 Giới thiệu
Java có thể xây dựng HTTP Server mà không cần framework phức tạp.

## 🧠 Kiến thức chính
Sử dụng HttpServer trong package com.sun.net.httpserver.

## 💻 Ví dụ minh họa

HttpServer server = HttpServer.create(new InetSocketAddress(8080), 0);
