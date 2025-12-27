Sử dụng Fetch API trong JavaScript
date: 2025-12-22


## 📌 Giới thiệu
Fetch API dùng để gửi HTTP request từ trình duyệt.

## 🧠 Kiến thức chính
Fetch trả về Promise và hỗ trợ async/await.

## 💻 Ví dụ minh họa

fetch("/api/data")
  .then(res => res.json())
  .then(data => console.log(data));
