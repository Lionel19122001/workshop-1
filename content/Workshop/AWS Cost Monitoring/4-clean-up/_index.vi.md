---
title : "Dọn dẹp"
date : 2024-01-01
weight : 4
chapter : false
pre : " <b> 4 </b> "
---

Dọn dẹp các tài nguyên AWS được tạo trong workshop để tránh chi phí không cần thiết.

#### Các bước
1. Dọn dẹp người dùng và tài nguyên phân tích trên QuickSight.
Mở tài khoản quản trị, vào **Manage users**, và xóa các user workshop không còn sử dụng.
![overview](/images/2.2-MonitorCost/34-inviteUser.png)
![overview](/images/2.2-MonitorCost/45-cleanup.png)

Xóa dashboard **My Cost**.
![overview](/images/2.2-MonitorCost/44-cleanup.png)

Xóa dataset `myCostExport`.
![overview](/images/2.2-MonitorCost/46-cleanup.png)
![overview](/images/2.2-MonitorCost/47-cleanup.png)

Xóa data source `myCostExport` và analysis liên quan.
![overview](/images/2.2-MonitorCost/48-cleanup.png)
![overview](/images/2.2-MonitorCost/49-cleanup.png)

Mở **Manage account** và vào phần account settings.
![overview](/images/2.2-MonitorCost/50-cleanup.png)

Chọn **Manage**, tắt account termination protection, nhập `confirm`, rồi xóa account nếu môi trường này không còn cần thiết.
![overview](/images/2.2-MonitorCost/51-cleanup.png)
![overview](/images/2.2-MonitorCost/52-cleanup.png)

2. Xóa cấu hình billing data export.
Mở **Billing and Cost Management**.
![overview](/images/2.2-MonitorCost/6-dataExport.png)

Vào **Data export**, chọn `myDataCost`, và xóa export job.
![overview](/images/2.2-MonitorCost/53-cleanup.png)
![overview](/images/2.2-MonitorCost/54-cleanup.png)

3. Xóa S3 bucket và toàn bộ file export.
Mở Amazon S3.
![overview](/images/2.2-MonitorCost/11-s3.png)

Trong **General purpose buckets**, chọn `workshop-cost-export-<yourname>` và nhấn **Empty**.
![overview](/images/2.2-MonitorCost/55-cleanup.png)

Xác nhận xóa dữ liệu trong bucket.
![overview](/images/2.2-MonitorCost/56-cleanup.png)

Chọn lại bucket, nhấn **Delete**, và xác nhận xóa bucket.
![overview](/images/2.2-MonitorCost/57-cleanup.png)
![overview](/images/2.2-MonitorCost/58-cleanup.png)

#### Kết quả
Tất cả tài nguyên workshop đã được dọn dẹp và xóa khỏi AWS account của bạn.
