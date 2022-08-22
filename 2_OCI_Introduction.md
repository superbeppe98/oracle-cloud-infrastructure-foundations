[Back to Syllabus](./README.md#course-syllabus)

## OCI Architecture
- Divided in 3 parts:
    - Regions
    - Availability Domains (AD)
    - Fault Domains (FD)

![image](https://user-images.githubusercontent.com/29455975/185917416-4f30b2cf-c146-43b8-9363-872cb4f23153.png)

- Regions
    - Location: closest to you for lowest latency and highest performance
    - Data Residency & Compliance: Every countries have data residency requirements
    - Service Availability: Depends on regional demand and other factors

- Availability Domains
    - Isolated from each other, difficoult to fail simultaneously
    - Physical infrastructure not shared

- Fault Domains
    - Each Availability Domains has three Fault Domains
    - Logical data center within an AD
    - They don't share single points of hardware failure
    - Possibilites to change instances to fault domains at instance "launch" time
    - Avoid single points of failure:
        - In different fault domains
        - In different availability domains for multiple AD regions
        - In different fault domains in one AD region

[Go to Next Module](./3_Oracle_Cloud_Free_Tier_Account.md)