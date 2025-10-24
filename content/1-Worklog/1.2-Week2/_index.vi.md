---
title: "Worklog Tuần 2"
date: "2025-09-15"
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục Tiêu Tuần 2:

* Thiết lập Hybrid DNS với Route 53 Resolver.
* Thiết lập VPC peering

### Các nhiệm vụ được thực hiện trong tuần này:
| Ngày | Nhiệm vụ                                                                                                                                                                                                   | Ngày Bắt Đầu | Ngày Hoàn Thành | Tài Liệu Tham Khảo                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 1   | - Triển khai Amazon EC2 Instances <br> + Tạo EC2 Server <br> + Kiểm tra kết nối <br> + Tạo NAT Gateway <br> + Sử dụng Reachability Analyzer <br> + Tạo EC2 Instance Connect Endpoint <br> + AWS Systems Manager Session Manager <br> + CloudWatch Monitoring & Alerting <br> - Thiết lập kết nối Site-to-Site VPN trong AWS <br> + Tạo Virtual Private Gateway <br> + Tạo Customer Gateway <br> + Tạo VPN Connection <br> + Cấu hình Customer Gateway <br> + Chỉnh sửa AWS VPN Tunnel <br> + Cấu hình VPN thay thế <br> + Hướng dẫn khắc phục sự cố VPN                                                | 15/09/2025 | 15/09/2025 | <https://000003.awsstudygroup.com/> |
| 2   | - Kết nối VPN sử dụng Strongswan với Transit Gateway <br> + Tạo Transit Gateway <br> + Tạo Transit Gateway Attachment <br> + Cấu hình Route Tables <br> + Cấu hình Customer Gateway <br> - Dọn dẹp tài nguyên <br> - Thiết lập Hybrid DNS với Route 53 Resolver <br> - Giới thiệu Amazon Route 53<br>                   |16/09/2025 | 16/09/2025      | <https://000003.awsstudygroup.com/> <br> <https://000004.awsstudygroup.com/>|
| 3   | - Chuẩn bị Amazon Route 53 <br> + Tạo Key Pair <br> + Khởi tạo CloudFormation Template <br> + Cấu hình Security Group <br> - Kết nối tới RDGW <br> - Triển khai Microsoft AD <br> - Thiết lập DNS <br> + Tạo Route 53 Outbound Endpoint <br> + Tạo Route 53 Resolver Rules <br> + Tạo Route 53 Inbound Endpoints <br> + Kiểm tra kết quả <br> - Dọn dẹp tài nguyên | 17/09/2025 | 17/09/2025 | <https://000004.awsstudygroup.com/> |
| 4   | - Thiết lập VPC Peering <br> - Giới thiệu <br> - Yêu cầu tiên quyết <br>&emsp; + Khởi tạo CloudFormation Template <br>&emsp; + Tạo Security Group <br>&emsp; + Tạo EC2 Instance <br> - Cập nhật Network ACL <br> - VPC Peering <br> - Route Tables <br> - Cross-Peer DNS <br> - Dọn dẹp | 18/09/2025 | 18/09/2025 | <https://000019.awsstudygroup.com/> |
| 5   | - **Thực hành 1:** Tạo và cấu hình EC2 Server <br> - **Thực hành 2:** Kiểm tra kết nối tới EC2 Instance <br> - **Thực hành 3:** Thiết lập Hybrid DNS với Route 53 Resolver <br> - **Thực hành 4:** Khám phá Amazon Route 53 và các tính năng <br> - **Thực hành 5:** Tạo Key Pair và kiểm tra khả năng sẵn sàng cho Amazon Route 53 | 19/09/2025 | 19/09/2025 | 
### 🏆 **Thành Tựu Tuần 2**

* **Triển khai Amazon EC2 Instances**

  * Tạo EC2 Server và kiểm tra kết nối
  * Cấu hình NAT Gateway, Reachability Analyzer và EC2 Instance Connect Endpoint
  * Kích hoạt CloudWatch Monitoring & Alerting
  * Sử dụng AWS Systems Manager Session Manager

* **Cấu hình kết nối Site-to-Site VPN**

  * Tạo Virtual Private Gateway, Customer Gateway và VPN Connection
  * Chỉnh sửa VPN Tunnel và thực hiện khắc phục sự cố

* **Xây dựng kết nối VPN sử dụng Strongswan với Transit Gateway**

  * Tạo Transit Gateway và Attachments
  * Cấu hình Route Tables và Customer Gateway
  * Thiết lập Hybrid DNS với Route 53 Resolver

* **Triển khai Microsoft AD và cấu hình Route 53**

  * Tạo Route 53 Endpoints (Inbound & Outbound) và Resolver Rules
  * Kiểm tra phân giải DNS và xác minh kết nối

* **Triển khai VPC Peering và Cross-Peer DNS**

  * Tạo EC2 Instances, cập nhật Network ACLs và cấu hình Route Tables
  * Xác thực DNS qua các VPC được peer

* **Hoàn thành các bài thực hành**

  * Thiết lập EC2 và kiểm tra kết nối
  * Cấu hình Hybrid DNS và Route 53
  * Tạo key pair và xác thực hệ thống
