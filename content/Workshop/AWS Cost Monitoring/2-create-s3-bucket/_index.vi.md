---
title : "Tạo S3 bucket"
date : 2024-01-01
weight : 2
chapter : false
pre : " <b> 2 </b> "
---

Tạo Amazon S3 bucket để lưu các file export dữ liệu billing.

#### Các bước
1. Mở **Amazon S3** trong AWS console.
![overview](/images/2.2-MonitorCost/11-s3.png)
2. Chọn **Create bucket**.
![overview](/images/2.2-MonitorCost/12-s3.png)
3. Nhập tên bucket duy nhất toàn cục (ví dụ: `workshop-cost-export-<your-name>`).
![overview](/images/2.2-MonitorCost/13-s3.png)
4. Giữ bật **Block all public access**.
5. (Tùy chọn) Bật versioning để cập nhật an toàn hơn.
![overview](/images/2.2-MonitorCost/15-s3.png)
6. Tạo bucket.
![overview](/images/2.2-MonitorCost/14-s3.png)

#### Kết quả
Bạn đã có S3 bucket sẵn sàng để nhận file export từ billing.

![overview](/images/2.2-MonitorCost/16-s3.png)
