[Back to Syllabus](./README.md#course-syllabus)

## Compute Introduction

- Virtual Machines , Bare Metal server or Dedicated Host
    - Scalability
    - high performance
    - Low pricing

- Flexible Shapes for CPU or RAM
    - Right Machine Type

- Virtual machine as shared and multi-tenant
    - AMD, Intel and ARM processors
    - Pay for What you use
    - Preemptible VMs
        - Low cost
        - Short lived VMs
        - Batch Jobs
        - Fault tolerant workloads
        - 50% cheaper

## Instance Basics

- VNIC is virtualized
- The instance have a boot volume on a remote storage
- Can have other disks as data volume

## Scaling

- Vertical Scaling
    - Scale up and down
    - New shape have same hardware
    - Stop instance before resizing
    - Downtime required
- Horizontal Scaling
    - Autoscaling: more VMs identical
    - Scale in and out
    - Large scale deployment
    - Indipendent VMs
    - Match traffic demand automatically
    - No extra cost in autoscaling

    - Create template of running instance
    - Create instance pool
    - Scaling rule

## OS Management Service

- Automate the OS patch managements
- Patch management:
    - Fix bugs
    - Improve performance
    - Add features

- Package management:
    - Installing and patching software

- OSMS automate Patch management
- OSMS simplified package management
- Search common vulnerabilities and exposures lookup

## Hands-On Activity: Compute
A pdf with an exercise to practicing with compute

[Go to Next Module](./7_Storage.md)