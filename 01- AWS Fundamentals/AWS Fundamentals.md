# AWS Fundamentals

## AWS Global Infrastructure

**Region**: a region is simply a geographical location like London, Mumbai, North Virginia etc.
**Availability Zone**: an availability zone is one or more data centers situated closely (within 100 km) to each other in a single region.

- Each region has at least 2 availability zones.
- Availability zones has redundant power, networking, and connectivity

**Edge Locations**: edge locations are end points for AWS that are used for caching content. There are more edge locations than regions.


## Responsibilities in the Cloud

- AWS is responsible for security **OF** the cloud such as physical security of their DCs, Edge locations, regions, all hardware of the utilized by the AWS cloud, and the software that functions the stack such as hypervisors.
- You are responsible for security **IN** the cloud. You are responsible for the security of the data you store in the cloud, the software (applications, and OSes) you run on top of the cloud etc.
- Encryption is a shared responsibility.

## AWS Well-Architected Framework 

- Consists of 5 pillars: **operational excellence**, **security**, **reliability**, **performance efficiency**, **cost optimization**