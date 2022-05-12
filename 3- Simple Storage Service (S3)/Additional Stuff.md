**Cached Volume Gateway** 
- data is primarily stored in AWS S3 but frequently accessed data exists as a copy locally in your datacenter. 
- Can take snapshots (incremental) of S3 buckets for backup. 
- All gateway data and buckets are encrypted using SSE
- can't access S3 data using AWS CLI or AWS S3 management console

**Stored Volume Gateway**
- entire data-set is stored primarily on-premise
- you only store periodic point-in-time backups of data in S3
- the on-premise dataset provides low-latency

**File Gateway**
- presents a file interface
- you can store files as objects in S3 using standard NFS and SMB file protocols
- you can access these files via the same protocols from your DC or EC2 instances as files.
- can access the files as objects from the AWS CLI
- 