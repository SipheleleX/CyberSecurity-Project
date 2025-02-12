# Security + Project

## Objective

 This project involved creating three virtual machines to simulate different network configurations. My task involved configuring these virtual machines according to specified requirements and ensuring proper networking between them, while considering security implications.
 
### Skills Learned

- Creating and configuring virtual machines using Oracle VirtualBox.
- Configuring the necessary network settings between the virtual machines and ensuring communication between all of them.
- Assigning static addresses and bridging networks between the vritual machines.
- Using builtin tools in Kali Linux e.g.Social Engineer Toolkit (SET)to clone a webiste and capture the login credentials.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Nmap: for sending packets and analyzing the responses
- Social Engineer Toolkit (SET) to clone a specific website.

## Steps I followed

Firstly, I will determine which hypervisor I will use to conduct this project and discovered that using VirtualBox by Oracle is going to be the best choice for this project. Seeing as the project required me to create 3 virtual machines and configure 80GB of storage and at least 1024MB of memory, but 50GB for the Kali Linux machine. Also considering the amount of memory and storage available on the host machine.

1)	Choose a virtualization platform: VirtualBox Oracle
2)	Created 3 virtual machines
  a)	VM1—Metasploitable 2
  b)	VM2: Kali Linux
  c)	VM3: Windows 10 Client Machine
3)	Subsequently, I configured the VM hardware resources as instructed. Specifically, the CPU (number of virtual CPUs or cores), the RAM for each VM, disk space, and the network configurations. For the VMs to be able to communicate, I created my own internal network on the virtualization platform and set the network adapter to NAT.
4)	Then proceeded to install the different OSs’ by mounting the ISO files and following the installation steps.
5)	After that, I then configured the network and host names and then statically assigned the required IP addresses and configured the required permissions on the Windows machine to be able to communicate with the other VMs. Tested the connectivity by pinging each machine with each other.
6)	Proceeded with running the required updates on all the VMs and latest patches, configured the firewall, and set any user accounts and permissions.
7)	I then verified the resource usage to make sure everything is running smoothly.
8)	Document the IP addresses, login credentials, installed applications, and any other relevant configurations.


![image](https://github.com/user-attachments/assets/81fc2f2b-2d6b-4e44-b5c4-e6471f3147c4)
*Ref 1: Nmap scan on the target machine*

![image](https://github.com/user-attachments/assets/d366d3bf-ef48-40dd-b3e0-ddd951c12233)
*Ref 2: The Social-Engineer Toolkit (SET)*

![image](https://github.com/user-attachments/assets/613aa91a-a8b6-4778-85ed-1ad44b049c90)
*Ref 3: SET login details of the target successfully captured.*

![image](https://github.com/user-attachments/assets/3bce7416-405d-4d07-907d-f2145d1cee7b)
*Ref 4: Screenshot of the cloned website.*
