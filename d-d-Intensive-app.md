# Designing Data Intensive Application

call an app - data intensive, if data is the primary challenge (as opposed to CPU intensive) - quantity, complexity, speed at which it is changing  
rapid changes in technology - but there are enduring principles that remain true

# Foundations of Data Systems 

**Building Block**   
- databases - store data  
- caches - speed up expensive operation  
- search indexes - search data by keyword or filter data  
- stream processing - send message to another process  
- batch processing - periodically crunch a large amount of accumulated data   

all blocks under one umbrella, data systems - but different access patterns, implementation, performance  

what we’re actually trying to achieve: reliability, scalability, and maintainability

**Reliability** - continue to work correctly, even when things go wrong  
fault - one component deviating from it's spec  
failure - when system as a whole stops providing the required service to the user  

The netflix chaos monkey

**Hardware faults** - Hard disks crash, RAM becomes faulty, power blackout  
storage with 10,000 disks - average one disk to die per day  
RAID configuration in disks - hot swappable CPUs

**Software Errors** - software bug, bad input,   
CPU time -   
memory -  
disk space -  
network bandwidth -    
roll back configuration changes -  
unit test, integration test, manual test, automation test  
monitoring - performance metrics, error rates  
