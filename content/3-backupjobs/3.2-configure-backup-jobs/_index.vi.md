---
title : "Cấu hình các tác vụ sao lưu AWS tự động"
date :  "2025-06-13" 
weight : 2
chapter : false
pre : " <b> 3.2. </b> "
---

Bước 1: Trong **AWS Backup console**, chọn **Backup plans** ở thanh điều hướng bên trái dưới mục **My account**, sau đó nhấn Create backup plan
![EC2](/images/3.2.conect/1.jpg)

Bước 2: Trên trang **Create backup plans** , chọn các tùy chọn sau:
  + Chọn **Build a new plan**
  + Nhập Tên kế hoạch sao lưu **backup plan name**
  + Nhập Tên quy tắc sao lưu **Backup rule name**
  + Chọn **Default** cho **Backup vault**. Hoặc tùy chọn, bạn có thể tạo vault sao lưu của riêng mình
  + Chọn **Daily** cho **Backup frequency** (Tần suất sao lưu)
  + **Backup windows** bao gồm thời gian bắt đầu của cửa sổ sao lưu và thời lượng của cửa sổ (tính bằng giờ). Lab này sẽ đặt giá trị mặc định, hoặc bạn có thể tự cấu hình theo ý muốn
  + Chọn **Forever** cho **Total retention period**
  + Cuối cùng, nhấp vào **Create plan**

![EC2](/images/3.2.conect/2.jpg)
![EC2](/images/3.2.conect/3.jpg)
![EC2](/images/3.2.conect/4.jpg)
![EC2](/images/3.2.conect/5.jpg)

Bước 3: Quay lại trang **Backup plans**, bạn sẽ thấy kế hoạch sao lưu mà bạn vừa tạo
![EC2](/images/3.2.conect/6.jpg)

Bước 4: Nhấp vào **Backup plan** để xem chi tiết. Trên trang **EC2-backup-plan**, chọn nút **Assign resources**
![EC2](/images/3.2.conect/7.jpg)

Bước 5: Nhập **Resource assignment name**(Tên phân công tài nguyên). Sau đó chọn **Default role** trong phần **IAM role**
![EC2](/images/3.2.conect/8.jpg)

Bước 6: Trong phần **Define resource selection**, chọn **Include specific resource types**. Sau đó chọn **Resource types** là **EC2**. Cuối cùng, nhấn nút **Assign resources** 
![EC2](/images/3.2.conect/9.jpg)

Bước 7: Trở lại trang **AWS Backup console** Các công việc sao lưu sẽ xuất hiện trong mục **Jobs**
![EC2](/images/3.2.conect/10.jpg)
