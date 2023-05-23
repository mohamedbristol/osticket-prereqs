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

- PhPManager for IIS
- Rewrite Module  
- PHP
- VC_redist
- MySQL
- osTicket 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/dlzzqGy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I first started by creating a resource group for my virtual machine to go into. Once I had my resource group, I created a virtual machine and put my resource group into the virtual machine, I then finished setting up my virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/Nx8L9rI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I grabbed my virtual machine's public IP address to remote desktop control (RDC) into the virtual machine I just created.
</p>
<br />

<p>
<img src="https://i.imgur.com/XTHURzM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, via my virtual machine in RDC, I doownloaded PhpManager for IIS and accessed it from my downloads folder to finsih setting it up.
</p>
<br />
<p>
<img src="https://i.imgur.com/gxZm5N9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, I installed Rewrite Module, used to rewrite some URL's ;)
</p>
<br />
<p>
<img src="https://i.imgur.com/7TVIXAt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I downloaded a file named PHP with contents in it. The contents in this file I will unzip into a C/ directory that I created and name PHP. I will simply extract the contents from the right, into the directory to the left.
</p>
<br />

<p>
<img src="https://i.imgur.com/tFD77fE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
VC_redist is an installer for one of the redistributables.
</p>
<br />

<p>
<img src="https://i.imgur.com/sSpkLhS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
MySQL, the second from last step needed, mySQL is simply just a database management system that I used for this lab. 
</p>
<br />

<p>
<img src="https://i.imgur.com/zNrUblb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, osTIcket! The last prerequisite that needed to be installed to get everything up and running smoothly.
</p>
<br />
