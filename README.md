## AWS Questions
### 1. What the relationship between an instance and AMI is?

An `Amazon Machine Image (AMI)` is a special type of virtual appliance that is used to create a virtual machine within the Amazon Elastic Compute Cloud. It serves as the basic unit of deployment for services delivered using EC2.

while an `Instance` typically symbolizes the hardware of the host computer. Each instance type offers different computing and memory capabilities. 

From a single AMI, many instances can be launched.

### 2. What does an AMI include?

An AMI includes the following:

- One or more EBS snapshots, or, for instance-store-backed AMIs, a template for the root volume of the instance (for example, an operating system, an application server, and applications).

- Launch permissions that control which AWS accounts can use the AMI to launch instances.

- A block device mapping that specifies the volumes to attach to the instance when it's launched.

### 3. What the difference between Amazon S3 and EC2 is?

Amazon EC2 is a service for accessing cloud-based servers, while Amazon S3 is a storage service.
S3 buckets can be used as a storage location for backing up data from inside EC2 instances. S3 can also be accessed from multiple EC2 instances.

### 4. How many buckets can you create in AWS by default?
### 5. What is Buffer in Amazon web services?
### 6. What are the storage class available in Amazon S3?
### 7. What is the importance of buffer in Amazon Web Services?
### 8. When should you use the classic load balancer and the application load balancer?
### 9. Can you change the instance type of the instances that are running in your application tier and are also using autoscaling? If yes, then how?
### 10. Any advantages and disadvantages when do autoscaling on running instance especially on production instance?
### 11. What do you do to secure your data in Cloud?
### 12. Explain Stopping, Starting, and Terminating an Amazon EC2 instanc## e.
### 13. Define regions and availability zones in Amazon EC2
### 14. Is it important to select suitable zones for AWS services? What's the benefits of it?
### 15. What are the challenges in microservices debugging and troubleshooting?