[Back to Syllabus](./README.md#course-syllabus)

## Storage Introduction

- Persistente vs non-persistent
- Type of file
- Performance
- Durability
- Connectivity
- Protocol

- Local NVMe: local attached storage
- Block Volume: storage to a remote server in fixes size block
- File Storage: shared file services similar to block volume in file and directories
- Object Storage: any kind of file for web server

- Data Migration Services
    - Data Transfer Disk
    - Data Transfer appliance
    - Storage gateway

## Object Storage

- Internet scale storage platform
- Data managed as objects
- Unstructured data
- Multiple storage tiers
- Private access from OCI resources
- Advanced capabilities

- Scenarios:
    - Content Repository
    - Unstructured data
    - Big data or Backup

- Object are key-value pairs
    - have metadata
    - stored in bucket
    - bucket have unique name and flat hierarchy

- Namespace have global unique name for all your buckets space.
- Usable throught API endpoint

- Object Storage Tiers
    - Standard Tier
        - Fast immediate access to data
    - Infrequent Access
        - Infrequent access
    - Archive Tier
        - Rarely access

- Auto-Tiering
    - Move data between Tier

- Life-Cycle management
- Versioning
- Data encryption

## Block volume

- Persistent and durable storage
- Create and attach disks
- Detach and delete disks
- Retain disks after instance deletion

- Block Volume Tiers
    - Basic
    - Balanced
    - Higher performance
    - Ultra Higher Performance
 - IOPS per GB

- Auto-Tune Performance
- Encrypted Block Volumes
- BYOK
- In-Transit Encryption
- Read/write Shareable (VMs talk to one disks)
- Resizing Block Volumes online and offline
- Replication of Block Volumes across regions
    - Disaster Recovery
    - Migration
    - Business Expansion
    - Asynchronous replication
- Volume groups
    - Backups across volume and instances

## File Storage

- Collections of documents organized into named directories

- Use cases:
    - EBS
    - General purpose file systems
    - Micro services and containers
    - Scale out apps
    - Analitycs

- Support NFS v3
- Snapshots
- Security

## Migration Services

- Offline and Online Migration
- Data Transfer disk
- Data Transfer Appliance throught a Site

- Storage Gateway Service
    - Docker image
    - NFS mount point on clients
    - Connect to a OCI Object Storage

[Go to Next Module](./8_Database.md)