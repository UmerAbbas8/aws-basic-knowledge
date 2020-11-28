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

By default, you can create up to 100 buckets in each of your AWS accounts. If you need additional buckets, you can increase your account bucket limit to a maximum of 1,000 buckets by submitting a service limit increase.

### 5. What is Buffer in Amazon web services?

Buffer helps to synchronize different components, which gets requests and processes it in an unsynchronized way. It manages the balance between various components in order to maintain the speed and provide a faster service. In AWS buffer also ensures efficiency over traffic or load.

### 6. What are the storage class available in Amazon S3?

Amazon S3 offers a range of storage classes designed for different use cases. These include S3 Standard for general-purpose storage of frequently accessed data; S3 Intelligent-Tiering for data with unknown or changing access patterns; S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA) for long-lived, but less frequently accessed data; and Amazon S3 Glacier (S3 Glacier) and Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive) for long-term archive and digital preservation; and S3 Outposts for on-premises object storage to meet data residency needs. You can learn more about these storage classes on the [Amazon S3 Storage Classes page](https://aws.amazon.com/s3/storage-classes/).

### 7. What is the importance of buffer in Amazon Web Services?

An Elastic Load Balancer ensures that the incoming traffic is distributed optimally across various AWS instances. A buffer will synchronize different components and makes the arrangement additional elastic to a burst of load or traffic. The components are prone to work in an unstable way of receiving and processing the requests. The buffer creates the equilibrium linking various apparatus and crafts them effort at the identical rate to supply more rapid services.

### 8. When should you use the classic load balancer and the application load balancer?



### 9. Can you change the instance type of the instances that are running in your application tier and are also using autoscaling? If yes, then how?


### 10. Any advantages and disadvantages when do autoscaling on running instance especially on production instance?
### 11. What do you do to secure your data in Cloud?
### 12. Explain Stopping, Starting, and Terminating an Amazon EC2 instanc## e.
### 13. Define regions and availability zones in Amazon EC2
### 14. Is it important to select suitable zones for AWS services? What's the benefits of it?
### 15. What are the challenges in microservices debugging and troubleshooting?