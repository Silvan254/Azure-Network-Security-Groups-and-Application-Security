# Azure-Network-Security-Groups-and-Application-Security
I will set up virtual networking for my organization with two server groups: Web Servers and Management Servers, each in its own Application Security Group. I'll configure rules to allow RDP to Management Servers, IIS access to Web Servers, and restrict RDP to Web Servers.  Lab Objectives: Create network infrastructure. Deploy VMs and test filters.

Network and Application Security Groups diagram


![image](https://github.com/user-attachments/assets/b9765f2d-4e30-4d82-bf2b-1613dc7e78f5)


#Exercise 1: Create the virtual networking infrastructure
Task 1: Create a virtual network
![image](https://github.com/user-attachments/assets/addd283f-94a2-4a8d-ae84-85f061985a0b)

![image](https://github.com/user-attachments/assets/e9219a66-d6a4-45d0-bb9d-181c8ba43217)

On the IP addresses tab of the Create virtual network blade, set the IPv4 address space to 10.0.0.0/16, and, if needed, in the Subnet name column, click default, on the Edit subnet blade, specify the following settings and click Save:
![image](https://github.com/user-attachments/assets/6c41d899-7e36-4e72-bd20-7b25bc61396e)


