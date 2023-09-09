<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
  

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
  

<h2>Deployment and Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/BXcMuda.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created the Domain Controller VM (Windows Server 2022) named “DC-1”, then I Set the Domain Controller’s NIC Private IP address to be static. Next I created the Client VM (Windows 10) named “Client-1”.
</p>
<br />

<p>
<img src="https://i.imgur.com/o2PJ9X0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I have completed the comprehensive installation and configuration of Microsoft Active Directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/JDk8BYC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Active Directory Users and Computers (ADUC), I created an Organizational Unit (OU) called “_EMPLOYEES”.
<br />
