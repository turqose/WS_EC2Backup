---
title : "Dọn dẹp tài nguyên"
date :  "2025-06-13" 
weight : 5 
chapter : false
pre : " <b> 5. </b> "
---

Thực hiện các bước sau để xóa tài nguyên đã tạo trong bài 

#### Xóa phiên bản EC2

1. Truy cập EC2   
   + Bước 1: hấp vào **Instances**.
   + Bước 2: Chọn cả **EC2 Backup** và các phiên bản  **EC2 Backup** đã được khôi phục
   + Bước 3: Nhấn vào **Instance state**
   + Bước 4: Nhấn vào **Terminate instance**, sau đó nhấn vào **Terminate** để xác nhận
![EC2](/images/5.clear/1.jpg)

#### Xóa điểm khôi phục của AWS Backup
1.  Truy cập AWS Backup 
   + Bước 1: Nhấn vào **Vaults**
   + Bước 2: Nhấn vào kho lưu trữ **Default**
   + Bước 3: Chọn **Recovery point**
   + Bước 4: Nhấn vào **Actions**, sao đó chọn **delete**
![EC2](/images/5.clear/2.jpg)

#### Xóa kế hoạch sao lưu AWS Backup
1. Truy cập AWS Backup 
   + Bước 1: Chọn **Backup plans**
   + Bước 2: Nhấp vào tên kế hoạch sao lưu **EC2-backup-plan** 
   + Bước 3: Chọn **EC2-resources** trong phần **Resource assignments**
   + Bước 4: Nhấn **Delete**
![EC2](/images/5.clear/3.jpg)




