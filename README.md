<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>


---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Acknowledge Agent Panel vs Admin Panel
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img src="https://imgur.com/UJIbBIK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Agent Panel</h2>

<img src="https://imgur.com/FzYCLMx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Admin Panel</h2>

</p>
<p>
There are 2 Panels in OsTicket, one to use as an agent communicating with end users(agent panel) and one to use as an admin to configure settings and assign tickets.
</p>
<br />

<p>
<img src="https://imgur.com/zF1ACb2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/x1GDcLB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/rhjK5fy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles (for grouping permissions) Admin Panel -> Agents -> Roles -> Supreme Admin. Make sure to check off all boxes, we want to give this role total access.
</p>
<br />

<p>
<img src="https://imgur.com/vvz6wMn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a new department called "SysAdmins" by going to Admin Panel -> Agents -> Departments.
</p>
<br />

<p>
<img src="https://imgur.com/5pOgUTE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure teams by going to the admin panel -> Agents -> Teams -> "Add New Team" (we will call this Online Banking).
</p>
<br />

<p>
<img src="https://imgur.com/dlkV51b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We wil now allow anyone to create tickets by making sure this setting is unchecked through the Admin Panel.
</p>
<br />

<p>
<img src="https://imgur.com/Ha5yr2L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/vJFiuGw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h>Configure Agents by going to Admin Panel->Agents->Add New, we will now add Jane Doe and John Doe.</h>


<h2>Give john "Support" and "Supreme Admin" Dept Role through the "Access" tab and "Level 1 Support" with "Online Banking" "Teams" tab.</h2>
<img src="https://imgur.com/sI7Xll6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/60hyO47.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Give Jane "SysAdmins" and "Supreme Admin" Dept role through the "Access" tab and "Level 1 Support" with "Online Banking" "Teams" tab.</h2>
<img src="https://imgur.com/Qlq9nHq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/60hyO47.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
<img src="https://imgur.com/ehNwdfJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/lu4timR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/MQCNOlu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users by going to the Agent Panel->Users->Add New (We will be adding 2 users named Karen and Ken)
</p>
<br />

<p>
<img src="https://imgur.com/nRaQwFv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/LtUJJb1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/MGis4Su.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create 3 New SLAs by going to Admin Panel->Manage->SLA 
</p>
<br />

<p>
<img src="https://imgur.com/rCTNSf7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/3ERrX24.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/K2m2qVb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/nJMtMEY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/HLZNp1w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create 5 new Help Topics (for when users create a ticket) Admin Panel-> Manage-> Help Topics
  
</p>
<br />


