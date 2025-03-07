<h1>Viewing and Analysis of Linux Event Logs</h1>

<h2>Description</h2>

In this lab I will be viewing and analysing linux security logs.
<h2>Lab walk-through:</h2>

#### Nevigating to events log directory
- Event logs are located in the /var/log directory

<p align="center"><img src="https://i.imgur.com/I5lZFRn.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>
<br />

 - **`cat auth.log`** to view authentication-related events log
- Windows Logs > Security
<p align="center"><img src="https://i.imgur.com/aW1OEnU.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
- in the right panel we can filter the log for event ID 4625 (logon failure):
<p align="center">
<img src="https://i.imgur.com/SX3S1Ue.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center"><img src="https://i.imgur.com/RfgZZ7G.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>

- C:\Windows\System32\winevt\Logs to view the system logs:
<p align="center"><img src="https://i.imgur.com/pwVpKyD.png" height="50%" width="80%" alt="Disk Sanitization Steps"/><br />

We can double-click on any log to view a detailed information about the captured event.<br />

This concludes the demonstration showing how to configure, view and analyze Windows event logs.
