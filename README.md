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

Amazon S3 offers a range of storage classes designed for different use cases. These include S3 Standard for general-purpose storage of frequently accessed data; S3 Intelligent-Tiering for data with unknown or changing access patterns; S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA) for long-lived, but less frequently accessed data; and Amazon S3 Glacier (S3 Glacier) and Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive) for long-term archive and digital preservation; and S3 Outposts for on-premises object storage to meet data residency needs. More about these storage classes on the [Amazon S3 Storage Classes page](https://aws.amazon.com/s3/storage-classes/).

### 7. What is the importance of buffer in Amazon Web Services?

An Elastic Load Balancer ensures that the incoming traffic is distributed optimally across various AWS instances. A buffer will synchronize different components and makes the arrangement additional elastic to a burst of load or traffic. The components are prone to work in an unstable way of receiving and processing the requests. The buffer creates the equilibrium linking various apparatus and crafts them effort at the identical rate to supply more rapid services.

### 8. When should you use the classic load balancer and the application load balancer?

The Classic Load Balancer operates on both the request and connection levels. However, it doesn't support features like host and path based routing. This is the first load balancer that AWS introduced in 2009 so it is missing some features. The Application Load Balancer was introduced to address this. A Classic Load Balancer is recommended only for EC2 Classic instances.

Where as the Application Load Balancer operates at the request level only. If you're dealing with HTTP requests, which you are for your web application, you can use this. It supports the basic feature of distributing requests using the round robin algorithm. It also supports advanced features like host and path based routing.

### 9. Can you change the instance type of the instances that are running in your application tier and are also using autoscaling? If yes, then how?

yes, You would need to create a new launch config specifying the new instance type and associate that with your autoscaling group - removing the current launch config. Over time the EC2s with the previous instance type will be terminated (assuming the default termination rules apply) and the new instance types will be launched when the auto scaling group scales out.

### 10. Any advantages and disadvantages when do autoscaling on running instance especially on production instance?

Autoscaling has many advantages on running instance while in production is always an advantage provided if it's configured properly.

Only disadvantage will be poorly configured auto scaling that could lead to cost alot of money for the company.

### 11. What do you do to secure your data in Cloud?

1. Choose your cloud provider with care (Use cloud services that encrypt your data)
2. Encrypt the data before uploading to the cloud
3. Ask about provider’s processes in case of a breach
4. Utilize file-level encryption
5. Institute password best practices
6. Implement two-factor authentication
7. Transfer data securely
8. Back up data consistently
9. Understand recovery options
10. User error (Educate employees)

### 12. Explain Stopping, Starting, and Terminating an Amazon EC2 instance.
### 13. Define regions and availability zones in Amazon EC2
### 14. Is it important to select suitable zones for AWS services? What's the benefits of it?
### 15. What are the challenges in microservices debugging and troubleshooting?