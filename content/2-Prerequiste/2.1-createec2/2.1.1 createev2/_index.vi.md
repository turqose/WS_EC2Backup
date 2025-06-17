---
title : "Create EC2"
date :  "2025-06-13" 
weight : 1
chapter : false
pre : " <b> 2.1.1 </b> "
---


#### Tạo EC2 
Bước 1: Truy cập **AWS Management Console** và mở AWS EC2 
   + Chọn **EC2**
![EC2](/images/2.1.1createEc2/1.jpg)


Bước 2: Trong bảng điều hướng bên trái của **AWS EC2 console**, dưới mục **Intances**, chọn **Intances**, sau đó chọn **Launch Instance**
![EC2](/images/2.1.1createEc2/2.jpg)
Bước 3: Trên trang **Launch an instance**, tại mục **Name**, nhập tên 
![EC2](/images/2.1.1createEc2/3.jpg)

Bước 4: Ở tab **Quick Start**, chọn **Amazon Linux**. Sau đó chọn **Amazon Linux 2023 AMI** và **Architecture** như hình 
![EC2](/images/2.1.1createEc2/4.jpg)

Bước 5: Mục **Instance Type**, chọn **t2.micro**
![EC2](/images/2.1.1createEc2/5.jpg)

Bước 6: Để mặc định các mục **Key pair**, **Network settings**, **Configure storage** , **Advanced details** 
- Nhấp vào **Launch instance**
![EC2](/images/2.1.1createEc2/6.jpg)

Bước 7: Trở lại trang **Instances**, bạn sẽ thấy một phiên bản EC2 vừa được tạo làm mới trang. Chờ cho **Status check** hoàn thành 2/2
![EC2](/images/2.1.1createEc2/7.jpg)
