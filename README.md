# Home-Network-Project
<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2> Utilities Used</h2>

- <b>Command Prompt</b> 
- <b>TextEdit</b>
- <b>Cisco Packet Tracer</b>

<h2>Environments Used </h2>

- <b>MacOS Sonoma</b> 

<h2>Building the network through steps:</h2>

<p align="center">
Launch the utility: <br/>
<br />
<br />
<img src="https://i.imgur.com/8q8xOXJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Place the network topology. Then connect the computer to the network and set the password and number of devices allowed on the network:  <br/>
<br />
<br />
<img src="https://i.imgur.com/k6Uf8to.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/NrnzYup.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/WvLdV9c.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/fv9UVcT.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
Set up the Server and Printers reserved IP adresses by using their MAC addresses: <br/>
<br />
<br />
<img src="https://i.imgur.com/m5KljZh.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/9n2hTa0.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/fv9UVcT.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
Next create the wireless network and setup the security using WPA2:  <br/>
<br />
<br />
<img src="https://i.imgur.com/wLLGQxU.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/f4Daun0.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
Quick example of setting up a guest network for a group of laptops to join:  <br/>
<br />
<br />
<img src="https://i.imgur.com/MyixWwp.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/kuC3Hql.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
And one final example of MAC filtering by using the laptop MAC adresses and filtering them from joining:  <br/>
<br />
<br />
<img src="https://i.imgur.com/cgqasHF.png" width="80%" alt="Home Network Steps"/>
<br />
<br />
<img src="https://i.imgur.com/obc7p0N.png" height="80%" width="80%" alt="Home Network Steps"/>
<br />
<br />
Final image of the Network in full effect (without MAC Filtering):  <br/>
<br />
<br />  
<img src="https://i.imgur.com/3XWFhST.png" height="80%" width="80%" alt="Home Network Steps"/>
</p>
