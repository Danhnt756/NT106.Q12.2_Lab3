# NT106.Q12.2 – Lab 3: Working with Sockets in C#

## Thành viên nhóm
| MSSV | Họ và Tên |
|------|------------|
| 22521251 | Nguyễn Duy Thế Sơn |
| 24520262 | Nguyễn Tấn Danh |

---

**Lab 3 – Working with Sockets in C#** là bài thực hành thuộc học phần *Lập trình mạng căn bản (NT106)* tại UIT.  
Mục tiêu của bài lab là giúp sinh viên hiểu và triển khai được cơ chế giao tiếp giữa các tiến trình thông qua **socket** với hai giao thức chính là **UDP** và **TCP**.

### Các bài trong Lab gồm có

| Bài | Nội dung chính |
|-----|----------------|
| Bài 1 | Gửi và nhận dữ liệu sử dụng UDP Client – UDP Server |
| Bài 2 | Lắng nghe dữ liệu từ dịch vụ Telnet qua TCP Socket |
| Bài 3 | Giao tiếp 1 Server – 1 Client sử dụng TCP Listener / TCP Client |
| Bài 4 | Mô hình 1 Server – Nhiều Client (ứng dụng quản lý phòng vé) |
| Bài 5 | 1 Server – Multi Client (ứng dụng “Hôm nay ăn gì?” tích hợp SQLite) |
| Bài 6 | Ứng dụng Chat Room đa người dùng qua TCP (gửi tin nhắn và file) |

---

## Yêu cầu kỹ thuật
- Ngôn ngữ lập trình: **C# (.NET 8.0 / WinForms)**
- IDE: **Visual Studio 2022**

---

## Kiến thức áp dụng
- Tạo và quản lý socket kết nối giữa client và server  
- Lập trình đa luồng (Multithreading) để xử lý song song  
- Truyền dữ liệu chuỗi và file giữa client và server  
- Thiết kế giao diện với **Windows Forms**  
- Tích hợp **SQLite** làm cơ sở dữ liệu cục bộ

---

## Hướng dẫn chạy project

1. Clone repository  
   ```bash
   git clone https://github.com/Danhnt756/NT106.Q12.2_Lab3.git
