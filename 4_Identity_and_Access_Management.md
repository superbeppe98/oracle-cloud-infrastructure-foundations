[Back to Syllabus](./README.md#course-syllabus)

## IAM Introduction
- IAM = Identity and Access Management Service
- Fine-grained Access Control
    - AuthN - Who are you?
    - AuthZ - What permission do you have?

- Identity Domains
    - Container for user and groups
    - Policies for tenancy or resources

- Resources: all things that you can provide in Cloud
    - OCID: Unique identifier with a specific sintax

## Compartments

- Tenancy and root compartment
    - Collection of related resources
    - Isolate and controll access for every compartment
    - Root have all resources displayed
    - Resources can talk to each other in other compartments
    - Resources can be moved to various compartments
    - Can be nested with a max of 6 level of hierarchy
    - Set quotas and budgets

## AuthN and AuthZ

- Principals: IAM entities taht can interact with OCI Resources
    - IAM Users
    - Resource Principals
    - Groups: collection of user

- AuthN:
    - Username, password
    - API Signing Key
    - Auth Tokens

- AuthZ:
    - IAM Policies

## Tenancy Setup
- Tenancy Admin
- OCI Admin: Set of users
    - OCI-admin-group with OCI Admin with they own policies on a compartment

[Go to Next Module](./5_Networking.md)