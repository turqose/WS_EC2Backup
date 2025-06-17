---
title : "Restore an Amazon EC2 instance using AWS Backup"
date :  "2025-06-13" 
weight : 4
chapter : false
pre : " <b> 4. </b> "
---

Step 1: In the **AWS Backup console**, select **Vaults** in the left navigation pane under **My account**, then click the **Default** vault in the **Vaults** page
![EC2](/images/4.restore/1.jpg)

Step 2: Select the latest completed backup
![EC2](/images/4.restore/2.jpg)

Step 3: Choose **Restore**
![EC2](/images/4.restore/3.jpg)

Step 4: In the Network settings pane, accept the defaults or specify the options for the **Instance type**, **Virtual Private Cloud (VPC)**, **Subnet**, **Security groups**, and **Instance IAM role settings**

Step 5: Choose **Proceed with no IAM role** under the **Instance IAM role** section
![EC2](/images/4.restore/4.jpg)

Step 6: Under the **Restore section** section, choose **Default role**
+ Ignore **Advanced settings** accept the defaults and click **Restore backup** button
![EC2](/images/4.restore/5.jpg)

Step 7: Check for your restored backup job under **Restore jobs** in the the **AWS Backup console**
![EC2](/images/4.restore/6.jpg)

Step 8: Navigate to the **Amazon EC2 console** and select **Instances** in the left navigation pane to see the restored EC2 instance
![EC2](/images/4.restore/7.jpg)

