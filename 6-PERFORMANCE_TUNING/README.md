- Identify Hardware Characteristics: \
  The root folder contains a file named dmidecode.out which is the output obtained using dmidecode on another system. \
  You have to determine the sizes of the L1 and L2 cache data sizes. \
  The data might contain information pertaining to several processors and cores.
  You have to base your answer selecting just one processor or core.
  
- Analyze sar ourput: \
  The file /root/sar.data contains data. It might also contain logical volume info but you have to select only physical volumes.
  
- Memory: 
  There are two applications in /usr/local/bin folder. \
  You must configure your system such that when you attempt to run /usr/local/bin/greedy \ 
  you get the message ' unable to allocate memory' \
  and when you attempt to to run /usr/local/bin/checklimit, you get "Success: Memory within space limit" 
  

- Configure Memory Allocation: 
You have to allocate the SYSV memory such that mimimum 1 GiB and max 1.5 Gib - which persists across reboots ?


- Configure Process Priority: 
       There is an application named realtime in /usr/local/bin. 
You must configure such that it starts up automatically at boot time with static priority of 27 in round robin process scheduler.It runs in the background. You can verify that it is running by checking /var/log/messages. 


- Find the physical memory in pages taken by real time, you can select from list, rounding up or down to nearest number.


- Choose Best Cache Performance: 
		There are two applications cache-a and cache-b 
		One makes improper use of cache 
		You have to select the one which makes the best use of cache 
		And copy that file to /usr/local/bin/   folder 
		Determine the tool or tools which might be required for the purpose.


- Configure Network Buffers: 
	Configure the the network buffers, so that UDP, both incoming and outgoing, has 128 of minimum and 192 of max for buffers. 


- Configure SWAP: 
		You have to configure 2 Gib of swap space under the following circumstances 

		a)  Do not delete the existing swap volume. 
		b)  The extra swap space must be equally split between 2 new partitions 
		c)  The two new partitions should be mounted at system boot 
        d)  At system boot the kernel should first use the new swap partitions and then the old one 


- Configure Network Latency: 
Most of tne network connections between your system and other system are via a low earth orbit satellite link. 
It has a approximately 500 miiliseconds and a bandwith of 1.5 Mib /s (meebibit per sec) 
		 
		Configure so that 
		 
a) the minimum amount of memory for buffering per connection is equal to the latency and bandwidth. 
b) the default amount of memory is the minimum amount of memory available for buffering. 
c) the maximum amount of memory for buffering per connection is 1.5 time the minimum amount of memory available. 


- There are two applications memapp1 and memapp2 in /usr/local/bin. User MemHog must be able run memapp1 but not memapp2 or any other application having similar characteristics


- Configure the system so that the modified contents in memory remain for 60 seconds minimum before 	being considered for flushing to disk.


- 