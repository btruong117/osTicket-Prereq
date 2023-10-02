<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<!---
<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)
--->
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Internet Information Services (IIS)
- PHP manager
- Rewrite Module
- PHP Installation
- VC redist
- HeidiSQL
- mySQL
- osTicket v1.5.

<h2>Installation Steps</h2>
<br />
<h3>Installing VM</h3>
<p>
<img src="https://i.imgur.com/S3joMyx.png" height="80%" width="80%" alt="VM Creation"/>
</p>
<p>
Since the osTicket instance is going to be hosted on a VM, we'll start with that first. For all intents and purposes, this could be done on any VM manager, but in this case we'll use Azure's Virtual Machine
  Service to host it. Start by going to "Virtual Machines" in your Azure dashboard and create an Windows 10 VM with version 21H2. The specs you pick are at your discretion. Remember to document the username and password you set during the creation process.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2) Next, connect to the VM using Remote Desktop Connection (RDC). RDC using the search bar. Once it is open, enter the public IP address for the VM in the text box(pictured above) and enter the credentials. Keep in mind, if you are running Windows 10 Home on your host system, RDC will not be available for you. The only other option would be to upgrade to Windows 10/11 Pro or use third party software.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3) 
</p>
<br />
