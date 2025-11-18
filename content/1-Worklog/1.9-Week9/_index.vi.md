---
title: "Nhật ký tuần 9"
date: "2025-11-03"
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Hiểu cách dùng Tag để quản lý tài nguyên AWS  
* Thực hành tạo Resource Group và lọc tài nguyên theo Tag  
* Quản lý truy cập EC2 bằng Tag tài nguyên và IAM Policy  
* Hiểu IAM Permission Boundary và cách giới hạn quyền người dùng  

### Các công việc trong tuần:
| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --------- | ------------ | --------------- | ------------------- |
| 1   | - **Lab 27:** Manage Resources Using Tags and Resource Groups <br>&emsp;2. Using Tags <br>&emsp;2.1 Sử dụng Tag trên Console <br>&emsp;&emsp;- 2.1.1 Tạo EC2 instance kèm Tag <br>&emsp;&emsp;- 2.1.2 Quản lý Tag trên các tài nguyên AWS <br>&emsp;&emsp;- 2.1.3 Lọc tài nguyên theo Tag <br>&emsp;2.2 Sử dụng Tag với CLI <br>&emsp;3. Tạo Resource Group <br>&emsp;4. Dọn dẹp tài nguyên | 03/11/2025 | 03/11/2025 | <https://000027.awsstudygroup.com/> |
| 2   | - **Lab 28:** Manage access to EC2 services with resource tags through IAM services <br>&emsp;1. Introduction <br>&emsp;2. Preparation (chuẩn bị) <br>&emsp;&emsp;- 2.1 Tạo IAM user <br>&emsp;3. Tạo IAM Policy <br>&emsp;4. Tạo IAM Role <br>&emsp;5. Kiểm tra Policy: <br>&emsp;&emsp;- 5.1 Switch Roles <br>&emsp;&emsp;- 5.2 Kiểm tra IAM Policy <br>&emsp;&emsp;- 5.2.1 Truy cập EC2 console ở Region Tokyo <br>&emsp;&emsp;- 5.2.2 Truy cập EC2 console ở Region North Virginia <br>&emsp;&emsp;- 5.2.3 Thử tạo EC2 instance khi không có/đúng Tag yêu cầu <br>&emsp;&emsp;- 5.2.4 Chỉnh sửa Resource Tag trên EC2 instance <br>&emsp;&emsp;- 5.2.5 Quan sát kết quả Policy <br>&emsp;6. Dọn dẹp tài nguyên | 04/11/2025 | 04/11/2025 | <https://000028.awsstudygroup.com/> |
| 3   | - **Thực hành:** Ôn lại Lab 27 & Lab 28 <br>&emsp;+ Thực hành lại dùng Tag trên Console và CLI <br>&emsp;+ Lọc tài nguyên và dùng Resource Group <br>&emsp;+ Thực hành lại kiểm soát truy cập EC2 theo Tag với IAM Policy <br>&emsp;+ Ghi lại một số best practice đơn giản về Tag và kiểm soát truy cập | 05/11/2025 | 05/11/2025 | <https://000027.awsstudygroup.com/>, <https://000028.awsstudygroup.com/> |
| 4   | - **Lab 30:** Limitation of user rights with IAM Permission Boundary <br>&emsp;1. Introduction <br>&emsp;2. Preparation <br>&emsp;3. Tạo Restriction Policy (Permission Boundary) <br>&emsp;4. Tạo IAM Limited User (user bị giới hạn quyền) <br>&emsp;5. Test giới hạn quyền của IAM user <br>&emsp;6. Dọn dẹp tài nguyên | 06/11/2025 | 06/11/2025 | <https://000030.awsstudygroup.com/> |
| 5   | - **Thực hành:** Ôn lại Tag, IAM Policy và Permission Boundary <br>&emsp;+ Ôn lại cách Tag và Resource Group hỗ trợ quản lý tài nguyên <br>&emsp;+ Ôn lại kiểm soát truy cập EC2 theo Tag (Lab 28) <br>&emsp;+ Ôn lại Permission Boundary trong Lab 30 <br>&emsp;+ Tổng kết kiến thức đã học trong tuần 9 | 07/11/2025 | 07/11/2025 | <https://000027.awsstudygroup.com/>, <https://000028.awsstudygroup.com/>, <https://000030.awsstudygroup.com/> |

### 🏆 **Thành tựu tuần 9**

* **Tag và quản lý tài nguyên**
  * Thêm Tag cho EC2 và các tài nguyên khác trên Console
  * Lọc và tìm tài nguyên theo Tag
  * Dùng CLI để thao tác với Tag và tạo Resource Group

* **Kiểm soát truy cập EC2 bằng Tag**
  * Tạo IAM user, IAM policy và IAM role để kiểm soát truy cập theo Tag
  * Thử truy cập EC2 console ở nhiều Region (Tokyo, North Virginia)
  * Thử tạo EC2 instance có và không có Tag đúng yêu cầu
  * Chỉnh sửa Tag và quan sát Policy cho phép hoặc từ chối hành động

* **IAM Permission Boundary**
  * Tạo Restriction Policy dùng làm Permission Boundary
  * Tạo IAM user với quyền bị giới hạn
  * Kiểm tra những thao tác user được phép và không được phép trên AWS console

* **Thực hành và dọn dẹp**
  * Thực hành nhiều lần với Tag, Resource Group và IAM Policy
  * Dọn dẹp toàn bộ tài nguyên sau khi hoàn thành các lab
  * Hiểu rõ hơn cách kết hợp Tag và IAM để kiểm soát truy cập


