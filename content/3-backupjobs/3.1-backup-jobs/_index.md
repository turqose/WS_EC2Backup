---
title : "Create an on-demand AWS Backup job of an Amazon EC2 instance"
date :  "2025-06-13" 
weight : 1
chapter : false
pre : " <b> 3.1. </b> "
---

Step 1: Open the **AWS Backup console**

 Configure the services used with AWS Backup

 On the left side of **AWS Backup console**, under **My account**, choose Settings.
![EC2](/images/3.1.createawsbackup/1.jpg)

Step 2: On the **Service opt-in** page, choose **Configure resources**
![EC2](/images/3.1.createawsbackup/2.jpg)

Step 3: On the **Configure resources** page, use the toggle switches to enable or disable the services used with AWS Backup. In this lab, only select EC2, then click **Confirm**.
![EC2](/images/3.1.createawsbackup/3.jpg)

Step 4: Back in the **AWS Backup** console, under **My account** in the left navigation pane, select **Protected resources**
 - Click **Create on-demand backup** button
![EC2](/images/3.1.createawsbackup/4.jpg)


Step 5: On the Create on-demand backup page, choose the following options:
  + Select **Resource type** is EC2
  + Select Instance ID of the EC2 resource that you just created in the previous chapter
  + Choose **Create backup now** under the **Backup window**
  + Select **Forever** for **TOtal retention period**
  + Select **Default** for **Backup vault**. Optionally, you can create your own backup vault
  + Choose **Default role** under **IAM role**
  + Click **Create on-demand backup**
![EC2](/images/3.1.createawsbackup/5.jpg)
![EC2](/images/3.1.createawsbackup/6.jpg)

Step 6: On the **Jobs** page, you will see the backup jobs you created
![EC2](/images/3.1.createawsbackup/7.jpg)

Step 7: Choose the **Backup job ID** to see the details of that job
