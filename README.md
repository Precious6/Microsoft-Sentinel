# Microsoft-Sentinel
configured azure sentinel( Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to phyical location and mangiude of attacks : Below is the steps i follow to be able to visualize the attack  .

Step 1 : Created Subscription

Step 2  : Created VM (turn the external firewall off  that VM by setting Inbound rule to allow any port from any protocol and source and then turn off windows firewall off as well) so that it will be super exposed to the internet like anyone can able to ping it from any country.

Step 3: Create Log Analytics Workspace which will be using to absorb  logs from VM .

Step 4 :Create Microsoft Sentinel(SIEM) that is use for creating map that maps all the differen attackers across the world.

Here's the sample of what i've done but also do check workflows folder.
I have created Vm and connect it to Log analytics workspace
![image](https://user-images.githubusercontent.com/63658710/166250051-49e1bd5c-1082-4256-b7d1-e8c82261ec4e.png)

I then created Sentinel that maps (visualize attack from different countries)
![sentinel](https://user-images.githubusercontent.com/63658710/166250122-5fbdaffe-557b-4994-a862-a2ed3248600d.PNG)


