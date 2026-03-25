<p align="center">
<img src="../assets/jvbnetlabs.png" width="300">
</p>

# Static Route Configuration
- Exam Topic 3.3 - **"Configure and verify IPv4 and IPv6 static routing"** - *IPv4 foucused.  IPv6 routing to be addressed in future lab*
- [📄 View Full Lab (PDF)](./Static_Route_Configuration.pdf)

## Scenario
  A company has a user network on the branch floor (SW1) and a server network in the data center (SW2), and both need to communicate through the internal routing infrastructure. Under normal conditions, traffic is expected to follow the main path through R2, which acts as the central router connecting the two sides. There is also a direct link between R1 and R3, but it exists only as a backup and should not be used unless the primary path fails. 


  The network does not use dynamic routing, so everything must be handled with static routes. Your task is to configure routing on R1, R2, and R3 so that communication between the two networks works reliably, traffic prefers the path through R2, and automatically switches to the R1–R3 link if the main path goes down.


<img src="./Topology.png" width="500">

## Requirements
- Configure the necessary static routes on the routers for inter-office communication
- Configure the backup link accordingly, allowing for automatic switch-over in the main path fails.


## Post-Lab Testing
- Perform connectivity tests by pinging between PCs across switches
- Disable interfaces on primary route to test backup route switchover
- Run the appropriate ‘show’ commands to confirm configuration


<br>
  <a href="mailto:J.VanBurenIV@outlook.com"><img src="/assets/jvbsig.png"></a>
