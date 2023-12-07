# Cloud-computing
- Cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence-over the Internet ("the cloud") to offer faster innovation, flexible resources, and economies of scale

# Hyperscalars  :
A hyperscaler is a type of large-scale data center that offers massive computing resources, typically in the form of an elastic cloud platform. Organizations use them to deploy and manage large-scale applications and services.



# Cloud Computing
- • On-Demand delivery
- • Pay-as-you-go model
- • Provision only the size you need (exactly right type and size)
- • Access resources instantly


- ## Benefits
- • Faster time to market
- • Scalability and flexibility
- - Horizontal scaling involves adding more machines or nodes to a system, while vertical scaling involves adding more power (CPU, RAM, storage, etc.) to an existing machine![image](https://github.com/Rudrakshrawal/Cloud-computing/assets/144530387/fedab9a2-767c-453f-bdc1-8acd27dcbf87)
  - Soft Limits or Quotas - AWS allows users to set service-specific limits, also known as soft limits or quotas, on various resources such as EC2 instances, EBS volumes, or other services.

These soft limits are preconfigured limits on how much of a particular resource you can use within your AWS account. They are set by default to prevent accidental overuse of resources, which could potentially lead to unexpected charges or performance issues.


# Advantages
- • Cost savings
- • Better collaboration
- • Advanced security
- • Data loss prevention


- # Disadvantages
-  • risk of vendor lock-in
-  • less control over underlying cloud infrastructure
-  • concerns about security risks like data privacy and online threats
-  • integration complexity with existing systems
-  • unforeseen costs and unexpected expenses


# Public And Private cloud
- <img width="800" alt="Screenshot 2023-11-29 at 1 58 22 AM" src="https://github.com/Rudrakshrawal/Cloud-computing/assets/144530387/8dc6c05e-6aea-41ff-8d44-b09fc7d15587">
 # Hybrid cloud 
 - A hybrid cloud is a mixed computing environment where applications are run using a combination of computing, storage, and services in different environments ![image](https://github.com/Rudrakshrawal/Cloud-computing/assets/144530387/7eb094a6-917a-4266-9377-a5f2dcad622c) (During big billions sale flipkart can add the extra load on the public cloud and the usual load on the private cloud representing a use cse of hybrid cloud)

# Cloud Service Model
• laaS
• PaaS
• SaaS
<img width="750" alt="Screenshot 2023-11-29 at 2 17 07 AM" src="https://github.com/Rudrakshrawal/Cloud-computing/assets/144530387/088d2936-e0e6-4b96-93ab-5a7930e0e4db">

# Compute Services
- • Elastic Compute Cloud - EC2
- • ECS / EKS - Containerized Services
- • Lambda - Serverless(refers to a way of building and running applications without needing to manage the underlying servers. Instead, developers focus solely on writing and deploying code, rest is done by cloud provider.)

# Storage Services
- • Simple Storage Service - S3
- • Elastic Block Store - EBS
- • Elastic File System - EFS
- • Archival Service - Glacier
-  **(Object storage stores and manages all data in an unstructured format and in units called objects. Block storage takes any data, like a file or database entry, and divides it into blocks of equal sizes. It then stores the data block on underlying physical storage in a way that's optimized for fast access and retrieval.)**

# Network Services
- • Virtual Private Cloud - VPC
- • Domain Name Service - Route 53
- • Direct Connect
# Braket
- For quantum computing
# AMAZON SNS 
- **Simple Notification Services**
- A notification service provided as part of Amazon Web Services since 2010. It provides a service for sending messages.
-------------
# CODE PIPEPLINE ;
-  ### ***AWS CodePipeline is a continuous delivery service you can use to model, visualize, and automate the steps required to release your software. You can quickly model and configure the different stages of a software release process. CodePipeline automates the steps required to release your software changes continuously***
- -  # CODE BUILD
- - -  AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces ready-to-deploy software packages.
- - # CODE DEPLOY
- - - It is a deploy tool. This tool ensures that the code changes are reached and applied to the required locations with 0 downtime.
    - # CODE COMMIT
    - - Nothing but SCM(Source code management tool)used to track modifications to a source code repository. SCM tracks a running history of changes to a code base and helps resolve conflicts when merging updates from multiple contributors[Managed service of GIT
    - # CODE DELIVERY
    - -
# AMAZON POLY
- converts text into spoken audio. It allows developers to create speech-enabled applications and products.
# AMAZON LEX
- Converts speech to text




----------

## S3
- • Object Storage with durability of 99.999999999%, 11 9's
- - • Infinitely scaling storage
- - • Can keep files in buckets
- - • S3 is a global service but buckets are created in specific regions
- - • Globally unique bucket names
***Durability - 11 9's durability = If 10,000,000 objects stored, average incurred loss of a single object*
*once every 10,000 years*
*53 standard has 99.99% availability = not available 53 minutes a year*

 
- • Security
- - • User based - IAM policies
- - • Resource based
- - - • Bucket Policies
- - - • Bucket ACLs
- - - • Object ACLs
- • Public vs Private accessible Buckets
- • Object versioning
- • State-of-the-art in-transit and at-rest encryption 


- Storage Classes
- - • Amazon S3 Standard - General Purpose---- Costliest one but also the most preffered one
- - • Amazon S3 Standard-Infrequent Access (IA)----The durabilty is 99.99% and not 11 9's
- - • Amazon S3 One Zone-Infrequent Access
- - • Amazon S3 Glacier Instant Retrieval----For those people who are accessing the data once in a quarter
- - • Amazon S3 Glacier Flexible Retrieval----If someone is accessing it more frequently
- - • Amazon S3 Glacier Deep Archive----If the data is surely not to be opened but only unnder very very important and existential circumstances
- - • Amazon 53 Intelligent Tiering----- TAo intelligently tell the AWS to keep the data of a certain period and remove the other and etc.
-----------------------





# EC2 INSTANCES TYPE
***Instance store** is ideal for temporary storage of information that changes frequently, such as buffers, caches, scratch data, and other temporary content.*
<img width="561" alt="Screenshot 2023-12-07 at 12 52 31 PM" src="https://github.com/Rudrakshrawal/Cloud-computing/assets/144530387/004314c8-995c-471d-9bda-8ef9936fd015">
- C type instances are cpu intensive
- M type are general purpose instances. Balanced memory and cpu.
- R type have more ram
- T type instances should be used if we have to use them in optimised way ie. if you have to use all the 4 cores provided to you ,they can be accessed at a very nominal price and if not in use , the 3 cores will be rent out to someone else.
- D type have huge instance store.
- I type have the fastest IOPS provider.

- micro - 1cpu core and 1 gb ram only and some levelv of network



- • On-Demand Instances - short workload, predictable pricing, pay by second
- • Reserved (1 & 3 years)
- • Reserved Instances - commitment to an amount of usage, long workload, 1
- • 3 years uptront commitment, can save up to 72% on billing.
- • Spot Instances - short workloads, cheap, can lose instances (less reliable)
- • Dedicated Hosts - book an entire physical server, control instance placement, most expensive EC2, use case - BYOL, compliance or regulations
- • Dedicated Instances - no other customers will share your hardware

# ELB (Elastic Load Balancers)
- • Implementation of Horizontal Scaling
- • Required for High Availability
- • Types of Load Balancer
- - • Classic Load Balancer - Layer 4 & 7
- - • Application Load Balancer - Layer 7
- - • Network Load Balancer - Layer 4

# Reverse Proxy-
a server that sits in front of web servers and forwards client (e.g. web browser) requests to those web servers. Reverse proxies are typically implemented to help increase security, performance, and reliability.

