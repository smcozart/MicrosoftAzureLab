<h1>Microsoft Azure Lab</h1>

<h2>Description</h2>
Configured VM and firewall for remote access within Microsoft Azure. Used a custom PowerShell script to extract Windows Event Viewer metadata for geolocation using a third-party API. Established a Log Analytics workspace in Azure for custom geographic logs. Configured fields for Azure Sentinel geo-mapping. Implemented a Sentinel workbook, displaying global RDP brute force attacks on a world map. Enhanced security and threat visualization for the purpose of increasing overall security posture.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Azure Log Analytics Workspace</b>
- <b>Azure Sentinel</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center">
Project Goals: <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/df2cc7f4-f109-4817-9779-57fefeba2a16" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating & Configuring Network and VM:  <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/b5843ed0-4610-4198-beb0-6c25732767bc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Disabling Firewall on VM: <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/e17bd412-47cf-4ddb-835a-9350f6b2c228" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Monitoring RDP Brute Force Attempts:  <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/56b19324-e150-4b82-ad32-8ff86767ee0f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Utilizing PowerShell Script & API to Log Failed Attempts and Geolocation:  <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/053f15ff-f9e9-4a9a-a039-217476036efd" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Custom Log Set to Extract Data from PowerShell Script:  <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/0e00bea7-48ca-4905-8eb2-004512b43098" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Azure Sentinel Workbook Creation Linking Custom Log - Final Results:  <br/>
<img src="https://github.com/smcozart/MicrosoftAzureLab/assets/148355955/f14f5607-d264-4c83-8ad6-3654b2847709" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
