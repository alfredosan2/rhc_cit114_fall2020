#Notes 04: Cloud Secuirty with DevOps
### 1. Summarize a few key points made in the readings or videos 
+ The chapter went over the fundamentals of AWS cloud. It delved on concepts such as AWS load balancing, ELB, CW, and AS. It also stated the advantages of using public cloud services: that the setup & operations are intensely automated, including the monitoring. Also, by using correctly load balancing, auto scaling, and even the free or 3rd party monitoring services can save admins a lot of downtime and have more uptime.

### 2. Identify two quotes that were made, that you found interesting.
1. "Here’s the first rule of running applications in the cloud: you don’t know what’s going on unless you’re monitoring your application resources 24/7." (10.05). <br/>
2. “capabilities can be elastically provisioned and released” describes a situation in which a hosted cloud application can seemingly be changed on demand to provide the desired level of performance by adding performance or taking away the level of performance. (10.05) <br/>

### 3. What new facts did you learn from this section?
+ One of the NIST characteristics of the public cloud was defined as rapid elasticity featuring the statement “capabilities can be elastically provisioned and released in some cases automatically, to scale rapidly outward and inward commensurate with demand.”
+  Resource pooling, which is also related to the ability to scale. You can’t scale your resources (adding to the number of EC2 instances supporting your application) unless you have the actual resources available to add.
+ That if multiple VMs were hosted on a physical server, proper monitoring of the hosted virtual machines was essential to ensure that each virtual server’s performance was adequate and to make sure that each VM was not running out of RAM, CPU, and storage. And because virtual resources were being utilized from physical resources, additional RAM, CPU cores, and storage could be added and removed as required.

### 4. What questions remain in your mind after reading this section?
