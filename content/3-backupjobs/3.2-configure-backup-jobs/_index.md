---
title : "Configure automatic AWS Backup jobs"
date :  "2025-06-13" 
weight : 2
chapter : false
pre : " <b> 3.2. </b> "
---

Step 1: In the **AWS Backup console** select **Backup plans** in the left navigation pane under **My account**, and then Create backup plan
![EC2](/images/3.2.conect/1.jpg)

Step 2: Under the **Create backup plans** page, choose the following options:
  + select **Build a new plan**
  + Enter **backup plan name**
  + Enter **Backup rule name**
  + Select **Default** for **Backup vault**. Optionally, you can create your own backup vault
  + Select **Daily** for **Backup frequency**
  + **Backup windows** consist of the time that the backup window begins and the duration of the window in hours. This lab will set default or you can set whatever you want
  + Select **Forever** for **Total retention period**
  + Finally, click **Create plan**

![EC2](/images/3.2.conect/2.jpg)
![EC2](/images/3.2.conect/3.jpg)
![EC2](/images/3.2.conect/4.jpg)
![EC2](/images/3.2.conect/5.jpg)

Step 3: Back in to the **Backup plans** page, you will see the backup plan you just created.
![EC2](/images/3.2.conect/6.jpg)

Step 4: Click that **Backup plan** to see details. Then on the **EC2-backup-plan** page, choose **Assign resources** button
![EC2](/images/3.2.conect/7.jpg)

Step 5: Enter **Resource assignment name**. Then choose **Default role** under **IAM role** section
![EC2](/images/3.2.conect/8.jpg)

Step 6: Under **Define resource selection**, choose **Include specific resource types**. Then select **Resource types** is **EC2**. Finally, click **Assign resources** button
![EC2](/images/3.2.conect/9.jpg)

Step 7: Navigate to the **AWS Backup console**. The backup jobs will be seen under **Jobs**
![EC2](/images/3.2.conect/10.jpg)
