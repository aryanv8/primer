[🔙  Back to Menu](./)

<h1 style="color:teal;text-align:center;border-bottom:1px solid teal"> AWS Quiz </h1>

## AWS Resource for Tech Support Post ✅

### Question 1
Which of the following is a serverless computing?
- Amazon EC2
- Amazon EKS
- Amazon ECS
- ***Amazon Lambda***
**Explanation:** Amazon Lambda is a serverless computing service provided by AWS that runs code in response to events and automatically manages the underlying compute resources. It allows developers to execute code without provisioning or managing servers.

### Question 2
Which is the AWS service used for configuring Content Delivery Network(CDN)?
- Amazon CloudFront
- Amazon CDN
- Amazon ElastiCache
- Amazon CloudFormation
- ***Amazon CloudFront***
**Explanation:** Amazon CloudFront is a content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds. It integrates with other AWS services to provide a seamless experience.

### Question 3
Choose the infrastructure automation service from the given list?
- Amazon ElastiCache
- ***Amazon CloudFormation***
- Amazon CloudFront
- Amazon EC2
**Explanation:** Amazon CloudFormation is an infrastructure automation service that enables you to define and provision AWS infrastructure resources using templates. It helps automate the setup and configuration of resources, making it easier to manage and deploy applications.

### Question 4
Which AWS service used for enabling asynchronous communication between services.
- ***SQS***
- STS
- SES
- SNS
**Explanation:** Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables asynchronous communication between distributed systems, decoupling components of an application to ensure they run independently and efficiently.

### Question 5
Which of the following provides shared storage for Linux workloads
- S3
- ***EFS***
- FSX
- EBS
**Explanation:** Amazon Elastic File System (EFS) provides scalable file storage for use with Amazon EC2 instances in the AWS Cloud. It is designed to be highly available and durable, making it suitable for Linux workloads that require shared access to a file system.

### Question 6
\__________ is a serverless container orchestration service
- ECS
- ECR
- EKS
- ***Fargate***
**Explanation:** AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS). It eliminates the need to provision and manage servers, allowing users to focus on building and running applications.

### Question 7
Which of the following messaging services is based on pub/sub messaging model.
- ***SNS***
- STS
- SES
- SQS
**Explanation:** Amazon Simple Notification Service (SNS) is a fully managed messaging service that supports the pub/sub messaging model, allowing messages to be sent to multiple subscribers. It enables the decoupling of microservices, distributed systems, and serverless applications.

### Question 8
Which of the following load balancers support content based routing?
- ***Application Load Balancer***
- Classic Load Balancer
- All the options mentioned
- Network Load Balancer
**Explanation:** The Application Load Balancer (ALB) supports content-based routing, allowing you to route traffic based on the content of the request (such as host headers, paths, or HTTP methods). This makes it suitable for advanced routing and load balancing scenarios.

### Question 9
Which of the following database services support dynamic schema.
- ***Amazon DynamoDB***
- Amazon Aurora
- Amazon RDS
- Amazon ElastiCache
**Explanation:** Amazon DynamoDB is a fully managed NoSQL database service that supports dynamic schemas, allowing you to easily add or remove attributes from items in a table without affecting other items. This flexibility makes it ideal for applications with evolving data models.

### Question 10
Cloudwatch can monitor custom metrics in-addition to built-in metrics.
- ***True***
- False
**Explanation:** True. Amazon CloudWatch allows you to monitor custom metrics alongside built-in metrics, providing comprehensive monitoring and observability of your applications and infrastructure. You can publish your own application metrics and use CloudWatch to create alarms and visualizations based on these metrics.

## Security and Compliance - Pre ✅
### Question 1
AWS is responsible for protecting the Global infrastructure based on shared responsibility model .
Select one:
- ***True***
- False

**Explanation:** According to AWS's shared responsibility model, AWS is responsible for protecting the global infrastructure that runs all of the services offered in the AWS Cloud. This includes hardware, software, networking, and facilities that run AWS services.

### Question 2
The person or a workload who uses the AWS resources is known as _________
- Root user
- privileged user
- ***AWS user***
- Normal user

**Explanation:** An AWS user refers to any individual, system, or application that interacts with AWS resources. Users are authenticated entities that make requests to AWS services and are often managed through AWS Identity and Access Management (IAM).

### Question 3
To simplify the assignment of similar permission for many users, ______ is used.
- ***groups***
- organizational units
- resource management
- root account

**Explanation:** AWS IAM groups are collections of IAM users. By organizing users into groups, you can manage the permissions for multiple users simultaneously, making it easier to assign permissions to users who perform similar tasks.

### Question 4
Which of the below option is not a security best practice.
- Use roles for applications
- Remove unnecessary users and credentials
- ***Use AWS account root user for daily activities***
- Grant least privilege

**Explanation:** Using the AWS account root user for daily activities is not recommended as it poses security risks. Instead, AWS recommends using IAM users or roles with the minimum permissions necessary for performing tasks.

### Question 5
To organize and manage the AWS resources, _________ is used.
- Admistrative rights
- ***resource groups***
- organizational units
- resource management

**Explanation:** AWS resource groups are used to group AWS resources together based on criteria that you define (such as tags, region, resource types). This helps you organize and manage resources collectively, facilitating operations like applying policies or monitoring.

### Question 6
The method of authentication that enables the user to authenticate into multiple application with one set of credentials is __________
- authentication
- authorization
- multifactor authentication
- ***Single Sign on***

**Explanation:** Single Sign-On (SSO) is a method of authentication that allows a user to authenticate once and gain access to multiple applications without needing to re-enter credentials. It simplifies user management and improves user experience across applications.

### Question 7
Which of the following services are managed service
- ***Amazon RDS***
- Amazon EC2
- Amazon EBS
- ***Amazon S3***

**Explanation:** Managed services like Amazon RDS and Amazon S3 are fully managed by AWS, meaning AWS handles the infrastructure provisioning, maintenance, and scaling, allowing users to focus on using the service rather than managing it.

### Question 8
The addition layer of security along with the user credentials is __________
- Single Sign on
- ***multifactor authentication***
- authentication
- authorization

**Explanation:** Multifactor authentication (MFA) adds an additional layer of security to user logins by requiring two or more forms of authentication (factors) before granting access. This helps protect against unauthorized access even if credentials are compromised.

### Question 9
Which service used to control access to the services and resources.
- AWS Sheild
- Amazon KMS
- AWS WAF
- ***Amazon IAM***

**Explanation:** Amazon IAM (Identity and Access Management) is used to control access to AWS services and resources securely. It enables you to manage users, groups, roles, and their permissions in AWS.

### Question 10
Security in the cloud means customers are responsible for securing everything they deploy in the cloud
Select one:
- ***True***
- False

**Explanation:** True. In the cloud, the responsibility for security is shared between the cloud provider (AWS) and the customer. AWS secures the infrastructure, while customers are responsible for securing their data, applications, identities, and access management configurations.

## Security and Compliance - Post ✅
### Question 1
IAM policies can be attached to __________
- profile
- ***group***
- ***role***
- ***user***
**Explanation:** IAM policies can be attached to users, groups, and roles in AWS. This allows you to define permissions for these entities to control their access to AWS resources.

### Question 2
Which of the following entity allow a user to access AWS resources temporarily?
- IAM User
- IAM Policy
- IAM Access Keys
- ***IAM Role***
**Explanation:** An IAM Role allows users or services to access AWS resources temporarily. Roles provide temporary security credentials to access resources without needing to share long-term credentials.

### Question 3
Which AWS service provides access to security and compliance documents?
- AWS CloudHSM
- ***AWS Artifact***
- AWS Inspector
- AWS KMS
**Explanation:** AWS Artifact is a service that provides access to AWS’s security and compliance documents, including certifications and reports.

### Question 4
Which AWS service used for automated security assessments?
- ***AWS Inspector***
- AWS Shield
- AWS CloudHSM
- AWS KMS
**Explanation:** AWS Inspector is a security assessment service that helps improve the security and compliance of applications deployed on AWS by automatically assessing applications for vulnerabilities or deviations from best practices.

### Question 5
How to set max permission for a user?
- Permission Boundry
- Group
- Role
- Policy
- ***Permission Boundry***
**Explanation:** A Permission Boundary is an advanced feature for setting the maximum permissions that an IAM entity (user or role) can have. This provides an additional layer of security by limiting the permissions that can be granted to the entity.

### Question 6
AWS is responsible for protecting the Global infrastructure based on shared responsibility model.
Select one:
- ***True***
- False
**Explanation:** True. Under the AWS shared responsibility model, AWS is responsible for protecting the global infrastructure that runs all the services offered in the AWS Cloud. This includes hardware, software, networking, and facilities that run AWS services.

### Question 7
What is the primary purpose of AWS IAM?
- Scaling virtual machines
- Analyzing log data
- ***Controlling access to AWS resources***
- Managing database instances
**Explanation:** The primary purpose of AWS IAM (Identity and Access Management) is to control access to AWS resources. IAM enables you to manage access to AWS services and resources securely.

### Question 8
What is the benefit of using IAM roles for EC2 instances?
- Improved security by avoiding the use of roles
- Easier management of EC2 instances
- Automatic scaling of EC2 instances
- ***Secure access to AWS services without storing credentials***
**Explanation:** Using IAM roles for EC2 instances provides secure access to AWS services without needing to store credentials on the instance. This improves security by leveraging temporary security credentials.

### Question 9
Which of the following are best practices of IAM?
- ***Enable Multifactor authentication***
- ***Delete access keys of root user***
- Delete root user account
- Delete root user password.
**Explanation:** Best practices for IAM include enabling Multifactor Authentication (MFA) to add an extra layer of security, and deleting access keys for the root user to prevent misuse. It is also important to avoid using the root user for day-to-day activities.

### Question 10
Which AWS service protects applications running on AWS against DDoS attacks?
- ***AWS Shield***
- AWS IAM
- AWS Inspector
- AWS KMS
**Explanation:** AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. It provides automatic protections against common DDoS attacks.
