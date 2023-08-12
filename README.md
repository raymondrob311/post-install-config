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

<h2>Post-Install Configuration Objectives</h2>

- Create Roles (workers and customers) within osTicket 
- Assign Roles
- Create Tickets 
- Resolve Tickets 


<h2>Configuration Steps</h2>
<p>
<b>Configure Roles</b><br />
-Admin Panel -> Agents -> Roles<br />
-Supreme Admin<br />
<img src="https://i.imgur.com/t7pNklJ.png"/><br />
<img src="https://i.imgur.com/IeVX11J.png"/><br />
<img src="https://i.imgur.com/7WHb3sg.png"/><br />
<b>Configure Departments<br /></b>
Admin Panel -> Agents -> Departments<br />
System Administrators<br />
<b>Configure Teams<br /></b>
-Admin Panel -> Agents -> Teams<br />
-Level I Support<br />
-Level II Support<br />
<b>Allow anyone to create tickets<br /></b>
-Admin Panel -> Settings -> User Settings<br />
-Registration Required: Require registration and login to create tickets<br />
<b>Configure Agents (workers)<br /></b>
-Admin Panel -> Agents -> Add New<br />
-Jane<br />
-John<br />
<b>Configure Users (customers)<br /></b>
-Agent Panel -> Users -> Add New<br />
-Karen<br />
-Ken<br />
<b>Configure SLA<br /></b>
-Admin Panel -> Manage -> SLA<br />
-Sev-A (1 hour, 24/7)<br />
-Sev-B (4 hours, 24/7)<br />
-Sev-C (8 hours, business hours)<br />
<b>Configure Help Topics<br /></b>
-Admin Panel -> Manage -> Help Topics<br />
-Business Critical Outage<br />
-Personal Computer Issues<br />
-Equipment Request<br />
-Password Reset<br />

<br />
</p>
<br />
