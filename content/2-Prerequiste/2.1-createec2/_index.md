---
title : "Preparing EC2"
date :  "2025-06-13" 
weight : 1
chapter : false
pre : " <b> 2.1 </b> "
---

### Introduce

**Amazon Elastic Compute Cloud (Amazon EC2)**  is a virtual server rental service provided by Amazon Web Services (AWS), allowing you to run applications, websites, or backend systems in a flexible and scalable way

### Why Amazon EC2?

**Amazon Elastic Compute Cloud (Amazon EC2)** offers the broadest and deepest compute platform, with over 750 instances and choice of the latest processor, storage, networking, operating system, and purchase model to help you best match the needs of your workload. We are the first major cloud provider that supports Intel, AMD, and Arm processors, the only cloud with on-demand EC2 Mac instances, and the only cloud with 400 Gbps Ethernet networking. We offer the best price performance for machine learning training, as well as the lowest cost per inference instances in the cloud. More SAP, high performance computing (HPC), ML, and Windows workloads run on AWS than any other cloud

### Advantages
- **High flexibility and customizationt**: Dozens of instance types, operating systems, and options for storage and networking allow you to design the most suitable environment for your applications
- **Auto Scaling capability**: EC2 supports auto-scaling to automatically increase or decrease the number of instances based on actual demand, optimizing both performance and cost
- **High availability and fast failure recovery**: The ability to deploy across multiple Availability Zones helps minimize risks in case one zone experiences issues
- **Deep integration with the AWS ecosystem**: Easily connects with services like S3, RDS, ELB, IAM, CloudWatch… to build a comprehensive end-to-end system
- **Flexible payment models**: Multiple pricing options (On-Demand, Reserved Instances, Spot) help optimize your budget

### Disadvantages
- **Costs may be unpredictable and potentially high**: The complex pricing model (based on usage time, bandwidth, storage, etc.) can lead to unexpected expenses if not well-managed
- **Requires technical expertise**: Setting up networking, security, backup, and scaling requires a certain level of skill, especially for new users
- **Resource limits per region**: ach EC2 region has limitations on the number of instances — you may need to request a quota increase if necessary
- **Management overhead**: EC2 is an IaaS solution — meaning you are responsible for the entire instance lifecycle including patching, backups, and system updates
- **Startup time for instances**: Starting up an EC2 instance takes several minutes, making it less suitable for ultra-low-latency tasks
- **Dependent on network and geographic location**: Performance and latency depend on the quality and stability of your internet connection and the region you deploy in

### Summary

| Advantages| 		Disadvantages |
|---|---|
|  Flexible configuration options| 	Costs are often unpredictable |
| Auto scaling according to demand  | Requires technical knowledge  |
|  High availability and fault tolerance |  Resource limits by region|
|  Strong integration with AWS ecosystem | 	Requires self-management  |
| Variety of pricing models | 	Slow startup time|


{{% notice note %}}
Here is a reference website you can check:
{{% /notice %}}

- [AWS EC2](https://aws.amazon.com/ec2/)