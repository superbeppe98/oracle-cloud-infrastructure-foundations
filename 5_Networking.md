[Back to Syllabus](./README.md#course-syllabus)

## VNC Introduction

- VCN:Virtual Cloud Network
    - Private Network
    - Secure Communication
    - Lives in OCI Region
    - Highly Avaiable
    - Scalable

- VNC Address Space
    - 10.0.0.0/16
    - Different subnet (also private and public subnet)
    - 1.0 -> Public subnet
    - 2.0 -> Private subnet

- Communication from Internet
    - Internet Gateway
    - Nat Gateway (Unidirection traffic to Internet)
    - Service Gateway

- Communication on-premises
    - Dynamic Routing Gateway
    - Site-to-Site VPN
    - FastConnect

## VCN Routing

- Route Table: with rules you can route your data
    - Local Peering in same region
    - Remote Peering in different region
    - Dynamic Routing Gateway v2 (up to 300 VNC in a single DRG)

## VNC Security

- Security List:
    - Firewall rules (Stateful or stateless)
    - Network Security Group (NSG)

## Load Balancer

- Scalability
- Proxy connections
- Load balancer use Layer 7 but Network load balancer use Layer 4


[Go to Next Module](./6_Compute.md)