<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/MrMqc3w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<img src="https://i.imgur.com/QJYEKqI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/33QKu5p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I retrieved the public IP address in Azure, I then launched remote desktop and used the public IP address, user name and password I created in the virtual machine to launch the osTicket virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/FaSOdtQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/s638IZ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Q3JsnZt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/0pyoofC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download the osTicket installation files and set the extraction onto your desktop. These files will be used to launch osTicket and it's dependencies. I went to control panel, programs, on the left click "turn windows features on or off" and Enable IIS(Internet information services). Expand world wide services, application development features and then click on CGI to install. 
</p>
<br />

<p>
<img src="https://i.imgur.com/wI7zNbH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/mwtTW0W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/wI7zNbH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/VT4vXSR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/kY2wWnt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/28y14Lg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/28y14Lg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/bQMjMLD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/oTSIGUt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/rWniffS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/twaDvHm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/YClpW8k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    
</p>
<p>
Go into the installation file and click on PHP Manager and run the install, install the Rewrite Module. Then create a PHP Directory 

Go to the C drive and create a directory for PHP. Create new folder and title it PHP 

From the "osTicket-Installation-Files” folder, right click on the folder titled 
php-7.3.8-nts-Win32-VC15-x86 and extract the files on the C drive in the folder PHP that you created in the previous step. 

From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe 

From the “osTicket-Installation-Files” folder, install MySQL 5.5.62  
</p>
<br />
