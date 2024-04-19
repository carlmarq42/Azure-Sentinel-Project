<h1>Azure Sentinel Project</h1>



<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://github.com/carlmarq42/Azure-Sentinel-Project/assets/165202865/5c1546f0-8deb-4671-9d2e-1c6b95e2510a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Virtual Machine in Microsoft Azure: <br/> 
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/e38c0fce-8548-43c9-9fac-211c3432172c" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Allow Ports : <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/c26ecb4a-bd07-4b18-afeb-618cd143456b" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Log Analytics Workspace:  <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/1fb89489-3d1e-4b9f-875b-5804cc6d7198" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remote Login into VM:  <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/967d4248-336c-4087-b301-b0ddb396cb33" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Disable Firewall:  <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/774f5b78-60a0-497b-9674-ea3b5a4868f1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Custom log to Extract & Analyze Logs:  <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/f44c25e0-eb81-4409-b010-ac1e6b24a8d1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Observe the wiped disk:  <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/c3dd49fb-ee48-4da2-8f53-5f5e1c52f421" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://github.com/carlmarq42/Oracle-VM-/assets/165202865/8f23a35f-3561-493e-94d6-c2482ffedde0" height="80%" width="80%" alt="Disk Sanitization Steps"/>

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
