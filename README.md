<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this lab i set up a virtual environment that runs Active Directory and creating a lot of user using PowerShell. I setup VirtualBox and created 2 VMs (Windows 12 server VM, Windows 10). I then run a PowerShell script to created a 1000 new  users that can log into the Virtual Machine using their credentials.
<br />


<h2>Exposure to:</h2>

- <b>Active Directory </b> 
- <b>PowerShell</b>
- <b>Windows Server</b>
- <b>Virtualization (Oracle VirtualBox)</b> 

<h2>Environments Used </h2>

- <b>Oracle VirtualBox</b>
- <b>Windows 12 Server</b>
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Project Overview: <br/>
<img src="https://i.imgur.com/VyOMAf4.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Download Virtualbox:  <br/>
<img src="https://i.imgur.com/w48cOyj.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Download Windows 10 and Windows 2019 Server: <br/>
<img src="https://i.imgur.com/pxVOy3v.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/j89XuXU.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Create Windows Server 2019 VM Machines:  <br/>
<img src="https://i.imgur.com/m8TsFhV.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/HSRwrM4.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/zHkvMpC.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/> 
<br />
<br />
Set Up IP Addressing:  <br/>
<img src="https://i.imgur.com/qqZ24Ih.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/igHTymJ.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/DCyHxIR.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/n9XJDai.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/dleHJd3.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Configuring Post Deployment:  <br/>
<img src="https://i.imgur.com/xTyScdL.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Create A Dedicated Domain Account:  <br/>
<img src="https://i.imgur.com/BmK6ize.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Create Organizational Unit:  <br/>
 <img src="https://i.imgur.com/rd7uUHN.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Create New User:  <br/>
<img src="https://i.imgur.com/vP2FljL.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Make A Domain Admin: <br/>
<img src="https://i.imgur.com/Sv4IFx8.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Set up Routing and Remote Access:  <br/>
<img src="https://i.imgur.com/YZduZ7L.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Install NAT:  <br/>
<img src="https://i.imgur.com/otQtDFi.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/EcEAicn.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Set Up DHCP Server On Domain Controller:  <br/>
<img src="https://i.imgur.com/WroAUfn.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Configure DHCP Options:  <br/>
<img src="https://i.imgur.com/21h1bF9.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/lYeJU1Q.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Write PowerShell Script to Create 1000+ Users:  <br/>
<img src="https://i.imgur.com/8FV0ZT4.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/ePmISDh.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/0wRqrYp.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Set Up Windows 10 VM With Internal NIC:  <br/>
<img src="https://i.imgur.com/9CFzBh2.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/BvI4pgX.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/sRM6gaB.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/GsjHSmg.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/1fsn6PH.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<img src="https://i.imgur.com/lH9ZkW0.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Add Domain Controller for Windows 10 VM:  <br/>
<img src="https://i.imgur.com/s6tbKU0.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Address Leases:  <br/>
<img src="https://i.imgur.com/rwIty35.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
<br />
<br />
Active Directory Users And Computers:  <br/>
<img src="https://i.imgur.com/vkPYhwx.png" height="80%" width="80%" alt="Active Directory/Home Network Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
