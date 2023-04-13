# **Important Notes For Devops Engineer**
 **Microsoft Active Directory?**

- It is an identity and access management solution that allows you to define who can do what in your network.
- it helps you manage credentials of multiple computers and users in same network/domain.
- enables you to connect with linux and windows in same network.
- giving you a single sign-on and centralized management experience across a network of Windows and Linux instances.


##*why*
- With a single login, you can access different services and resources without logging into each one.
- with help of that you can access different services at single domain.
 
 ##*what is iam profile ?*
 - can contain only one role
 - one role is for one instance only
 
 
 ##*Features of EBS: *
 - It is availability zone specific, due to it has high performance.
 - you can change its volume type (gp2 to io2) without facing downtime.
 - you can expand your ssd volume.
 
 
#*what is CPU*
---- carries out the instruction from computer program. based upon the instruction it performs logical and arith. operations
###Functions of CPU in computer.
- controlling all other parts of machine and sending timing signals.
- transferring data between memory and i/o devices.
- fetching data and instructions from memory.
- decoding instructions.
- performing arthematic and logical operation
- executing programs and stored in memory.

###what is RAM?
- Ram is temporary memory bank where your computer stores data it needs to retrieve quickly.
- computer can access your RAM much faster than your disk data. that's why your ram is important.
- application cannot access without memory. Mem Plays vital role to run app.

##why memory is important?##
- If there is no memory, the computer will not boot up. It has to have RAM memory to load the instructions the computer needs to complete the boot up.
-  stores data and instructions that are currently being used by the computer. 
-  it stores the instruction/processes that are being used by commputer.
-  When an application is launched, it is loaded into the RAM, where the processor can access its instructions and data quickly.
-  The amount of RAM available determines the number of applications that can be run simultaneously and the speed at which they can operate.
-  ram is required to function the computer.


#why we Use SSD as Bootable volume?/why not HDD?
- SSD uses integrated circuit assemblies instead of moving mechanical parts,
- It can run more quickly, enjoy shorter access time and have lower power consumption than HDD.


##why time of booting is very faster in AMI than booting time of our Computers. 
- Ami Consist preconfigured kernal id and other ram id 
- time depends on number of factors= size of ami, how recently you have launched that AMI. 
- images launch for first time will take longer to boot.

##what is snapshot?
- a snapshot refers to a copy or image of a system, disk, file system, or virtual machine at a specific point in time.
- it is the snapshot of current state of object.
- it is very usefull in case of roll back to previous state.
- suppose we have to upgrade the machine, so for that we take snapshot for going wrong something, so you can quickly roll back to previous state.


##Difference between Hot storage vs Cold storage?
- hot storage:
-      refers to data that is frequently used and accessed, like document on your hard-drive 
-      it requires fastre hardware, (expensive data)
-      hourly access, daily.
-      *ex-* data access by customers or employees.SSD , in-memory database.
-      fast
- warm storage:
-      is data that less frequently access.
-      weekly access, monthly access
-      *ex*- data for reporting analytics.
-      

- cold storage:
-      refers to data that is inftrequntly access.
-      inexpensive data,
-      slowest
-      quarterly, yearly access
-      *ex-* this could be data that is archived for compliance reason,cheap, tape storage and 
-      hard drive

##Difference between Region specific and availability zone Specific?
- Region sp service= you can share your resources within REGION And can access by multiple AZI.
- Availability Zone Service = you cannot share your resources with other AZ.



##Terraform what use to manage different different Environment?
- it uses workspace













