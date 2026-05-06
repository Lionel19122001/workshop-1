---
title : "Clean up"
date : 2024-01-01
weight : 4
chapter : false
pre : " <b> 4 </b> "
---

Clean up AWS resources created during the workshop to avoid unnecessary costs.

#### Steps
1. Remove QuickSight users and analytics assets.
Open the management account, go to **Manage users**, and remove workshop users that are no longer needed.
![overview](/images/2.2-MonitorCost/34-inviteUser.png)
![overview](/images/2.2-MonitorCost/45-cleanup.png)

Delete the **My Cost** dashboard.
![overview](/images/2.2-MonitorCost/44-cleanup.png)

Delete the `myCostExport` dataset.
![overview](/images/2.2-MonitorCost/46-cleanup.png)
![overview](/images/2.2-MonitorCost/47-cleanup.png)

Delete the `myCostExport` data source and related analysis.
![overview](/images/2.2-MonitorCost/48-cleanup.png)
![overview](/images/2.2-MonitorCost/49-cleanup.png)

Open **Manage account** and go to account settings.
![overview](/images/2.2-MonitorCost/50-cleanup.png)

Select Account settings and choose **Manage**
![overview](/images/2.2-MonitorCost/51-cleanup.png)
Disable account termination protection, type `confirm`, and delete the workshop account if this environment is no longer required.
![overview](/images/2.2-MonitorCost/52-cleanup.png)

2. Delete the billing data export.
Open **Billing and Cost Management**.
![overview](/images/2.2-MonitorCost/6-dataExport.png)

Go to **Data export**, select `myDataCost`, and delete the export job.
![overview](/images/2.2-MonitorCost/53-cleanup.png)
![overview](/images/2.2-MonitorCost/54-cleanup.png)

3. Delete the S3 bucket and exported files.
Open Amazon S3.
![overview](/images/2.2-MonitorCost/11-s3.png)

Under **General purpose buckets**, select `workshop-cost-export-<yourname>` and click **Empty**.
![overview](/images/2.2-MonitorCost/55-cleanup.png)

Confirm empty bucket.
![overview](/images/2.2-MonitorCost/56-cleanup.png)

Select the same bucket, click **Delete**, and confirm bucket deletion.
![overview](/images/2.2-MonitorCost/57-cleanup.png)
![overview](/images/2.2-MonitorCost/58-cleanup.png)



#### Outcome
All workshop resources have been cleaned up and removed from your AWS account.
