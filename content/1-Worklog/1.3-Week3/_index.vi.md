---
title: "Nhật ký Tuần 3"
date: "2025-09-22"
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu Tuần 3:

* Thiết lập AWS Transit Gateway
* Tạo Transit Gateway Attachments và Route Tables
* Học các khái niệm và dịch vụ Amazon EC2 toàn diện
* Nghiên cứu EC2 Auto Scaling, EFS/FSx, Lightsail, và MGN

### Nhiệm vụ thực hiện trong tuần:
| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1   | - Giới thiệu AWS Transit Gateway <br>&emsp;+ Hiểu về các khái niệm Transit Gateway <br>&emsp;+ So sánh VPC Peering vs Transit Gateway <br>&emsp;+ Lợi ích và trường hợp sử dụng Transit Gateway <br>&emsp;+ Xem xét kiến trúc lab và điều kiện tiên quyết | 22/09/2025 | 22/09/2025 | <https://000020.awsstudygroup.com/> |
| 2   | - Tạo Transit Gateway <br>&emsp;+ Cấu hình tham số Transit Gateway <br>&emsp;+ Thiết lập cài đặt Transit Gateway <br>&emsp;+ Xem xét cấu hình Transit Gateway | 23/09/2025 | 23/09/2025 | <https://000020.awsstudygroup.com/>|
| 3   | - Tạo Transit Gateway Attachments <br>&emsp;+ Kết nối VPC với Transit Gateway <br>&emsp;+ Cấu hình cài đặt attachment <br>&emsp;+ Xác minh trạng thái attachment | 24/09/2025 | 24/09/2025 | <https://000020.awsstudygroup.com/>|
| 4   | - Transit Gateway Route Tables & Kiểm tra <br>&emsp;+ Tạo Transit Gateway Route Tables <br>&emsp;+ Thêm Routes vào VPC Route Tables <br>&emsp;+ Kiểm tra kết nối giữa các VPC <br>&emsp;+ Dọn dẹp tài nguyên | 25/09/2025 | 25/09/2025 | <https://000020.awsstudygroup.com/>|
| 5   | - **Module 03-01:** Nghiên cứu toàn diện Amazon EC2 <br>&emsp;+ Các loại EC2 Instance <br>&emsp;+ AMI / Backup / Key Pair <br>&emsp;+ Elastic Block Store <br>&emsp;+ Instance Store <br>&emsp;+ User Data <br>&emsp;+ Meta Data <br>&emsp;+ EC2 Auto Scaling <br>&emsp;- EFS/FSx - Lightsail - MGN| 26/09/2025 | 26/09/2025 | |

### 🏆 **Thành tựu Tuần 3**

* **Hiểu rõ các khái niệm AWS Transit Gateway**
  * Học về sự khác biệt giữa Transit Gateway và VPC Peering
  * Hiểu về lợi ích của kiến trúc mạng có thể mở rộng
  * Xem xét kiến trúc lab với bốn VPC
  * Dọn dẹp đúng cách tài nguyên Transit Gateway

* **Cấu hình Transit Gateway Attachments**
  * Kết nối thành công nhiều VPC với Transit Gateway
  * Xác minh trạng thái attachment và kết nối
  * Thiết lập kết nối VPC-to-Transit Gateway

* **Các khái niệm toàn diện Amazon EC2 (Ngày 5)**
  * Học về các họ instance EC2 khác nhau, loại và kích thước
  * Hiểu về khái niệm AMI, chiến lược backup và quản lý Key Pair
  * Nghiên cứu các loại EBS volume, hiệu suất, snapshots và mã hóa
  * So sánh đặc điểm Instance Store và EBS storage
