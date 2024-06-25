---
title : "Amazon VPC"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---
## Step 1: Create VPC
* To get started, navigate to the Your VPCs tab  in the VPC section of the console and click Create VPC button.

![img.png](/images/2.fundamentals/2.1/img.png)

## Step 2:
* Enter `VPC A` as the Name tag
* Specify `10.0.0.0/16` as IPv4 CIDR block.
* Do not enable IPv6.
* Leave `Default` selected as `Tenancy`.
* Accept proposed Tags
* Click `Create VPC`

![img.png](/images/2.fundamentals/2.1/step2.png)

## Step 3: After completing these steps, you should have a new VPC listed under Your VPCs
![img.png](/images/2.fundamentals/2.1/step3.png)

## Step 4: Click on **Actions** and select **Edit VPC** settings from the dropdown
![img.png](/images/2.fundamentals/2.1/step4.png)
* Check 2 box like image then save 

![img.png](/images/2.fundamentals/2.1/step4.1.png)

Every thing is done!\
**Congratulations, your first VPC is now built**