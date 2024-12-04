<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Command Prompt
- PowerShell
- WireShark

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create virtual machine
- Log into virtual machine with Remote Desktop
- Retrieve IP
- Ping a public site using Powershell
- Observe the ping traffic in WireShark

<h2>Deployment and Configuration Steps</h2>

 <p> 
<img src="https://i.imgur.com/P9f6XqS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the Virtual Machine being created in Azure
</p>
<br />
</p>
<p>
</p>
<p>
 
<p>
<img src="https://i.imgur.com/93KKcVv.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows logging into the virtual machine
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/QeehDgp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the private IP address of Virtual Machine being searched and found
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/UiFg89X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the use of powershell inside the virtual machine sending a ping to another machine
</p>
<br />
</p>
<p>
</p>
<p>


<p>
<img src="https://i.imgur.com/ium0TJi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The picture above shows the reply being sent back to our machine through Wireshark
</p>
<br />
