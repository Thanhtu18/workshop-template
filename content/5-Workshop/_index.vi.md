---
title: "Workshop"
date: "2025-09-09"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

# Xây dựng Nền tảng Quản lý Nhiệm vụ với DevOps trên AWS Serverless

#### Tổng quan

**AWS Serverless** cho phép xây dựng và triển khai ứng dụng mà không cần quản lý máy chủ, tự động mở rộng theo nhu cầu và chỉ trả phí cho những gì bạn sử dụng.

Trong workshop này, chúng ta sẽ học cách thiết kế, xây dựng và triển khai một nền tảng quản lý nhiệm vụ **TaskHub** hoàn chỉnh sử dụng kiến trúc serverless và quy trình DevSecOps tự động hóa.

Chúng ta sẽ tạo một hệ thống bao gồm frontend, backend API, database và CI/CD pipeline hoàn chỉnh. Workshop tập trung vào ba thành phần chính để xây dựng ứng dụng production-ready trên AWS:

+ **Serverless Backend** - Sử dụng AWS Lambda để xử lý nghiệp vụ, API Gateway làm cổng giao tiếp, DynamoDB lưu trữ dữ liệu, và Cognito quản lý xác thực người dùng với chi phí tối ưu.

+ **Content Delivery** - Triển khai ứng dụng Next.js trên S3, phân phối toàn cầu qua CloudFront với độ trễ thấp, và bảo vệ bằng AWS WAF chống các cuộc tấn công web phổ biến.

+ **DevOps Pipeline** - Tự động hóa quy trình build, test và deploy sử dụng CodePipeline và CodeBuild, tích hợp kiểm tra bảo mật với CodeGuru, và quản lý infrastructure as code với CloudFormation.

#### Nội dung

1. [Tổng quan về workshop](5.1-Workshop-overview/)
2. [Chuẩn bị](5.2-Prerequiste/)
3. [Truy cập đến S3 từ VPC](5.3-S3-vpc/)
4. [Truy cập đến S3 từ TTDL On-premises](5.4-S3-onprem/)
5. [VPC Endpoint Policies (làm thêm)](5.5-Policy/)
6. [Dọn dẹp tài nguyên](5.6-Cleanup/)

[Thiết lập Chính sách Quyền hạn (IAM Policy)](5.3-Policy/)
[Triển khai hàm phi máy chủ với AWS Lambda](5.4-Lambda/)
[Xây dựng Cổng API với Amazon API Gateway](5.5-APIGateway/)
[Sử dụng Cơ sở dữ liệu NoSQL hiệu năng cao Amazon DynamoDB](5.6-DynamoDB/)
[Lưu trữ đối tượng đơn giản và bảo mật với Amazon S3](5.7-S3/)
[Tăng tốc độ phân phối nội dung với Amazon CloudFront (CDN)](5.8-CloudFront/)
[Quản lý danh tính và truy cập người dùng với Amazon Cognito](5.9-Cognito/)
[Quản lý khóa mã hóa với AWS Key Management Service (KMS)](5.10-KeyManagementService/)
[Xây dựng Quy trình CI/CD với AWS CodePipeline](5.11-CodePileline/)
[Tự động hóa xây dựng và kiểm thử mã nguồn với AWS CodeBuild](5.12-CodeBuild/)
[Đánh giá và tối ưu mã nguồn tự động bằng Amazon CodeGuru](5.13-CodeGuru/)
[Quản lý Cơ sở hạ tầng dưới dạng mã (IaC) với AWS CloudFormation](5.14-CloudFormation/)
[Thu thập, giám sát và phân tích nhật ký với Amazon CloudWatch Logs](5.15-CloudWatchLogs/)

[Sử dụng Dịch vụ Thông báo Đơn giản Amazon SNS](5.16-SNS/)

[Thiết lập Giám sát và Báo động Hiệu năng với Amazon CloudWatch](5.17-CloudWatch/)













