<p align="center">
 <img src="https://i.imgur.com/3XRSwO2.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Assign File Permissions</h1>


<h2>Description</h2>
Are you ready to take control of your shared folders? Let me tell you why file permissions are crucial for keeping your data safe and sound in Windows.

Picture this: you've spent hours creating a project, saving it in a shared folder. Your colleagues need to access it too, but what if they accidentally delete or modify your hard work? Disaster strikes!

But fear not! File permissions in Windows come to the rescue. They allow you to dictate who can access, modify, or delete files in the shared folder. Without proper permissions, you're putting your precious data at risk of being lost or damaged.

With Windows file permissions, you're the boss. You can specify which users or groups have access to the shared folder and what actions they can perform on the files within it. Whether it's read-only access or full access to read, write, and delete files, you're in control. You can even restrict access to specific files or folders within the shared folder.

So, are you ready to take charge and secure your shared folders in Windows 10? Join me for today's demonstration, and I'll show you how to assign file permissions like a pro!
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2016</b> <p>


<h2>Program walk-through:</h2>

<p align="center">


<br />
Search for Network and Sharing Center.
 <br/>
<img src="https://i.imgur.com/G0FmySd.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Copy your the IP configuration of your primary ethernet adapter.
 <br/>
<img src="https://i.imgur.com/HUbLC6P.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Back in the Server Manager. Click Local Server then under Nic Teaming click the "Disabled" link.

 <br/>
<img src="https://i.imgur.com/1n4rirv.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Click the Tasks pull down menu and then select "New Team"
<br/>
<img src="https://i.imgur.com/47qEOI9.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select and configure your adapters and settings. Research what settings works best for your network. I used the name NetTeam for this demonstration but you can name it whatever you want. Click ok when finished and close all boxes.

 <br/>
<img src="https://i.imgur.com/bDsCrYP.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Enter the IP configuration of our primary adapter from the first step.
 <br/>
<img src="https://i.imgur.com/jmQiPHR.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
That's it! You're done. Should you check the details of the NicTeam interface it should reflect the primary adapter and we're good to go.
 <br/>
<img src="https://i.imgur.com/BPI2puP.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
I hope you enjoyed this demonstration.
 <br/>
<img src="https://i.imgur.com/S5L4DXX.jpg" height="80%" width="80%" alt="DHCP"/>
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
