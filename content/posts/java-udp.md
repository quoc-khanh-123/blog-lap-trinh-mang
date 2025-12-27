Lập trình UDP trong Java
date: 2025-12-22


## 📌 Giới thiệu
UDP là giao thức không kết nối, truyền dữ liệu nhanh nhưng không đảm bảo độ tin cậy.

## 🧠 Kiến thức chính
UDP sử dụng DatagramSocket và DatagramPacket để gửi/nhận dữ liệu.

## 💻 Ví dụ minh họa

DatagramSocket socket = new DatagramSocket();
byte[] data = "Hello UDP".getBytes();
