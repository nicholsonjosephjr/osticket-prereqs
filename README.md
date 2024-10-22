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

- Enable IIS, CGI 
- PHP manager 
- Rewrite Module 2 
- VC_redist.x86.exe 
- MySQL 5.5.62 


<h2>Installation Steps</h2>

<p> STEP 1: Download the osTicket-Installation-Files.zip </p>
<img src="https://i.imgur.com/tgt3ufz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<p> STEP 2: Go to your downloads folder and right click on the folder and scroll to Extract All </p>
<img src="https://i.imgur.com/FPKG6b0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 3: Set the destination to desktop and extract all files. The name of the folder should be titled “osTicket-Installation-Files”</p>
<img src="https://i.imgur.com/KdHaToK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rXtaK2D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>STEP 4: I went to control panel, programs, on the left turn windows features on or off and I installed Internet information services and CGI. Expand world wide services, application development features and then click on CGI. Once that's installed, you now can move onto the next step of instalation </p>
<img src="https://i.imgur.com/yx4xm8F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 5: Click on programs</p>
<img src="https://i.imgur.com/x5ECXgx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 6: On the left side of the box that pops up, click on turn windows features on or off</p>
<img src="https://i.imgur.com/tC3Cyy8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 7: Click on Internet Information Services </p>
<img src="https://i.imgur.com/zZud6ZZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 8: Scroll down to World Wide Web Services, click on the plus sign and and expand the options  </p>
<img src="https://i.imgur.com/sY7w1H3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 9: Click on Aplication Development Features, select CGI and click ok. </p>
<img src="https://i.imgur.com/IAVpsnx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/RjgCwiL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/HwzfXWh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 10: From the “osTicket-Installation-Files” folder on the desktop, install PHP Manager for IIS  </p> 
<img src="https://i.imgur.com/wfKdyGE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 11: On the installation wizard, click on next </p> 
<img src="https://i.imgur.com/siONvuD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 12: On the license agreement, select "I agree" and then click on next </p>
<img src="https://i.imgur.com/YVJZ266.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 13: PHP Manager will now install</p>
<img src="https://i.imgur.com/LA9PwVU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 14: Once complete, click on "Close" to exit </p>
<img src="https://i.imgur.com/ga1sSNa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 15: From the “osTicket-Installation-Files” folder on the desktop, install the Rewrite Module </p>
<img src="https://i.imgur.com/mtQtyqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 16: Check the box "I accept the terms in the License Agreement, then click "Install" </p>
<img src="https://i.imgur.com/hRG8Ulz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/68sL38j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 17: Once the installation is complete, click on "Finish" </p>
<img src="https://i.imgur.com/SP92ZxF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>STEP 18 </p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 20  </p>
    


    
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
