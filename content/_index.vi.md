---
title : "AWS EC2 Backup"
date :  "2025-06-13" 
weight : 1 
chapter : false
---
# Trong bài thực hành này, bạn sẽ được trang bị kiến thức nền tảng và trải nghiệm thực hành với các tính năng cốt lõi của AWS Backup

### Tổng Quan
 Trong bài thực hành này, bạn sẽ được trang bị kiến thức nền tảng và trải nghiệm thực hành với các tính năng cốt lõi của AWS Backup
- Khôi phục bản sao lưu của phiên bản EC2, nhằm kiểm tra khả năng phục hồi dữ liệu và xác minh rằng quy trình sao lưu của bạn đang hoạt động chính xác
- Gán tài nguyên vào một kế hoạch sao lưu hiện có bằng cách sử dụng thẻ (tags), cho phép quản lý sao lưu một cách linh hoạt và có khả năng mở rộng bằng cách tổ chức và liên kết tài nguyên dựa trên các giá trị thẻ cụ thể
- Sử dụng kế hoạch sao lưu để lên lịch và tự động hóa quá trình sao lưu các tài nguyên Amazon EC2 — bằng cách tận dụng các kế hoạch sao lưu trong AWS Backup, bạn có thể đảm bảo các bản sao lưu diễn ra đều đặn mà không cần can thiệp thủ công
- Tạo một công việc sao lưu theo yêu cầu cho phiên bản Amazon EC2, cho phép bạn chủ động khởi tạo một quy trình sao lưu ngay lập tức để bảo vệ dữ liệu
- Khám phá kho lưu trữ sao lưu (backup vaults) và trạng thái các công việc sao lưu, giúp bạn hiểu rõ cách AWS Backup lưu trữ dữ liệu một cách an toàn và theo dõi hiệu quả các hoạt động sao lưu và khôi phục
- Tìm hiểu về vai trò và quyền truy cập IAM cần thiết cho các hoạt động AWS Backup, đảm bảo bạn thiết lập các quyền kiểm soát truy cập phù hợp để quản lý sao lưu một cách an toàn
- Xem xét trạng thái tuân thủ và báo cáo sao lưu, giúp bạn theo dõi liệu các hoạt động sao lưu có đáp ứng các yêu cầu tổ chức hoặc quy định pháp lý hay không

### Nội dung trong bài viết
 1. [Giới Thiệu ](1-introduce/)
 2. [Các bước cần chuẩn bị](2-prerequiste/)
 3. [Tạo công việc sao lưu AWS](3-backupjobs/)
 4. [Khôi phục EC2 bằng AWS Backup](4-restore-backup/)
 5. [Dọn dẹp tài nguyên](5-cleanup/)
