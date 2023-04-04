<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager for IIS
- Rewrite Module
- PHP 7.3.8
- VC_redist.x86.exe.
- MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/rKOcjm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Install or Enable IIS in Windows with CGI
</p>
<br />

<p>
<img src="https://i.imgur.com/CVRPG90.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2. Download PHP manager for IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/Pma7cyS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/uWXZ4sc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3. Download Rewrite module (rewrite_amd64_en-US.msi) and create the directory C:/PHP
</p>

<p>
<img src="https://i.imgur.com/0MR407g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/HP5uUHe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4. Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip into file C:/PHP
</p>

<p>
<img src="https://i.imgur.com/455tSYQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5. Download VC_redist.x86.exe
</p>

<p>
<img src="https://i.imgur.com/Ntl4G0s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/HKuiydN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/FDcmjws.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6. Download MySQL 5.5.62, choose TYPICAL install. Choose standard configuration, choose password, and click execute
</p>

<p>
<img src="https://i.imgur.com/V2DJpzi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/3s6iynS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/lcffZYV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/u3fHwpq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TRsRboV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/V2DJpzi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7. Open IIS as an Admin and register PHP within IIS, restart or reload IIS once complete.
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 8. Download Rewrite module (rewrite_amd64_en-US.msi) and create the directory C:/PHP
</p>
<br />
