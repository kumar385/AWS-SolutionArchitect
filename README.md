# AWS-SolutionArchitect
This is AWS Solution Architect notes
# S3 : Simple Storage Service
S3 is object storage built to store and retrieve any amount of data from anywhere. It is designed to deliver 11 9's durability.

## S3 Facts: 
* One of the oldest AWS services
* Incredibly widely used
* Filing cabinet of the internet

## S3 Object:
* Object is a file
* Arbitrary collection of bytes
* S3 i key-value store
* Subresources
 -- Access Control Lists

## S3 Fundamentals:
* Object-based storage
* Durability through data being spread across devices and facilities
* File size from 0 to 5TB 
* Unlimited storage per account
* Files are stored in buckets
* S3 has flat (universal) namespace - bucket names must be unique across all AWS accounts
* Accessible via URL:
 -- https://<region>.amazonaws.com/<bucketname>
 -- Successful file upload returns HTTP 200 code
  
## S3 Data Consistency
* Object copies are placed across a number of devices and facilities for durability
* Object consistency therefore important
* Read after write consistency for new object PUT
* Eventual consistency for overwrite object PUT and DELETE - propogation time for change
