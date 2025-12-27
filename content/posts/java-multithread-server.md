Xây dựng Server đa luồng trong Java
date: 2025-12-22


## 📌 Giới thiệu
Server đa luồng giúp xử lý nhiều client cùng lúc.

## 🧠 Nguyên lý
Mỗi client được xử lý trong một Thread riêng biệt.

## 💻 Ví dụ minh họa

new Thread(() -> {
    // xử lý client
}).start();
