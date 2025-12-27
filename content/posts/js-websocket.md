Giao tiếp Realtime với WebSocket trong JavaScript
date: 2025-12-22


## 📌 Giới thiệu
WebSocket cho phép giao tiếp hai chiều realtime.

## 🧠 Nguyên lý
Kết nối được giữ liên tục giữa client và server.

## 💻 Ví dụ minh họa

const ws = new WebSocket("ws://localhost:8080");
ws.onmessage = e => console.log(e.data);
