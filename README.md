# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**

## Problem 1:Encryption Time Calculation
A company uses AES-256 encryption to secure its data before uploading it to the cloud. It takes 0.05 seconds to encrypt 1 MB of data.

Q: How long will it take to encrypt 2 TB of data before upload?

Encryption time = 0.05 seconds per 1 MB

 Data size = 2 TB = 2 × 1024 GB = 2048 GB = 2048 × 1024 MB = 2,097,152 MB
 
Total Time = 2,097,152 MB × 0.05 seconds/MB
           = 104,857.6 seconds
           
104,857.6 seconds ÷ 3600 ≈ 29.13 hours

It will take approximately 29.13 hours to encrypt 2 TB of data before upload.


## Problem 2:CPU Utilization Efficiency
A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average.

Q: What is the CPU utilization efficiency?

Given:

•	Allocated vCPUs: 8

•	Average used vCPUs: 5.5

CPU Utilization Efficiency Formula:

EFFICIENCY(%)=(used vCPUs/allocated vCPUs)*100

Efficiency=(5.5/8)*100=68.75

CPU Utilization Efficiency is 68.75%


## Problem 3: Network Throughput Efficiency

A cloud server has a maximum bandwidth of 1 Gbps, but during peak hours it only uses 600 Mbps.

Q: What is the network throughput efficiency?

Given:
•	Maximum Bandwidth: 1 Gbps

•	Actual Usage (Peak Hours): 600 Mbps

Network Throughput Efficiency Formula:

EFFICIENCY(%)=(Actual throughput/maximum bandwidth)*100

Efficiency=(600/1000)*100=60%

Network Throughput Efficiency is 60%

 ## Problem 4:Energy Efficiency
Two cloud setups process the same workload:

•	Setup A uses 500W for 2 hours.

•	Setup B uses 300W for 3.5 hours.

Q: Which setup is more energy-efficient

To compare energy efficiency, we need to calculate total energy consumed (in watt-hours) for each setup.

 Step 1: Energy Consumption Formula
 
Energy (Wh)=Power (W)×Time (h) 

Setup A:

500W×2 hours=1000 Wh500W 

Setup B:

300W×3.5 hours=1050 

 Conclusion:
 
•	Setup A consumes 1000 Wh

•	Setup B consumes 1050 Wh

Result:

 Setup A is more energy-efficient, as it consumes 50 Wh less than Setup B for the same workload.
 
## Problem 5: CPU Utilization Efficiency
A physical server has 16 cores and each VM uses 2 cores. CPU utilization is optimal at 75%.

Q: What is the maximum number of VMs that can be efficiently hosted?

 Given:
 
•	Total physical cores: 16

•	Each VM uses: 2 cores

•	Optimal CPU utilization: 75%

 Step 1: Calculate usable cores at 75% efficiency
 
16 cores×0.75=12 usable cores16 

 Step 2: Calculate max number of VMs
 
Max VMs=12 cores/2 cores per VM=6 VMs 

 Maximum number of VMs that can be efficiently hosted is 6






