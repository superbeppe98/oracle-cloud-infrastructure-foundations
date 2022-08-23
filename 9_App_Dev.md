[Back to Syllabus](./README.md#course-syllabus)

##  Developer Services Overview

- Cloud-Native: constructed on the cloud
    - Containers
        - Packaging app
        - Portable
    - Microservices
        - Split your task in various services
    - Service Meshes
        -
    - Immutable Infrastructure
    - Declarative APIs
    
    - Resilient
    - Manageable
    - Observable

- Cloud-Enabled: use in a conventional data center
- Cloud-Based: a middle ground between the two

- Containers & Artifacts
- Functions
- API Management
- DevOps
- Resource Manager
- Developer Resources

## Oracle Container Engine for Kubernetes (OKE)

- VMs vs Containers
    - VM don't share the libraries but all the OS
    - Container share only lib and runtime

    - VM have multiple VM, Os and use much space and longer boot time
    - Container boot faster, lightweight and portable

- Container have orchestration
    - Kubernets is an open source platform
    - any scale containers
    - self-heal
    - auto-scale
    - simplifies deployment

- OKE
    - K8s service
    - Based on open source system
    - Support for ARM and GPU instances
    - CLI/API Support
    - Benefits of orchestration

## Oracle Container Registry (OCIR)

- Docker v2 container registry service
- Private or public repositories
- Solve the maintanance of Docker images
- Enforce access rights for images
- Easy find the right images for a project

- Repositories
    - A collection of images uniquely identified

## OCI DevOps Service

- DevOps is a combination from developer and operations
- Continuous Integration (CI)
    - Planned
    - Built
    - Tested
    - Revised
- Continuous Deployment (CD)
    - Manual or Automatic

- is a CI/CD Platform for Developers    
- Automates delivery
- Release code much faster

- CI has Build Pipeline
- CD has Deployment Pipeline

## API Gateway

- Restful APIs
    - Different languages for client and server
    - Uses HTTP Verbs
    - Stateless

- APi Gateway is responsible for talk with every backend API
    - Enforce Auth
    - SLA Metrics
    - Alarms and logging
    - rate-limiting and routing
    - Custom domains
    - Header/Query Transformation
    - Support OpenAPI 2 and 3

- Similar to a load balancer

## Functions

- Faas: Functions as a service
    - Event Driven Architecture
    - Container Native
    - Autonomous

- More abstractions
- Pay as you go to pay per use pricing

- Push container to registry
- Configure function trigger
- Code run only when triggered
- Pay for code execution

- Function triggers with Direct Invoke API or OCI Events
- Function Integration like monitoring and logging

## Resource Manager

- Infrastructure as Code
    - Install, configure and manage resource

- Benefits
    - Improves team collaboration
    - Enables automation
    - Seamless integration with OCI platform
    - Provides a console UI experience

## OCI Developer Services Case Study

- Case study overview for an hotel

## Hands-On Activity: Resource Manager
A pdf with an exercise to practicing with resource manager

[Go to Next Module](./10_Observability_and_Management.md)