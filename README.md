# DistributedSystem
Semester project creating a simulation of a distributed system

##Project Specifics:
- Threaded Distributed System
- Program contains a master, two clients and two slaves
- Clients communicates via sockets to Master sending 'jobs' of either type A or B
- SlaveA prioritizes job of type A and slaveB prioritizes job of type B
- Master directs jobs to slaveA and slaveB based on their current work load and efficiency of sending the job to a slave which doesn't optomize that type
- Slaves return completed work (slept for specified duration) to master which in turn replies to correct client
