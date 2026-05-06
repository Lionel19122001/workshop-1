---
title : "Setup QuickSight"
date : 2024-01-01
weight : 3
chapter : false
pre : " <b> 3.3 </b> "
---

Set up Amazon QuickSight for the workshop dashboard.

#### Steps
1. Open the S3 bucket that contains the exported billing files and copy the object URL.
![overview](/images/2.2-MonitorCost/17-setup.png)
2. In the AWS console, open the **QuickSight** folder for the workshop.
![overview](/images/2.2-MonitorCost/18-setup.png)
![overview](/images/2.2-MonitorCost/19-setup.png)
3. Open the folder, then select the `<example>-QuickSightManifest.json` file.
![overview](/images/2.2-MonitorCost/20-setup.png)
4. Copy the S3 URL from the manifest details.
![overview](/images/2.2-MonitorCost/21-setup.png)
![overview](/images/2.2-MonitorCost/22-setup.png)
5. In **Amazon QuickSight**, create a new dataset and choose the source you prepared.
![overview](/images/2.2-MonitorCost/23-setup.png)
6. Create the data source and complete the import flow.
![overview](/images/2.2-MonitorCost/24-setup.png)
![overview](/images/2.2-MonitorCost/25-setup.png)
7. Name the data source `myCostExport`, paste the S3 URL, and click **Connect**.
![overview](/images/2.2-MonitorCost/26-setup.png)
![overview](/images/2.2-MonitorCost/27-setup.png)
![overview](/images/2.2-MonitorCost/28-setup.png)
8. Create the dashboard and customize it for your workshop requirements. 
9. The screenshots below show one example setup you can adapt for your workshop.
![overview](/images/2.2-MonitorCost/29-setup.png)
![overview](/images/2.2-MonitorCost/30-setup.png)
10. Name the dashboard, for example **My Cost**, then open it to verify the setup.
![overview](/images/2.2-MonitorCost/31-setup.png)

#### Result
QuickSight is now connected to the workshop data source and ready for dashboard review and sharing.
![overview](/images/2.2-MonitorCost/32-setup.png)
