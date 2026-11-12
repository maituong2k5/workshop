---
title: "Nhật ký tuần 6"
date: 2026-09-12
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

**### Mục tiêu tuần 6:**

- Hiểu các khái niệm và tính năng cơ bản của Amazon Relational Database Service (RDS).
- Tìm hiểu cách tạo và cấu hình một phiên bản Amazon RDS MySQL.
- Hiểu về DB Instance, DB Subnet Group và kết nối cơ sở dữ liệu.
- Tìm hiểu cách cấu hình quyền truy cập cơ sở dữ liệu thông qua Security Groups.
- Hiểu các chức năng sao lưu, khôi phục và giám sát cơ sở dữ liệu trên Amazon RDS.
- Tìm hiểu cách chuyển cơ sở dữ liệu MySQL hiện có từ môi trường Local lên Amazon RDS.
- Cấu hình Spring Boot Backend để kết nối với cơ sở dữ liệu MySQL trên Cloud.

**### Các công việc cần thực hiện trong tuần:**

| Ngày  | Công việc                                                                                                                                                                                                                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                    |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------------------- |
| **1** | - Giới thiệu về Amazon Relational Database Service (RDS)<br>- Tìm hiểu tính năng và lợi ích của dịch vụ cơ sở dữ liệu được quản lý<br>- Khám phá các hệ quản trị cơ sở dữ liệu được hỗ trợ<br>- Tìm hiểu khái niệm cơ bản về RDS DB Instance                                                                               | 12/09/2026   | 12/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |
| **2** | - Tìm hiểu cách tạo Amazon RDS Instance<br>- Lựa chọn MySQL làm Database Engine<br>- Cấu hình DB Instance và bộ nhớ lưu trữ<br>- Tìm hiểu các loại DB Instance và tùy chọn triển khai                                                                                                                                      | 13/09/2026   | 13/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |
| **3** | - Tìm hiểu DB Subnet Groups<br>- Phân biệt truy cập cơ sở dữ liệu Public và Private<br>- Cấu hình VPC và Subnet cho RDS<br>- Tìm hiểu kết nối mạng đến cơ sở dữ liệu                                                                                                                                                       | 14/09/2026   | 14/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |
| **4** | - Cấu hình Security Groups cho Amazon RDS<br>- Tìm hiểu quy tắc Inbound cho kết nối MySQL<br>- Cho phép truy cập cơ sở dữ liệu từ Security Group của Backend EC2<br>- Tìm hiểu các nguyên tắc bảo mật cơ sở dữ liệu cơ bản                                                                                                 | 15/09/2026   | 15/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |
| **5** | - Tìm hiểu chức năng sao lưu và khôi phục của Amazon RDS<br>- Tìm hiểu Automated Backups và Snapshots<br>- Khám phá giám sát cơ sở dữ liệu thông qua Amazon CloudWatch<br>- Rà soát tính sẵn sàng và cấu hình bảo trì RDS                                                                                                  | 16/09/2026   | 16/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |
| **6** | - Chuẩn bị cơ sở dữ liệu MySQL phone_store hiện tại để chuyển lên AWS<br>- Export database Local bằng công cụ SQL<br>- Tạo và cấu hình cơ sở dữ liệu trên Cloud<br>- Import cấu trúc bảng và dữ liệu ban đầu vào Amazon RDS                                                                                                | 17/09/2026   | 17/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |
| **7** | **Thực hành:**<br>+ Tạo và cấu hình Amazon RDS MySQL Instance<br>+ Kết nối RDS bằng công cụ quản lý cơ sở dữ liệu<br>+ Cấu hình thông tin kết nối database trong Spring Boot<br>+ Kiểm tra kết nối giữa EC2 và RDS<br>+ Kiểm tra các bảng và dữ liệu trong cơ sở dữ liệu<br>+ Rà soát bảo mật và cấu hình sao lưu database | 18/09/2026   | 18/09/2026      | [AWS CloudJourney](https://cloudjourney.awsfcaj.com/) |

**### Kết quả đạt được trong tuần 6:**

- Hiểu các khái niệm và tính năng cơ bản của Amazon RDS.
- Biết cách tạo và cấu hình RDS MySQL Instance.
- Làm quen với DB Instance, DB Subnet Group và kết nối cơ sở dữ liệu.
- Thực hành cấu hình Security Groups để kiểm soát quyền truy cập database.
- Hiểu các chức năng sao lưu, khôi phục và giám sát cơ bản của Amazon RDS.
- Tìm hiểu cách Export và chuyển cơ sở dữ liệu MySQL từ môi trường Local lên AWS.
- Khám phá cách kết nối ứng dụng Spring Boot với Amazon RDS.
- Xây dựng nền tảng tích hợp Backend chạy trên EC2 với cơ sở dữ liệu MySQL trên Cloud.
- Có thêm kiến thức thực tế về triển khai và quản lý tài nguyên cơ sở dữ liệu trên AWS.
