---
title : "Thiết lập QuickSight"
date : 2024-01-01
weight : 3
chapter : false
pre : " <b> 3.3 </b> "
---

Thiết lập Amazon QuickSight cho dashboard chi phí của workshop.

#### Các bước
1. Mở S3 bucket chứa file export billing và sao chép object URL.
![overview](/images/2.2-MonitorCost/17-setup.png)
2. Trong AWS console, mở thư mục **QuickSight** của workshop.
![overview](/images/2.2-MonitorCost/18-setup.png)
![overview](/images/2.2-MonitorCost/19-setup.png)
3. Mở thư mục và chọn file `<example>-QuickSightManifest.json`.
![overview](/images/2.2-MonitorCost/20-setup.png)
4. Sao chép S3 URL trong thông tin manifest.
![overview](/images/2.2-MonitorCost/21-setup.png)
![overview](/images/2.2-MonitorCost/22-setup.png)
5. Trong **Amazon QuickSight**, tạo dataset mới và chọn nguồn dữ liệu đã chuẩn bị.
![overview](/images/2.2-MonitorCost/23-setup.png)
6. Tạo data source và hoàn tất luồng import dữ liệu.
![overview](/images/2.2-MonitorCost/24-setup.png)
![overview](/images/2.2-MonitorCost/25-setup.png)
7. Đặt tên data source là `myCostExport`, dán S3 URL, rồi nhấn **Connect**.
![overview](/images/2.2-MonitorCost/26-setup.png)
![overview](/images/2.2-MonitorCost/27-setup.png)
![overview](/images/2.2-MonitorCost/28-setup.png)
8. Tạo dashboard và tùy chỉnh theo nhu cầu của workshop.
9. Các ảnh dưới đây là một ví dụ để bạn tham khảo và điều chỉnh theo mục đích sử dụng.
![overview](/images/2.2-MonitorCost/29-setup.png)
![overview](/images/2.2-MonitorCost/30-setup.png)
10. Đặt tên dashboard, ví dụ **My Cost**, sau đó mở dashboard để xác nhận cấu hình.
![overview](/images/2.2-MonitorCost/31-setup.png)

#### Kết quả
QuickSight đã được kết nối với nguồn dữ liệu workshop và sẵn sàng để xem, chia sẻ dashboard.
![overview](/images/2.2-MonitorCost/32-setup.png)
