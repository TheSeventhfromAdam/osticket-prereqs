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
</p>
<p>
Step 7. Open IIS as an Admin and register PHP within IIS, restart or reload IIS once complete.
</p>

<p>
<img src="https://i.imgur.com/MFBrMkw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/qtUX1vv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vf7bmju.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sL03ljP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 8. Download osticket, Extract then copy “upload” folder to c:\inetpub\wwwroot, inside c:\inetpub\wwwroot, Rename “upload” to “osTicket”. Reload IIS (Open IIS and click Stop and Restart)
</p>

<p>
<img src="https://i.imgur.com/EvCZnUS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/5vJgaGy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/IzeLJwZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 9: Go to sites -> Default -> osTicket, click (Browse *:80)
</p>
<br />

<p>
<img src="https://i.imgur.com/hr7BQn3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/sYDx5uW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bdJBS5j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/WA6FhA3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/vmE3OMI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 10: Go to IIS, sites -> Default -> osTicket, double click PHP Manager, Enable: php_imap.dll, Enable: php_intl.dll,Enable: php_opcache.dll. One enabled. Refresh osticket in browser and notice the results
</p>
<br />

<p>
<img src="https://i.imgur.com/ha7oSI3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/iDGW9K7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QGk1XcL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 11: Rename: ost-config.php, Before rename: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php After: C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p>
<br />

<p>
<img src="https://i.imgur.com/LaEVYGA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/BWoIFfK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XClSDoM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/R9KySem.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xFo9lnU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ndDL1vh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/XCUBl1k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 12: Assign Permissions: ost-config.php, Disable inheritance -> Remove All, New Permissions -> Everyone -> All

</p>
<br />

<p>
<img src="https://i.imgur.com/rKOcjm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 13: Continue with Help Desk setup in browser. Name: Helpdesk, Create Email

</p>
<br />

<p>
<img src="https://i.imgur.com/rKOcjm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 14: Download HeidiSQL, create new session, login with password made in step 6

</p>
<br />

<p>
<img src="https://i.imgur.com/rKOcjm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 15: Continue osTicket setup in browser. MySQL Database: osTicket, MySQL Username: root, MySQL Password:(Choose your own), click Install Now
</p>
<br />

<p>
<img src="https://i.imgur.com/rKOcjm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 16: Continue osTicket setup in browser. MySQL Database: osTicket, MySQL Username: root, MySQL Password:(Choose your own)
</p>
<br />

<p>
<img src="https://i.imgur.com/rKOcjm0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 17: Cleaning up Delete: C:\inetpub\wwwroot\osTicket\setup Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p>
<br />
