---
title : "Chuẩn bị EC2"
date :  "2025-06-13" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

### Giới thiệu

**Amazon Elastic Compute Cloud (Amazon EC2)**  là một dịch vụ thuê máy chủ ảo (instance) của Amazon Web Services (AWS), cho phép bạn chạy ứng dụng, website, hoặc hệ thống backend một cách linh hoạt và có khả năng mở rộng

### Tại sao lại là Amazon EC2?

**Amazon Elastic Compute Cloud (Amazon EC2)** cung cấp nền tảng điện toán rộng nhất và sâu nhất, với hơn 750 phiên bản và tùy chọn bộ xử lý, lưu trữ, mạng, hệ điều hành và mô hình mua hàng mới nhất để giúp bạn đáp ứng tốt nhất nhu cầu về khối lượng công việc của mình. Chúng tôi là nhà cung cấp dịch vụ đám mây lớn đầu tiên hỗ trợ bộ xử lý Intel, AMD và Arm, là đám mây duy nhất có phiên bản EC2 Mac theo yêu cầu và là đám mây duy nhất có mạng Ethernet 400 Gbps. Chúng tôi cung cấp hiệu suất giá tốt nhất cho đào tạo máy học, cũng như chi phí cho mỗi phiên bản suy luận thấp nhất trên đám mây. Nhiều khối lượng công việc SAP, điện toán hiệu suất cao (HPC), ML và Windows chạy trên AWS hơn bất kỳ đám mây nào khác

### Ưu Điểm
- **Tính linh hoạt và tùy biến cao**: Hàng chục kiểu instance, hệ điều hành và tùy chọn lưu trữ, mạng cho phép bạn thiết kế môi trường phù hợp nhất cho ứng dụng của mình
- **Khả năng tự động mở rộng**: EC2 hỗ trợ auto‑scaling để tự động tăng hoặc giảm số lượng instance dựa vào nhu cầu thực tế, giúp tối ưu hiệu suất và chi phí
- **Sẵn sàng và khôi phục lỗi nhanh**:Khả năng triển khai đa Availability Zones giúp giảm thiểu rủi ro khi một vùng gặp sự cố
- **Tích hợp sâu với hệ sinh thái AWS**: Dễ dàng kết nối EC2 với S3, RDS, ELB, IAM, CloudWatch… để xây dựng hệ thống end‑to‑end hiệu quả 
- **Phương thức trả phí linh hoạt**: Nhiều tùy chọn thanh toán (On‑Demand, Reserved Instances, Spot) giúp tối ưu ngân sách

### Nhược điểm
- **Chi phí khó dự đoán & có thể cao**: Mô hình phí phức tạp (theo giờ, băng thông, lưu trữ…) có thể dẫn đến chi phí vượt mức nếu không quản lý tốt
- **Cần kiến thức kỹ thuật**: Thiết lập mạng, bảo mật, backup, scaling – đều đòi hỏi kỹ năng nhất định, đặc biệt với người mới
- **Giới hạn tài nguyên theo khu vực**: Mỗi region EC2 có giới hạn số lượng instance – bạn phải request tăng quota nếu cần
- **Overhead quản trị**: EC2 là IaaS – bạn phải chịu trách nhiệm quản lý toàn bộ instance, từ patch, backup đến cập nhật hệ thống
- **Thời gian khởi tạo instance**: Khởi động instance mất vài phút, không phù hợp cho các tác vụ cực kỳ thời gian thực
- **Phụ thuộc vào kết nối mạng & vùng địa lý**: Hiệu suất và độ trễ phụ thuộc vào vị trí và độ ổn định của kết nối internet của bạn
- 
### Tổng Kết
| Ưu điểm  | 	Nhược điểm  |
|---|---|
|  Linh hoạt trong cấu hình | 	Chi phí thường không dễ dự đoán |
| Tự động mở rộng theo nhu cầu  | Cần kỹ năng chuyên môn  |
|  Sẵn sàng cao, hỗ trợ SAN hóa lỗi |  Giới hạn tài nguyên theo vùng |
|  Tích hợp mạnh với hệ sinh thái AWS | 	Phải tự quản trị hệ thống  |
| Nhiều lựa chọn giá phù hợp | 	Khởi động chậm |


{{% notice note %}}
Dưới đây là trang web mà bạn có thể tham khảo
{{% /notice %}}

- [AWS EC2](https://aws.amazon.com/ec2/)
