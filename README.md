<h1>PowerShell Practice</h1>


<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows Server 22</b> (64bit)

<h2>Program walk-through:</h2>

<p align="center">
Get-Content: <br/>
<img src="https://i.imgur.com/VAt1CHr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ForEach-Object:  <br/>
<img src="https://i.imgur.com/GUy5p52.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Out-File: <br/>
<img src="https://i.imgur.com/sLE1pT9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Test-NetConnection: <br/>
<img src="https://i.imgur.com/sFPX4QZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/nKZThmG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/oppZLVV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
ConvertTo-Json:  <br/>
<img src="https://i.imgur.com/PyK01gl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Get-Date:  <br/>
<img src="https://i.imgur.com/NlrBagg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TGQuqup.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Get-Command:  <br/>
<img src="https://i.imgur.com/fSsVopV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Get-Help:  <br/>
<img src="https://i.imgur.com/jbVgMec.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
