# SIEM-Azure-Lab
Build out of a SIEM inside Microsoft Azure


 

<h2>Description</h2>
The project consists of using a custom PowerShell script to pull data from Windows Event Viewer to forward it to a third-party API to extract location data of attempted logins. While configuring Log Analytics in Azure to understand the geographic information it is being fed, i.e. latitude, longitude, and country. Lastly, configuring a workbook inside Azure Sentinel to display and visualize the global attack data based on the physical location of the attacker and amount of attempts.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure Portal</b> 
- <b>Azure Sentinel</b>
- <b>Powershell</b>
- <b>Kusto Query Language</b>
- <b>Network Security Groups</b>



<h2>Environments Used </h2>

- <b>Windows 10 VM</b>

<h2>Program walk-through:</h2>

<p align="center">
Powershell Script <br/>
<img src="https://i.imgur.com/uTutvOm.jpeg" height="80%" width="80%" alt=""/>
<br />
<br />
Powershell Log:  <br/>
<img src="https://i.imgur.com/zkskNcn.jpeg" height="80%" width="80%" alt=""/>
<br />
<br />
Log Analytics Path: <br/>
<img src="https://i.imgur.com/yxMZ34i.jpeg" height="80%" width="80%" alt=""/>
<br />
<br />
Custom Query:  <br/>
<img src="https://i.imgur.com/nMS2bca.jpeg" height="80%" width="80%" alt=""/>
<br />
<br />
Map Visualizer for Login Attempts (Only 1 Hour After Creation):  <br/>
<img src="https://i.imgur.com/c77NgMp.jpeg" height="80%" width="80%" alt=""/>
<br />
<br />
Map Visualizer for Login Attempts (24 Hours Later):  <br/>
<img src="" height="80%" width="80%" alt=""/>
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
