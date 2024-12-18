<p align="center">
<img src="https://i.imgur.com/4y6oIkd.png" alt="osTicket logo"/>
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
<p>STEP 18: Create a directory on the C drive called "PHP". To get there, first click on the Manila folder (File Explorer) at the bottom of your screen. </p>
<img src="https://i.imgur.com/AUcEsD9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 19: On left, Click on "This PC" and the click on "Windows C" </p>
    <img src="https://i.imgur.com/TRtgxxZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <p> STEP 20: Create a folder and title it "PHP" make sure all the letters are capitalized </p>
    <img src="https://i.imgur.com/buqJYtu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <p> STEP 21: From the “osTicket-Installation-Files” folder, right click on "php-7.3.8-nts-Win32-VC15-x86" and select "extract all" </p>
<img src="https://i.imgur.com/42cvH8W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>   
<p> STEP 22: Set the location to the C:\PHP and click extract </p>
<img src="https://i.imgur.com/tXZkTxI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/PJoUIPG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<p> STEP 23: All the files should look like the picture below </p>
<img src="https://i.imgur.com/t2wWLox.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p> STEP 24: From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.  </p>
<img src="https://i.imgur.com/lMaCG50.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 25: Select "I agree with the License Agreement" and click "Install" </p>
<img src="https://i.imgur.com/VxY0YNO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/YbiOhtq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/T1RHILO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <P> STEP 26: From the “osTicket-Installation-Files” folder, install mysql-5.5.62-win32.msi </P>
<img src="https://i.imgur.com/cnR9k63.png " height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <P> STEP 27: Click on Next and select "I accept the terms in the License Agreement" </P>
<img src="https://i.imgur.com/yZxv79a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/90c4kcH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 28: Select "Typical" installation and click next, click install  </p>
<img src="https://i.imgur.com/OTz3Il5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/f6JSaPa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/zzHVyAn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/6PafWct.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 29: Install the next wizard and click next </p>
<img src="https://i.imgur.com/Li6DE73.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 30: Select Standard configuration, then click next </p>
<img src="https://i.imgur.com/sX6hyLj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> Leave this screen alone and click next</p>
   <img src="https://i.imgur.com/UMo9J7A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>  
       <p> STEP 31: Choose a root password and don't forget this password. Make sure you write it down on your notepad some where Click next . </p>
<img src="https://i.imgur.com/JvmOxSh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
 <p>STEP 32: Select Excute and then click finish </p>   
<img src="https://i.imgur.com/ebNoTYF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/iduhjVY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 33: Open IIS (Internet Information Service) as an Admin </p>
<img src="https://i.imgur.com/1xtCirO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 34: Click on PHP Manager </p>
<img src="https://i.imgur.com/g81Mlh2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
    <p> Once this box pops up, click on the small box with the three dots so you can browse </p>
<img src="https://i.imgur.com/bN3x34x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
    <p> Click the PHP folder </p>
<img src="https://i.imgur.com/T15nGj5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p>Select the file php-cgi and then click open </p>
<img src="https://i.imgur.com/0En4Iyr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
    <p>  The box will now read C:\PHP\php-cgi.exe and then you click ok </p>
<img src="https://i.imgur.com/HAUkpXJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
   
<p> Register new PHP version </p>

<img src="https://i.imgur.com/XvvJd6y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 39:  Reload IIS (Open IIS, Stop and Start the server) </p>
<img src="https://i.imgur.com/n4FYk7F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<p> Stop the server for a few seconds (10 seconds) </p>
<img src="https://i.imgur.com/xdRdbV4.png " height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> Click on Start for the server to run </p>
<img src="https://i.imgur.com/Uh1ThuP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 41: From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip” by right clicking on the file and extracting it to the same “osTicket-Installation-Files” folder</p>
<img src="https://i.imgur.com/I8yo14I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> Click browse and select “osTicket-Installation-Files” folder that's on the desktop </p>
<img src="https://i.imgur.com/swIM5Ui.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> Now, right click on osTicket-v1.15.8 Folder </p>
<img src="https://i.imgur.com/JHji2Eu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 43: </p>
<img src="https://i.imgur.com/61iS1kH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<p> STEP 44: Load a window, click on windows (C:) drive and click on the folders "inetpub/wwwroot </p>
<img src="https://i.imgur.com/RIyWzmM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
<img src="https://i.imgur.com/wVOVdyd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    
<p> STEP 45: copy the “upload” folder into "wwwroot" folder  </p>
<img src="https://i.imgur.com/oUQVdQK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 46:  Rename “upload” to “osTicket”</p>
<img src="https://i.imgur.com/02YeCw2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 47: Reload IIS and stop the server for 10 seconds   </p>
<img src="https://i.imgur.com/BjuPpLI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 48: After 10 seconds, click on Start </p>
<img src="https://i.imgur.com/T8kvJFA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 49:Go to sites -> Default -> osTicket </p>
<img src="https://i.imgur.com/DNQ3Ruq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 50: On the right, click “Browse *:80 </p>
<img src="https://i.imgur.com/UcF7IfK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 51: Some of the extensions are not enabled, Go back to IIS, sites -> Default -> osTicket
</p>
<img src="https://i.imgur.com/dbbLQK0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> STEP 52: Go back to IIS, sites -> Default -> osTicket, Double click PHP Manager </p>
<img src="https://i.imgur.com/Z9MWlPO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 

 <p> STEP 53: Go to PHP extensions, Click Enable or Disable extension </p>
<img src="https://i.imgur.com/BtXwOp6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

 <p> STEP 54: - Enable: php_imap.dll  </p>
             <p> - Enable: php_intl.dll </p>
             <p> - Enable: php_opcache.dll </p>
<img src="https://i.imgur.com/p59x2vK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
    
<img src="https://i.imgur.com/d1Vew50.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
  
<img src="https://i.imgur.com/kllszvu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
   <p> Refresh the osTicket site in your browser, notice the changes </p>
<img src="https://i.imgur.com/shH3Uh0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
 <p> STEP 55: Rename: ost-config.php
<P> - From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php </P>
<P> - To: C:\inetpub\wwwroot\osTicket\include\ost-config.php </P>
</p>
<img src="https://i.imgur.com/GmEkHen.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
  
<img src="https://i.imgur.com/AkYNeeO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
   <P> Click on the osTicket folder </P>
<img src="https://i.imgur.com/cP9chFj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
   <p> Click on the include folder </p>
<img src="https://i.imgur.com/TSqO5wI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
  <p> Go to the file "ost-sampleconfig.php" 
<img src="https://i.imgur.com/GUpBfSw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 
    <p> Right click and scroll down to "Rename" file to "ost-config.php" </p> </p>
<img src="https://i.imgur.com/2TXOQpC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> Assign Permissions to "ost-config.php"
    
Right click on "ost-config.php" and scroll down to properties. Assign Permissions: ost-config.php
 </p>
<img src="https://i.imgur.com/EkmV19j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
    <p> Click on Security and then click on Advanced  </p>
<img src="https://i.imgur.com/40xIRhP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> STEP 67 Disable inheritance, select apply and then click ok </p>
<img src="https://i.imgur.com/KSHCVIY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
<p> Click on "Remove all inherited permissions from this object" </p>
<img src="https://i.imgur.com/VH60dH8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
<p> Select apply and then click ok </p>
<img src="https://i.imgur.com/LP7APFH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> Click on Principle </p>

<img src="https://i.imgur.com/PdSbgHx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

In the box, Set it for "Everyone" 

<img src="https://i.imgur.com/RSgNS5k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<P> Make sure all permissions are checked off and click ok </P>
<img src="https://i.imgur.com/OKTlj0y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> Click Apply and then click ok </p>
<img src="https://i.imgur.com/HobQCcW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> Click ok </p>
<img src="https://i.imgur.com/cDWo3ZX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> Continue Setting up osTicket in the browser (click Continue) </p>
<img src="https://i.imgur.com/KG8Vszi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p> Name help desk  </p>
<img src="https://i.imgur.com/i659pMr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

<p>  From the “osTicket-Installation-Files” folder, Right click on "HeidiSQL_12.3.0.6589_Setup" and click open </p>

<img src="https://i.imgur.com/BSeClVd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Select "I accept the aggrement" and click next 
<img src="https://i.imgur.com/TlJVMbS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
Click Next 
<img src="https://i.imgur.com/8ARqlYo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
Click Next 
<img src="https://i.imgur.com/q3axqmk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
Click Next 
<img src="https://i.imgur.com/wxYonTT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
Click Next 
<img src="https://i.imgur.com/QNc6Ygp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
At this point, program is installing 
<img src="https://i.imgur.com/xqtCwkW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>
Make sure the box "Laugh HeidiSQL is checked and then click Finish

<img src="https://i.imgur.com/O6ANgWR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Click Skip

<img src="https://i.imgur.com/FmPzFxO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>


Open HeidiSQL 
<img src="https://i.imgur.com/4LQE1Ss.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Create a new session and enter the password "root" which you had set earlier in the installation for MYSQL Server 
<img src="https://i.imgur.com/sWAv2Fw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>


<img src="https://i.imgur.com/BKH0o43.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Hoover over "unnamed" right click and Click "Create New" and then click "Database" 
<img src="https://i.imgur.com/6jtkf1A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Name the database "osTicket" and click ok 

<img src="https://i.imgur.com/04ZZuCh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

You now have a osTicket Database 

<img src="https://i.imgur.com/yfBfo2n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Continue Setting up osTicket in the browser
<img src="https://i.imgur.com/etpvinT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 

Click install

<img src="https://i.imgur.com/F37RVVf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p>

Click Install Now


<img src="https://i.imgur.com/JlWK5Tf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 

<img src="https://i.imgur.com/kT83lzG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><p> 


Congratulations, you have successfully installed osTicket. 



    


