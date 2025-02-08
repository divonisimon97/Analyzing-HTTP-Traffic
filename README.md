# <h1>Analyzing HTTP Traffic </h1>

<h2>Description</h2>
In this project, I use Wireshark to capture and inspect unencrypted HTTP traffic, focusing on how sensitive data, such as login credentials, can be exposed when transmitted over non-HTTPS connections.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> (4.4.3)
- <b>Test HTTP Website</b> (http://testphp.vulnweb.com/login.php) 

<h2>Environments Used </h2>

- <b>Windows 11</b> (24H2)
- <b>PfSense</b> (Version 2.7.2)

<h2>Program walk-through:</h2>

<p align="center">
Launch Wireshark: <br/>
<img src="https://i.imgur.com/oxEMPCt.png" height="80%" width="80%" alt="Launch Wireshark"/>
<br />
<br />
Capture Traffic: <br/>
<img src="https://i.imgur.com/yDTyAB4.png" height="80%" width="80%" alt="Capture Traffic"/>
<br />
<br />
Launch the utility & enter login info: <br/>
<img src="https://i.imgur.com/inuqTYk.png" height="80%" width="80%" alt="Test Website"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
