Lập trình mạng với Node.js
date: 2025-12-22


## 📌 Giới thiệu
Node.js cho phép JavaScript chạy phía server.

## 🧠 Kiến thức chính
Node.js hỗ trợ TCP/HTTP thông qua module net và http.

## 💻 Ví dụ minh họa

const http = require("http");
http.createServer((req, res) => {
  res.end("Hello Node.js");
}).listen(3000);
