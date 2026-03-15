<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1> 
This lab demonstrates how Network Security Groups (NSGs) control traffic between Azure Virtual Machines and how Wireshark can be used to capture and analyze that network communication. The goal is to observe how security rules impact connectivity and packet flow within an Azure virtual network. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 11
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Deploy Virtual Machines
- Created two Windows Virtual Machines in the same Virtual Network
- Verified both machines were running and accessible
- Installed Wireshark on VM1
- Configured packet capture on the primary network interface
- Created inbound rules to allow or deny specific traffic

<h2>Actions and Observations</h2>
<img width="1366" height="737" alt="Capture" src="https://github.com/user-attachments/assets/8747be02-9fd0-4590-bb7f-a6ad2d16027f" />
<img width="990" height="637" alt="Capture" src="https://github.com/user-attachments/assets/0c4180c9-8f3b-4ef5-8124-b34abb6fa596" />


Azure Virtual Machine 


<p>
</p>
<p>
An Azure Resource Group was created. Within this resource group, both Linux and Windows Virtual Machines were deployed to support the environment. Secure access to the Windows Virtual Machine was established using Remote Desktop. After connecting to the VM, Wireshark was installed to enable network traffic analysis and packet inspection.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
