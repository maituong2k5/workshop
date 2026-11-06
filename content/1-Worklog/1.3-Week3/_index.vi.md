---
title: "Nhật ký công việc Tuần 3"
date: 2026-08-22
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

## Mục tiêu

- Hiểu những kiến thức cơ bản về Amazon EC2 và vai trò của dịch vụ này trong AWS.
- Tìm hiểu các loại EC2 Instance và mục đích sử dụng của từng loại.
- Hiểu về Amazon Machine Image (AMI) và Amazon EBS.
- Tìm hiểu Key Pair, Security Group, Elastic IP và User Data.
- Nắm được các lệnh Linux cơ bản và cách quản lý hệ thống tệp.
- Tìm hiểu cách quản lý người dùng, nhóm và quyền truy cập trong Linux.
- Thực hành kết nối đến EC2 Instance bằng SSH.
- Tìm hiểu cách cài đặt và cấu hình Nginx trên máy chủ Ubuntu.

## Nhật ký công việc

| Ngày  | Nội dung công việc                                                                                                                                                                                                                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                                                                                       |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **1** | - Giới thiệu tổng quan về Amazon EC2.<br>- Tìm hiểu các loại EC2 Instance và mục đích sử dụng của từng loại.<br>- Tìm hiểu Amazon Machine Image (AMI).<br>- Khám phá các mô hình tính phí EC2: On-Demand, Reserved Instances và Spot Instances.                                                                                                                                                      | 22/08/2026   | 22/08/2026      | [Tài liệu Amazon EC2](https://docs.aws.amazon.com/ec2/)                                                                  |
| **2** | - Tìm hiểu Amazon EBS và khả năng lưu trữ dữ liệu.<br>- Tìm hiểu Key Pair và Security Group.<br>- Tìm hiểu Elastic IP và EC2 User Data.<br>- Thực hành khởi tạo một EC2 Instance sử dụng Ubuntu.                                                                                                                                                                                                     | 23/08/2026   | 23/08/2026      | [Tài liệu Amazon EC2](https://docs.aws.amazon.com/ec2/)                                                                  |
| **3** | - Giới thiệu về hệ điều hành Linux.<br>- Tìm hiểu hệ thống tệp và cấu trúc thư mục trong Linux.<br>- Phân biệt đường dẫn tuyệt đối và đường dẫn tương đối.<br>- Thực hành các lệnh Linux cơ bản: `pwd`, `ls`, `cd`, `mkdir`, `cp` và `mv`.                                                                                                                                                           | 24/08/2026   | 24/08/2026      | [Tài liệu Ubuntu Server](https://documentation.ubuntu.com/server/)                                                       |
| **4** | - Tìm hiểu người dùng và nhóm trong Linux.<br>- Tìm hiểu các quyền truy cập tệp: Read, Write và Execute.<br>- Tìm hiểu người dùng root và lệnh `sudo`.<br>- Thực hành quản lý người dùng và quyền truy cập bằng các lệnh `whoami`, `chmod`, `chown`, `groups`, `useradd` và `passwd`.                                                                                                                | 25/08/2026   | 25/08/2026      | [Tài liệu Ubuntu Server](https://documentation.ubuntu.com/server/)                                                       |
| **5** | - Tìm hiểu SSH và cơ chế xác thực bằng khóa (Key-based Authentication).<br>- Tìm hiểu cách truyền tệp bằng SCP.<br>- Tìm hiểu quản lý tiến trình và dịch vụ trong Linux.<br>- Thực hành kết nối đến EC2 Instance bằng SSH.<br>- Thực hành các lệnh như `ps aux`, `top`, `df -h`, `free -m` và `systemctl status`.                                                                                    | 26/08/2026   | 26/08/2026      | [AWS – Kết nối đến máy chủ Linux](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-connect-methods.html) |
| **6** | - Giới thiệu về Web Server và Nginx.<br>- Tìm hiểu giao thức HTTP/HTTPS và các cổng 80, 443.<br>- Tìm hiểu cấu hình cơ bản của Nginx.<br>- Thực hành cài đặt Nginx trên Ubuntu bằng các lệnh `sudo apt update` và `sudo apt install nginx -y`.<br>- Khởi chạy và kiểm tra trạng thái dịch vụ Nginx.                                                                                                  | 27/08/2026   | 27/08/2026      | [Tài liệu Nginx](https://nginx.org/en/docs/)                                                                             |
| **7** | - Ôn tập và thực hành các kiến thức đã học trong tuần.<br>- Khởi tạo và cấu hình một EC2 Instance sử dụng Ubuntu.<br>- Cấu hình Security Group và kết nối thông qua SSH.<br>- Thực hành các thao tác quản trị máy chủ Linux cơ bản.<br>- Cài đặt và khởi chạy Nginx trên EC2 Instance.<br>- Truy cập Web Server thông qua địa chỉ Public IP.<br>- Tổng kết kiến thức và ghi lại quá trình thực hành. | 28/08/2026   | 28/08/2026      | [Tài liệu Amazon EC2](https://docs.aws.amazon.com/ec2/)<br>[Tài liệu Nginx](https://nginx.org/en/docs/)                  |

## Kết quả đạt được

- Hiểu được kiến thức cơ bản về Amazon EC2 và các thành phần chính.
- Biết cách khởi tạo và cấu hình EC2 Instance sử dụng Ubuntu.
- Hiểu về AMI, EBS, Key Pair và Security Group.
- Thực hành các lệnh Linux cơ bản và quản lý hệ thống tệp.
- Biết cách quản lý người dùng, nhóm và quyền truy cập trong Linux.
- Thực hành kết nối đến EC2 Instance bằng SSH và truyền tệp bằng SCP.
- Cài đặt và cấu hình Nginx trên máy chủ Ubuntu.
- Truy cập thành công Web Server cơ bản thông qua địa chỉ Public IP của EC2.
