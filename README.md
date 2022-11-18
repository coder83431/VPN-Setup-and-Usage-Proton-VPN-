<p align="center">
<img src="https://imgur.com/jC9F3V8.png"/>
</p>

<h1>osTicket - Setup and Usage of Proton VPN </h1>
This tutorial outlines the process of retrieving and observing IP addresses while using desktops within differnet locations. We will be observing our own desktop IP address, then within a different location within a Azure virtual machine, and then finally through where are device is connected to on Proton VPN.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (version 22H2)

<h2>Installation Steps</h2>


<p>  
<img src = "https://imgur.com/tPLmzJs.png " height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>Overview</p>

<p>
<img src = "https://imgur.com/4SNVlfC.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 <p>
1. Browse to https://whatismyipaddress.com/ and take note of this in a text file

</p>                                                                                                    
                                                                                                     
<p>
<img src= "https://imgur.com/pPgcdOz.png" " height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

<p>
                                                                                                 
                                                                                                 
                                                                                                 
2.Create a resource group in Microsoft Azure
</p>
<br />




<p>
<img src="https://imgur.com/1pvRT18.png" alt="Disk Sanitization Steps"/>
</p>


<p>
<img src = "https://imgur.com/3HF3a21.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
3. Create a Windows 10 Virtual Machine in another geographic location (try a different country)
Log into the VM with Remote Desktop
Browse to https://whatismyipaddress.com/ and take note of this in a text file
</p>
<br />




<p>
<img src = "https://imgur.com/290CTCp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
<img src = "https://imgur.com/CFGwidV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<p>
4. On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en. Loginto the VPN server and choose a VPN server within another country than your own. Then browse to  https://whatismyipaddress.com/ once more to view your IP address.

</p>
<br />

<p>
<img src="https://imgur.com/8UHGoeX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/KRBIf5T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
5. Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different.

</p>
<br />


<p>
<img src="https://imgur.com/beY8Kft.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


6. Its now time to clean up your Azure resources. Make sure to delete the resource group and resources you created in Step 2 and ensure to disconnect from the Proton VPN server.
