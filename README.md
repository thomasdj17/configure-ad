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
- Group Policy

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Created Domain Controller and a Virtual CPU
- Assigned the Virtual CPU to the Domain Controller Private IP
- Created Organizational Groups within the domain controller
- Assigned the Admin of the virtual CPU into the domain controller
- Created employee users with Powershell ISE
- Logged into the domain controller using the employee user's information

<h2>Deployment and Configuration Steps</h2>

 <p> 
<img src="https://i.imgur.com/XkV6EQm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
The IP address of the client computer is being assigned to the same private network as the domain controller
<br />
</p>
<p>
</p>
<p>
 
<p>
<img src="https://i.imgur.com/aOV7LY7.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
Building an Organizational Unit within the domain controller for employees and admin
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/Bv4c9as.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Build and Organizational Unit for the original CPU admin and assign it
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/Ipps5f2.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
Create new employee accounts using Powershell ISE for the domain controller
</p>
<br />
</p>
<p>
</p>
<p>

<p>
<img src="https://i.imgur.com/f0glHqD.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
Make sure that the employee account is able to sign in successfully
</p>
<br />
