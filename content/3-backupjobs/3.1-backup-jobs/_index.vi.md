---
title : "Tạo tác vụ AWS Backup theo yêu cầu của phiên bản Amazon EC2"
date :  "2025-06-13" 
weight : 1
chapter : false
pre : " <b> 3.1. </b> "
---

Bước 1: Mở **AWS Backup console**

 Cấu hình các dịch vụ được sử dụng với AWS Backup

 Ở phía bên trái của **AWS Backup console**, trong **My account**, chọn Cài đặt.
![EC2](/images/3.1.createawsbackup/1.jpg)

Bước 2: Trên trang **Service opt-in**, chọn **Configure resources**.
![EC2](/images/3.1.createawsbackup/2.jpg)

Bước 3: Trên trang **Configure resources**, sử dụng các công tắc chuyển đổi để bật hoặc tắt các dịch vụ được sử dụng với AWS Backup. Trong phòng thí nghiệm này, chỉ chọn EC2, sau đó nhấp vào **Confirm**
![EC2](/images/3.1.createawsbackup/3.jpg)

Bước 4: Quay trở lại **AWS Backup**, trong **My account** ở ngăn điều hướng bên trái, chọn  **Protected resources**
- Nhấp vào nút **Create on-demand backup**.
![EC2](/images/3.1.createawsbackup/4.jpg)




Bước 5: Trên trang Tạo bản sao lưu theo yêu cầu, hãy chọn các tùy chọn sau:
  + Chọn **Resource type** là EC2
  + Chọn Instance ID of the EC2 rmà bạn vừa tạo ở chương trước
  + Chọn **Create backup now** trong **Backup window**
  + Chọn **Forever** cho **TOtal retention period**
  + Select **Default** cho **Backup vault**. Tùy chọn, bạn có thể tạo kho lưu trữ sao lưu của riêng mình
  + Chọn **Default role** trong **IAM role**
  + Nhấp chọn **Create on-demand backup**
![EC2](/images/3.1.createawsbackup/5.jpg)
![EC2](/images/3.1.createawsbackup/6.jpg)

Bước 6: Trên trang **Jobs**, bạn sẽ thấy các công việc sao lưu mà bạn đã tạo
![EC2](/images/3.1.createawsbackup/7.jpg)

Bước 7: Chọn **Backup job ID** để xem thông tin chi tiết 





