---
title : "Clean up resources"
date :  "2025-06-13" 
weight : 5 
chapter : false
pre : " <b> 5. </b> "
---

The following steps to delete the resources we created 

#### Delete EC2 Instances

1. Go to EC2 service management console
   + Step 1: Click **Instances**
   + Step 2: Select both **EC2 Backup Lab** and restored **EC2 Backup Lab** instances
   + Step 3: Click **Instance state**
   + Step 4: Click **Terminate instance**, then click **Terminate** to confirm
![EC2](/images/5.clear/1.jpg)

#### Delete the AWS Backup recovery point
1.  Go to AWS Backup Console
   + Step 1: Step 1: Click **Vaults**
   + Step 2: Click **Default** vault
   + Step 3: Choose the **Recovery point**
   + Step 4: Click **Actions**, then click **delete**
![EC2](/images/5.clear/2.jpg)

#### Delete the AWS Bacup Plans
1. Go to AWS Backup Console
   + Step 1: Step 1: Click **Backup plans**
   + Step 2: Click the **EC2-backup-plan** Backup plan name
   + Step 3: Choose **EC2-resources** under the **Resource assignments** section
   + Step 4: Click **Delete**
![EC2](/images/5.clear/3.jpg)
