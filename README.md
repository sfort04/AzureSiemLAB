![image](https://github.com/sfort04/AzureSiemLAB/assets/46600225/81003547-223a-42d9-922c-0cf156117164)<h1>Failed RDP to IP Geolocation Information</h1>


 ### [YouTube Demonstration (@16:20)](https://youtu.be/RoZeVbbZ0o0?t=980)


<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/3d3CEwZ.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from Paraguay coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://github.com/sfort04/AzureSiemLAB/assets/46600225/b4257d6e-d291-4e03-9ba8-bb1f20bbd417" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after finishing lab (built custom logs including geodata)</h2>

<p align="center">
<img src="https://github.com/sfort04/AzureSiemLAB/assets/46600225/daf38148-0075-4a5b-b98d-49ab18f238e8" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<p align="center">
<img src="https://github.com/sfort04/AzureSiemLAB/assets/46600225/5f247a2b-904e-4ec8-824a-2f69bdcef873" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
