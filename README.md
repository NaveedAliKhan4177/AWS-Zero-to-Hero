Cloud Computing & AWS Fundamentals
Trainer's Reference Material | Beginner Level | Suggested duration: 90–120 minutes
 
Training purpose: Build a clear foundation in cloud computing, virtualization, public and private cloud, AWS, cloud repatriation, and safe AWS account onboarding.
Module 1: Understanding Cloud Computing
1. What is Cloud Computing?
Definition: Cloud computing is the delivery of computing resources such as servers, storage, databases, networking, and software over the internet on a pay-as-you-go basis.
In simple words: Instead of purchasing and maintaining physical servers, companies can rent computing resources from cloud providers like AWS, Microsoft Azure, and Google Cloud.
Real-world example: Imagine you want to start an online shopping website. Traditionally, you would need physical servers, networking equipment, hard disks and storage, cooling systems, electricity, IT administrators, and security systems. This requires significant investment. With cloud computing, you can rent servers from AWS and pay only for the resources you use.
 
2. Evolution of Cloud Computing
Explain the evolution in three stages.
Stage 1: Traditional Data Center (On-Premises)
Earlier, organizations maintained their own physical infrastructure. A company might purchase 10 physical servers, install operating systems, configure networking, maintain hardware, handle power and cooling, and manage security and backups.
Problems:
•	High initial investment
•	Hardware maintenance
•	Limited scalability
•	Resource wastage
•	Time-consuming infrastructure setup
Stage 2: Virtualization
Virtualization is a technology that allows multiple virtual machines (VMs) to run on a single physical server.
Example: Suppose a company has one physical server with 32 GB RAM, 16 CPU cores, and 1 TB storage. Instead of using this server for just one application, virtualization allows us to create multiple virtual machines.
Virtual machine	RAM	CPU
VM 1	8 GB	4 cores
VM 2	8 GB	4 cores
VM 3	8 GB	4 cores
VM 4	8 GB	4 cores

This improves hardware utilization.
 
Important terms:
•	Hypervisor: Software that creates and manages virtual machines.
•	Virtual Machine: A software-based computer running its own operating system.
•	Host Machine: The physical server running virtual machines.
•	Guest OS: Operating system installed inside a virtual machine.
Examples of hypervisors: VMware ESXi, Microsoft Hyper-V, and KVM.
Stage 3: Cloud Computing
Cloud providers operate large data centers containing thousands of physical servers. Customers can request computing resources whenever needed.
•	Need one server? Launch one.
•	Need 100 servers? Launch 100.
•	Need more storage? Increase storage.
•	Need to reduce resources? Scale down.
This is called scalability and elasticity.
3. Why Do We Need Cloud Computing?
Ask students: “What problems do companies face when they manage their own infrastructure?” Expected answers:
•	Hardware purchasing costs
•	Electricity and cooling costs
•	Hardware maintenance
•	Security management
•	Infrastructure upgrades
•	Limited scalability
•	Disaster recovery challenges
Cloud computing helps address these challenges.
Module 2: Private Cloud vs Public Cloud
4. What is Private Cloud?
A private cloud is a cloud environment dedicated to a single organization. The organization has greater control over its infrastructure, configuration, security, and access.
Example: A large bank maintains a private cloud environment to host sensitive banking applications.
 
Advantages:
•	Greater infrastructure control
•	Custom security configurations
•	Dedicated environment
•	Can support strict compliance requirements
Disadvantages:
•	Higher infrastructure costs
•	Maintenance responsibilities
•	Requires skilled IT teams
•	Scaling can require additional capacity planning
Note: Private cloud can be hosted in an organization's own data center or by a third-party provider. It does not necessarily mean that the organization owns all the hardware.
5. What is Public Cloud?
A public cloud is a cloud computing environment where a third-party cloud provider delivers computing resources over the internet.
Examples: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).
How does it work?
1.	The cloud provider owns and maintains physical infrastructure.
2.	Customers create accounts.
3.	Customers select required services.
4.	Resources are provisioned through a web console, API, or command-line interface.
5.	Customers pay according to the pricing model and resources consumed.
6. Private Cloud vs Public Cloud
Feature	Private Cloud	Public Cloud
Infrastructure	Dedicated to one organization	Provider-owned infrastructure
Management	Organization or contracted provider	Cloud provider manages physical infrastructure
Cost	Usually higher fixed investment	Consumption-based pricing available
Scalability	Depends on available capacity	Highly scalable
Control	Greater control	Less control over physical infrastructure
Examples	OpenStack-based private cloud	AWS, Azure, GCP

Trainer's explanation: Think of private cloud as owning or exclusively using your own house. Public cloud is like renting an apartment. You use the facilities without managing the entire building.
Module 3: Benefits of Public Cloud
7. Why Are Companies Moving to Public Cloud?
1. Cost Optimization
Traditional infrastructure requires significant capital expenditure (CapEx). Cloud computing allows companies to use operational expenditure (OpEx) models. Example: Instead of purchasing a server for ₹5 lakh, a company can rent cloud infrastructure and pay according to usage. Remember: Cloud is not always cheaper. Poor resource management can increase costs.
2. Scalability
Scalability means increasing or decreasing computing resources based on requirements. Example: An e-commerce website may experience high traffic during a festival sale. It can increase server capacity during the sale and reduce it afterward.
3. High Availability
Cloud providers offer infrastructure across multiple locations and availability zones. This helps organizations design applications that remain available even if individual components fail.
4. Global Reach
Companies can deploy applications in different geographical regions. For example, an Indian company can host applications in Mumbai, Singapore, Frankfurt, or Virginia.
5. Reduced Maintenance
Cloud providers manage the underlying physical infrastructure, including physical server maintenance, data center power, cooling, hardware replacement, and physical security. However, customers still manage many responsibilities, including application security, identity permissions, data protection, and operating systems where applicable.
6. Faster Deployment
Traditional infrastructure procurement can take weeks. Cloud resources can often be provisioned in minutes.
Module 4: Why AWS?
8. What is AWS?
AWS stands for Amazon Web Services. It is a cloud computing platform offered by Amazon.
AWS provides services for computing, storage, databases, networking, security, monitoring, artificial intelligence, and application deployment.
9. Why Should We Learn AWS?
1. First-Mover Advantage
AWS launched in 2006 and was an early major player in commercial cloud computing. This helped AWS establish a strong market presence.
2. Wide Range of Services
AWS offers more than 200 services and features across different technology categories.
3. Industry Adoption
AWS is used by startups, enterprises, government organizations, and technology companies.
4. Career Opportunities
Learning AWS can help professionals pursue roles such as Cloud Engineer, AWS Solutions Architect, DevOps Engineer, Cloud Administrator, Site Reliability Engineer (SRE), and Cloud Security Engineer.
5. Flexible Pricing
AWS provides different pricing models, including On-Demand, Savings Plans, Reserved capacity options for eligible services, and Spot Instances. Students should learn AWS cost management from the beginning.
Module 5: Introduction to Important AWS Services
10. Important AWS Services
Amazon EC2
Elastic Compute Cloud. Used to create and run virtual servers in AWS. Example: Hosting a website on a virtual server.
Amazon S3
Simple Storage Service. Used to store files, images, videos, backups, and other objects.
Amazon RDS
Relational Database Service. Used to create and manage relational databases.
Amazon VPC
Virtual Private Cloud. Used to create an isolated virtual network in AWS.
AWS IAM
Identity and Access Management. Used to manage users, roles, permissions, and access.
AWS Lambda
Used to run code without managing the underlying servers.
Amazon CloudWatch
Used for monitoring AWS resources, logs, metrics, and alarms.
 
Module 6: Cloud Repatriation
11. What is Cloud Repatriation?
Cloud repatriation means moving applications, workloads, or data from public cloud environments back to on-premises infrastructure or private cloud environments.
 
Why do companies move workloads back?
•	High cloud bills
•	Predictable workloads
•	Data sovereignty requirements
•	Regulatory and compliance requirements
•	Performance requirements
•	Greater control over infrastructure
Example: Imagine a company runs a database on AWS. Initially, cloud hosting is convenient because the company does not need to purchase servers. However, after several years, the database becomes very large and its workload becomes predictable. The company evaluates whether purchasing dedicated infrastructure would reduce its long-term operating costs. It may decide to move the database back to its own data center.
Does cloud repatriation mean cloud computing is failing?
No. Different workloads have different requirements.
Public cloud is particularly useful for:
•	Startups
•	Rapidly growing businesses
•	Variable workloads
•	Global applications
•	Organizations that want to avoid managing physical infrastructure
On-premises infrastructure can be attractive for:
•	Predictable workloads
•	Specialized hardware requirements
•	Certain compliance needs
•	Workloads with favorable long-term economics
Trainer's key message: Cloud is not about moving everything to AWS. It is about choosing the right infrastructure for the workload.
Module 7: AWS Account Creation
12. What Do We Need to Create an AWS Account?
6.	A valid email address
7.	A phone number
8.	A valid credit or debit card supported by AWS
9.	Internet access
10.	Basic personal or business details
13. Step-by-Step AWS Account Creation
Step 1: Open the AWS website
Go to https://aws.amazon.com/ and click on Create an AWS Account.
Step 2: Enter Email Address
Enter your email address, provide an AWS account name, and verify your email using the verification code.
Step 3: Create a Password
Create a strong password according to AWS requirements.
Step 4: Enter Contact Information
Choose whether the account is for personal use or business use, then enter the required contact details.
Step 5: Payment Information
Enter your supported credit or debit card information. AWS uses payment information as part of account verification. A temporary authorization or verification charge may occur depending on the payment method and region. Important: Creating an AWS account does not mean all AWS services are free.
Step 6: Identity Verification
Complete the phone or other verification process requested by AWS.
Step 7: Select a Support Plan
Choose the available support option appropriate for your needs. Review the current pricing before selecting paid support.
Step 8: Sign in to AWS Management Console
After completing registration, open https://console.aws.amazon.com/. Students should now be able to access their AWS console.
14. Important AWS Account Safety Instructions
•	Never share AWS root account credentials.
•	Enable MFA (Multi-Factor Authentication).
•	Avoid using the root account for everyday activities.
•	Create IAM users or roles with appropriate permissions.
•	Set up billing alerts and budget notifications.
•	Delete unused resources.
•	Check the AWS Free Tier eligibility and current usage limits.
Important trainer warning: Free Tier eligibility, allowances, and duration vary by account creation date and service. Always check the current AWS Free Tier details before launching resources.
AWS Free Tier information: https://aws.amazon.com/free/
Module 8: Practical Demonstration
After explaining the theory, conduct a simple practical demonstration.
Practical 1: Explore the AWS Management Console
Ask students to:
11.	Log in to AWS.
12.	Explore the AWS Management Console.
13.	Search for EC2.
14.	Open the EC2 dashboard.
15.	Identify the AWS Region selector.
16.	Explore the available services.
 
Practical 2: Understand an EC2 Instance
An EC2 instance is a virtual server running in AWS.
Important concepts:
•	Instance type: Defines compute capacity.
•	AMI: Amazon Machine Image, used as a template to launch an instance.
•	Key pair: Used for supported secure instance access methods.
•	Security Group: Controls inbound and outbound network traffic.
•	EBS: Provides block storage for EC2 instances.
Suggested demonstration: Show the EC2 launch wizard, explain its configuration options, and stop before launching if students do not have a verified budget and cost controls.
Module 9: Trainer Assessment and Interview Questions
Use these questions to check whether students understood the session.
1. What is cloud computing?
Answer: Delivering computing resources over the internet.
2. What is virtualization?
Answer: Creating multiple virtual machines on physical hardware.
3. Which company provides AWS?
Answer: Amazon.
4. Which AWS service is used for virtual servers?
Answer: EC2.
5. Which AWS service is used for object storage?
Answer: S3.
6. What is cloud repatriation?
Answer: Moving workloads back to on-premises or private infrastructure.
7. What does IAM manage?
Answer: Identity and permissions.
Module 10: Suggested Training Agenda
Topic	Duration
Introduction to cloud computing	15 min
Evolution: Data Center to Virtualization to Cloud	15 min
Private vs Public Cloud	15 min
Benefits of Public Cloud	10 min
Introduction to AWS	15 min
Important AWS services	15 min
Cloud repatriation	10 min
AWS account creation	15 min
Practical demonstration and Q&A	10 min
Total	120 min

Final Trainer Summary
At the end of the session, students should understand these five concepts:
17.	Cloud Computing: Renting computing resources over the internet instead of maintaining all physical infrastructure.
18.	Virtualization: Running multiple virtual machines on one physical server.
19.	Public Cloud: Using cloud services from providers like AWS, Azure, and GCP.
20.	AWS: Amazon's cloud platform offering compute, storage, networking, databases, and many other services.
21.	Cloud Repatriation: Moving workloads from public cloud back to on-premises or private infrastructure when business requirements justify it.
Recommendation for the next training session: Don't jump directly into advanced AWS services. First ensure students understand the fundamentals, then move into AWS IAM, EC2, S3, VPC, and RDS with hands-on exercises. This will give them a much stronger foundation for real-world AWS projects.
