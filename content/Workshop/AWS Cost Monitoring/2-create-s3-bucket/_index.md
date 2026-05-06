---
title : "Create S3 bucket"
date : 2024-01-01
weight : 2
chapter : false
pre : " <b> 2 </b> "
---

Create an Amazon S3 bucket to store exported billing data files.

#### Steps
1. Open **Amazon S3** in the AWS console.
![overview](/images/2.2-MonitorCost/11-s3.png)
2. Choose **Create bucket**.
![overview](/images/2.2-MonitorCost/12-s3.png)
3. Enter a globally unique bucket name (for example: `workshop-cost-export-<your-name>`).
![overview](/images/2.2-MonitorCost/13-s3.png)
4. Keep **Block all public access** enabled.
5. (Optional) Enable bucket versioning for safer updates.
![overview](/images/2.2-MonitorCost/15-s3.png)
6. Create the bucket.
![overview](/images/2.2-MonitorCost/14-s3.png)

#### Outcome
You have an S3 bucket ready to receive billing export files.

![overview](/images/2.2-MonitorCost/16-s3.png)