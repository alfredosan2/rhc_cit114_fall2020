# Notes 1: Cloud Concepts Overview
### 1. Summarize a few key points made in the readings or videos 
+ Hardware that allows you to scale up as needs get brought up (more website visits).
+ Increased Security Vulnerabilities: by hastily migrating to the cloud, a lot of wrong configs can occur, causing bad actors to access mission critical data/processes.
+ How the four pillars of IT help maintain our lifestyle: Infrastructure, Development, Security, Data.

### 2. Identify two quotes that were made, that you found interesting.
1. “IT can provide the edge a company needs to outsmart, outpace and out-deliver competitors,” says Edward Kiledjian, a Chief Information Security Officer and technology blogger. (1.2). <br/>
2. "It was during this time [2006] that Amazon launched its Elastic Compute Cloud (EC2) services that enabled organizations to "lease" computing capacity and processing power to run their enterprise applications." (1.4).

### 3. What new facts did you learn from this section
1. Clouds can be for public use, like the Internet, and private clouds allow users to access privately owned internet resources such as documents accessed through the internet. <br/>
2. Cloud consumers experience decreased portability moving data from one cloud provider to another cloud provider's services. <br/>
3. SaaS applications, such as Microsoft 365, overall performance relies heavily on a user's internet performance. SaaS is often end-user applications often maintained by the service provider. <br/>
4. The On Premises cloud model, or private cloud, doesn't provide all the benefits of cloud computing but is utilized because of its ability to provide on premise resources.

### 4. What questions remain in your mind after reading this section?
1. In what ways will utilizing AWS help me grasp how cloud computing has been impacting my daily life?

# Notes 2: Cloud Economics, Billing & Support
### 1. Summarize a few key points made in the readings or videos 
+ Fundamentals of AWS pricing: The Compute – pay per processing cpu cycles, Storage – pay per Gb, Outbound data transfer – the more data you allow to be transferred outside of AWS data centers the more you pay. 
+ Free Tier: AWS will generously allow you to test drive certain services to familiarize or see if implementation is doable. It includes: Elastic Beanstalk, CloudFormation, VPC, Auto-Scaling, IAM, CloudFormation.
+ Traditional Infrastructure vs Cloud Infrastructure: In traditional set-ups data storage, equipment, and maintenance is done in-house. While in cloud set-ups you can use a cloud provider like AWS, Azure, Google, etc. to host your resources or you could also create and spin up your own private cloud by building it yourself.

### 2. Identify two quotes that were made, that you found interesting.
1. "System health monitoring: Monitor system-wide health, respond to performance changes, and optimize your resource utilization. With AWS CloudWatch (Links to an external site.), you get monitoring and operational data in the form of logs, metrics, and events, providing you with a unified view of your AWS resources, applications, and services that run on AWS and on-premises servers. " (2.16). <br/>
2. " Use free client software. Users can run most SaaS apps directly from their web browser without needing to download and install any software, although some apps require plugins. This means that you don’t need to purchase and install special software for your users." (2.12). <br/>

### 3. What new facts did you learn from this section?
1. Pay-as-you-go Using AWS does not mean you have to pay upfront a set monthly bill, you only have pay for what resources are consumed. <br/>
2. AWS Management Console: I thought I was going to have to memorize and learn various monitoring and locations of resources. But AWS has it all organized & in a human-friendly way to review and lots of templates. <br/>
3. What is the Total Cost of Ownership? TCO I didn’t know there was a formula that you could use to assess whether your existing infrastructure, existing skilled and humans, difference in cost pre-cloud and post-cloud. <br/>
4. Different support plans such as: Basic plan(free), developer, Business, Enterprise support plans each tuned to the need of that. <br/>

### 4. What questions remain in your mind after reading this section?
1. In what ways could I implement AWS to save a medium business resources on contracting IT Support to maintain aging in-House Tech? Virtualize Wi-Fi-portal in the cloud? Create web based smart displays to showcase the update menu items or inventory? <br/>

# Notes 03: 
# Notes 04: 
# Notes 05: Networking & Content Delivery
### 1. Summarize a few key points made in the readings or videos 
+ The chapter went over the fundamentals of network security. It delved on concepts such as Cloud front, VPC (Virtual Private Cloud), and Route 53. It did mention that the concept of physical switches and networking too. Such as Wireless access points, Routers, L3 Switches, different topologies such as the most often used is star topology in most networks. It also delves into separating your network with subnetting so unnecessary devices are not roaming around your network and telephoning back home data.

### 2. Identify two quotes that were made, that you found interesting.
1. "The principle of least privilege is an important concept in computer security. It promotes that you grant only the minimal user privileges needed to the user, based on the needs of your users." (6.06). <br/>
2. The customer is responsible for what is implemented by using AWS services and for the applications that are connected to AWS. The security steps that you must take depend on the services that you use and the complexity of your system. Customer responsibilities include selecting and securing any instance operating systems, securing the applications that are launched on AWS resources, security group configurations, firewall configurations, network configurations, and secure account management. (6.04) <br/>

### 3. What new facts did you learn from this section?
+ How to implement AWS CloudFront and its nuances like working with Vpcs and elastic ip addresses was very interesting, and how you could do that on the fly.
+ Authorization is the process of determining what permissions a user, service or application should be granted. After a user has been authenticated, they must be authorized to access AWS services.

### 4. What questions remain in your mind after reading this section?
1. There has to be more labs I can practice networking in the cloud with AWS, such creating security groups and such. <br/>
2. Is there anyways I can implement subnetting so I can divide up my network? Perhaps through subnetting? ( iot, wifi guests, main network for trusted devices) <br/>

# Notes 06: Compute
### 1. Summarize a few key points made in the readings or videos 
+ The chapter involved many concepts but one of the main one was about VMs and docker. It also delves into what an OS, storage, and memory in the cloud meant. It also explains in depth of how elastic the services it provided were. Basically, you were guided in the process of deploying the instances and your team could develop actual stuff for your project. 

### 2. Identify two quotes that were made, that you found interesting.
1. "What is a virtual machine? A virtual machine (VM) is a software-based computer that exists within another computer’s operating system, often used for the purposes of testing, backing up data, or running SaaS (Links to an external site.) applications." (8). <br/>
2. "Operating in an AWS environment allows customers to take advantage of embedded, automated tools like AWS Security Hub, AWS Config and AWS CloudTrail for validating compliance. These tools reduce the effort needed to perform audits, since these tasks become routine, ongoing, and automated. By spending less time on manual activities, you can help evolve the role of compliance in your company from one of a necessary administrative burden, to one that manages your risk and improves your security posture. " (8.03). <br/>

### 3. What new facts did you learn from this section?
+ An AMI includes the following: One or more EBS snapshots, or, for instance-store-backed AMIs, a template for the root volume of the instance (for example, an operating system, an application server, and applications)
+ Key Benefits Elastic Web-Scale Computing Completely Controlled Flexible Cloud Hosting Services Integrated Reliable Secure Inexpensive Easy to Start
+ Docker vs Kubernetes A fundamental difference between Kubernetes and Docker is that Kubernetes is meant to run across a cluster while Docker runs on a single node
+ Many people who are first introduced to the concept of a container think that containers are exactly like virtual machines. However, the differences are in the details. One significant difference is that virtual machines run directly on a hypervisor, but containers can run on any Linux OS

### 4. What questions remain in your mind after reading this section?
1. I think the chapter should had dwell a bit more on implementing instances/containers, such as deploying ansible with Docker since it’s a more scalable project than deploying vms which are way more resource intensive. <br/>

# Notes 07: Storage
### 1. Summarize a few key points made in the readings or videos 
+ I liked how it explained in depth the most common levels used by businesses for backups are RAID 1, RAID 5, RAID 6 and RAID 1+0. Also, how RAIDS are often used with SANS and NAS systems. How volatile vs non-volatile memory cannot and can retain data.

### 2. Identify two quotes that were made, that you found interesting.
1. "Software test and development environments often require separate, independent, and duplicate storage environments to be built out, managed, and decommissioned. In addition to the time required, the up-front capital costs required can be extensive." (9.04). <br/>
2. "When development teams are ready to execute, infrastructure should never slow them down. Cloud storage allows IT to quickly deliver the exact amount of storage needed, right when it's needed. This allows IT to focus on solving complex application problems instead of having to manage storage systems." (9.03). <br/>

### 3. What new facts did you learn from this section?
+ Some of the largest and most valuable companies in the world have created applications in record time by leveraging the flexibility, performance, and low cost of cloud storage. Even the simplest static websites can be improved for an amazingly low cost.
+ Fault tolerance is the idea that a system can continue to run properly even in the event of a failure of a component of that system.
+ Disaster recovery (DR) starts with a plan that works in conjunction with the business continuity and contingency plans. In DR, the goal is to get a business back operating as normally as possible as quickly as possible.
+ If a computer does not have the recommended memory to run the operating system and software programs being used, it will result in slower performance. The more memory a computer has, the more information and software it can load and process quickly.

### 4. What questions remain in your mind after reading this section?
1. Does Intel’s Optane memory count as nonvolatile memory even though it is used for temporary caching at every boot-up? Does it have a high fault tolerance? <br/>

# Notes 08: Databases
### 1. Summarize a few key points made in the readings or videos  
+ I learned about Relational Databases; I didn’t know you could make data interact like that. Plus, the way you can view in different ways: like arranging data in a date field to be ordered according to a calendar system. Also how NoSQL databases are easier to scale than typical SQL ones since it uses horizontal scale-out: making it affordable and fast to run.

### 2. Identify two quotes that were made, that you found interesting.
1. "NoSQL is particularly useful for storing unstructured data, which is growing far more rapidly than structured data and does not fit the relational schemas of RDBMS. Common types of unstructured data include: user and session data; chat, messaging, and log data; time series data such as IoT and device data; and large objects such as video and images." (10.04). <br/>
2. "Managed services require the user to configure the service, however, much of the the underlying patching, backups, ensuring availability, and more are managed by the service provider. " (10.06). <br/>

### 3. What new facts did you learn from this section?
+ A combination of fields makes up a table. For example, each field in an employee table contains data about an individual employee.
+ A database management system (DBMS) is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information.
+ A database system is referred to as self-describing because it not only contains the database itself, but also metadata which defines and describes the data and relationships between tables in the database.
+ Concurrency control strategies: features of a database that allow several users access to the same data item at the same time

### 4. What questions remain in your mind after reading this section?
1. Maybe trying out designing a short and simple database to see how the data relationships interact a bit more? <br/>
2. I think practicing a bit more SQL would benefit me since I’m trying to target more the cyber-security aspect of databases and potentially point out data breaches in the future. <br/>

# Notes 09: Cloud Architecture
### 1. Summarize a few key points made in the readings or videos  

# Notes 10: Automatic Scaling & Monitoring
### 1. Summarize a few key points made in the readings or videos 
+ The chapter went over the fundamentals of AWS cloud. It delved on concepts such as AWS load balancing, ELB, CW, and AS. It also stated the advantages of using public cloud services: that the setup & operations are intensely automated, including the monitoring. Also, by using correctly load balancing, auto scaling, and even the free or 3rd party monitoring services can save admins a lot of downtime and have more uptime.

### 2. Identify two quotes that were made, that you found interesting.
1. "Here’s the first rule of running applications in the cloud: you don’t know what’s going on unless you’re monitoring your application resources 24/7." (10.05). <br/>
2. “capabilities can be elastically provisioned and released” describes a situation in which a hosted cloud application can seemingly be changed on demand to provide the desired level of performance by adding performance or taking away the level of performance. (10.05) <br/>

### 3. What new facts did you learn from this section?
+ One of the NIST characteristics of the public cloud was defined as rapid elasticity featuring the statement “capabilities can be elastically provisioned and released in some cases automatically, to scale rapidly outward and inward commensurate with demand.”
+  Resource pooling, which is also related to the ability to scale. You can’t scale your resources (adding to the number of EC2 instances supporting your application) unless you have the actual resources available to add.
+ That if multiple VMs were hosted on a physical server, proper monitoring of the hosted virtual machines was essential to ensure that each virtual server’s performance was adequate and to make sure that each VM was not running out of RAM, CPU, and storage. And because virtual resources were being utilized from physical resources, additional RAM, CPU cores, and storage could be added and removed as required.
+Auto scaling with CloudWatch alarms—Automatically adjust your applications based on need with EC2 auto scaling, ELB, and CloudWatch alarms.

+ Filter logs with metric filters and alerts—Be notified when specific data patterns occur in your logs, and act accordingly using CloudWatch alerts, metric filters, and simple notification service (SNS) notifications calling Lambda to run custom functions for custom tasks.
+ Billing alarms enabling you to monitor costs—Control costs by matching billing alerts to actual budget targets using billing alerts and SNS notifications.
+ Logging CloudTrail IAM API calls to CloudWatch logs—This involves creating CloudTrail trails, storing the trails in CloudWatch, and using metric filters on root account activity.

### 4. What questions remain in your mind after reading this section?
1. CloudWatch is not really useful until you start to figure out the data patterns your network uses, a baseline per say. <br/>
2. Is there anyways I can implement more redundancy so I can load balance? Or enable other features like alarm triggers if a device can’t be pinged? <br/>
