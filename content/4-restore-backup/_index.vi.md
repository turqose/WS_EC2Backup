---
title : "Khôi phục phiên bản Amazon EC2 bằng AWS Backup"
date :  "2025-06-13" 
weight : 4
chapter : false
pre : " <b> 4. </b> "
---

Bước 1: Trong **AWS Backup console** chọn **Vaults** trong thanh điều hướng bên trái dưới phần **My account**, sau đó chọn **Default** trên trang **Vaults**
![EC2](/images/4.restore/1.jpg)

Bước 2: Chọn bản sao lưu mới nhất đã hoàn tất
![EC2](/images/4.restore/2.jpg)

Bước 3: Chọn **Restore**
![EC2](/images/4.restore/3.jpg)

Bước 4:Trong phần Network settings, giữ nguyên cài đặt mặc định hoặc chỉ định các tùy chọn cho: **Instance type**, **Virtual Private Cloud (VPC)**, **Subnet**, **Security groups**, and **Instance IAM role settings**
 Chọn **Proceed with no IAM role** trong phần **Instance IAM role**
![EC2](/images/4.restore/4.jpg)

Bước 5: Trong phần **Restore section**, chọn **Default role**
+ Bỏ qua phần **Advanced settings** giữ nguyên mặc định và nhấn nút **Restore backup**
![EC2](/images/4.restore/5.jpg)

Bước 6: Kiểm tra công việc khôi phục của bạn trong phần **Restore jobs** tại [**AWS Backup console**]
![EC2](/images/4.restore/6.jpg)

Bước 7: Chuyển đến **Amazon EC2 console** và chọn **Instances** trong thanh điều hướng bên trái để xem phiên bản EC2 đã được khôi phục
![EC2](/images/4.restore/7.jpg)

