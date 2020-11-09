## Notes 06: Compute
#### Alfredo Sanchez Mendoza
#### CIT 114 FALL 2020

### 1. Summarize a few key points made in the readings or videos 
+ The chapter involved many concepts but one of the main one was about VMs and docker. It also delves into what an OS, storage, and memory in the cloud meant. It also explains in depth of how elastic the services it provided were. Basically, you were guided in the process of deploying the instances and your team could develop actual stuff for your project. 

### 2. Identify two quotes that were made, that you found interesting.
1. "What is a virtual machine? A virtual machine (VM) is a software-based computer that exists within another computer’s operating system, often used for the purposes of testing, backing up data, or running SaaS (Links to an external site.) applications." (8). <br/>
2. "Operating in an AWS environment allows customers to take advantage of embedded, automated tools like AWS Security Hub, AWS Config and AWS CloudTrail for validating compliance. These tools reduce the effort needed to perform audits, since these tasks become routine, ongoing, and automated. By spending less time on manual activities, you can help evolve the role of compliance in your company from one of a necessary administrative burden, to one that manages your risk and improves your security posture. " (8.03). <br/>

### 3. What new facts did you learn from this section?
An AMI includes the following: One or more EBS snapshots, or, for instance-store-backed AMIs, a template for the root volume of the instance (for example, an operating system, an application server, and applications) <br/>
Key Benefits Elastic Web-Scale Computing Completely Controlled Flexible Cloud Hosting Services Integrated Reliable Secure Inexpensive Easy to Start <br/>
Docker vs Kubernetes A fundamental difference between Kubernetes and Docker is that Kubernetes is meant to run across a cluster while Docker runs on a single node <br/>
Many people who are first introduced to the concept of a container think that containers are exactly like virtual machines. However, the differences are in the details. One significant difference is that virtual machines run directly on a hypervisor, but containers can run on any Linux OS <br/>

### 4. What questions remain in your mind after reading this section?
1. I think the chapter should had dwell a bit more on implementing instances/containers, such as deploying ansible with Docker since it’s a more scalable project than deploying vms which are way more resource intensive. <br/>
