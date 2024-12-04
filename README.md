<h1>Active Directory Home Lab </h1>

<h2>Description</h2>
This project demonstrates the creation of a home lab environment featuring Active Directory, utilizing Windows Server 2019 within Oracle VirtualBox. It provides a comprehensive walkthrough of configuring and deploying a virtualized domain controller, including setting up the necessary infrastructure and implementing core functionalities followed with a tutorial by Josh Madakor
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Server 2019</b> 

<h2>Program walk-through:</h2>

<p align="center">
Diagram: <br/>
<img src="https://i.imgur.com/Rd8Lcox.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
<br />Set up the virtual machine with two network adapters: one dedicated to internet connectivity and the other for the private network:<br/>
<img src="https://i.imgur.com/hEd1zA7.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/xgqlVhZ.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/sXVl3nD.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
install the following IP address to the Internal Network: <br/>
<img src="https://i.imgur.com/c0mdGLy.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Name the server and install Active Directory to create the domain:  <br/>
<img src="https://i.imgur.com/qfssHEb.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/tkuIheB.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Add a user to the Domain and give them Admin Permission:  <br/>
<img src="https://i.imgur.com/w8v3llL.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/MO3lqmr.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Set up routing to enable clients on the private network to access the internet via the domain controller. :  <br/>
<img src="https://i.imgur.com/eWFFB4T.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Set up DHCP on the domain controller.:  <br/>
<img src="https://i.imgur.com/l69A2hD.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/eud9b11.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/960QbkO.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Create Users with Powershell script:  <br/>
<img src="https://i.imgur.com/NTF8dAo.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Create a virtual machine named "Client1" and install Windows 10 as its operating system: <br/>
<img src="https://i.imgur.com/aR73iEL.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Link the client machine to the private network and add it to the domain:  <br/>
<img src="https://i.imgur.com/beKcNsV.png" height="80%" width="80%" alt="Active Directory steps"/>
<img src="https://i.imgur.com/2oLr5sN.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />
Log back into the DC and ensure Client 1 is active:  <br/>
<img src="https://i.imgur.com/RU4GoHD.png" height="80%" width="80%" alt="Active Directory steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>


</p>
