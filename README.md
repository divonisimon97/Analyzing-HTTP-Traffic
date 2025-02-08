# <h1>Extracting Login Credentials from HTTP Traffic </h1>

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
<img src="https://i.imgur.com/oxEMPCt.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Capture Traffic: <br/>
<img src="https://i.imgur.com/yDTyAB4.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Launch the Website & Enter Login Info: <br/>
<img src="https://i.imgur.com/inuqTYk.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Filter and Inspect HTTP Traffic:  <br/>
<img src="https://i.imgur.com/KTEkYrf.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Locate HTTP POST request: <br/>
<img src="https://i.imgur.com/baJPWiA.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
Open HTML Form URL Encoded & Extract Login Credentials:  <br/>
<img src="https://i.imgur.com/RLhXII5.png" height="80%" width="80%" alt="Analyzing HTTP Traffic"/>
<br />
<br />
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
