<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial, I will demonstrate how to set up osTicket configurations from the perspectives of customers and agents.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>
- Windows 10</b> (21H2)
<h2>Post-Install Configuration Objectives</h2>

- Create Roles 
- Assign Roles

<h2>Configuration Steps</h2>
<p>
<b>Configure Roles</b><br />
The first thing we will do is create the role of Supreme Admin. With thise role, every permission is granted. Be sure creating this role, you are creating it on the Admin panel. It is located in the top right corner of the osTicket homepage, right next to where it says "Welcome (insert name here)." we will be switching between Admin and Agent panel, so be sure to always be cognizant of this. Open the Admn panel, select Agents and click "Add Role" at the very bottom. <br />
<img src="https://i.imgur.com/t7pNklJ.png"/><br />
<img src="https://i.imgur.com/IeVX11J.png"/><br />
<img src="https://i.imgur.com/7WHb3sg.png"/><br />
<h2>Configure Departments</h2><br/>
From here, we will create a new Department for our System Administrators. From the Admin panel, click on the Agents menu and select Departments to create a new Department. <br />
<h2>Configure Teams</h2>
In addition to our Level I Support Team (which was automatically created), we will need to create a new Level II Support Team. To do this, switch to the Admin panel and click the Teams tab. At the bottom, click "Add New Team" and create the Level II Support Team.<br />
<h2>Configure Agents</h2>
Now, we need to create our workers, or Agents. They will be responsible for responding to and resolving incoming tickets. To do this, make sure you are viewing osTicket from the Admin panel. Open the Agents tab and click on Add New Agent. Each agent will have different assigned responsibilities. For the sake of this lab, we will name them Jane Doe and John Doe. <br />
<h2>Configure Users</h2>
Next, we will need to create users who are able to submit tickets, so that Jane and John can access them. Switch over to he Agents panel, click on the Agents tab, and select "Add User." For the sake of this lab, we will just use the names Ken and Karen. <br />
<h2>Configure SLA</h2>
We will need to create SLAs (Service Level Agreements) for this portion of the lab as well. SLAs categorize tickets from least to most urgent. They will also have time frames. In order to do this, switch back over to the Admin panel. Click on the Manage tab and select "Add New SLA Plan." In this lab, we will create three new SLA plans: Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7) and Sev-C (8 hours, business hours). <br />
<h2>Create Help Topics</h2>
The last thing we will do is create Help Topics that will be submitted by our users who are having IT related issues. Each topic will be different with different levels of severity and time frames. To create a new Help Topic, switch over to the Admin panel. Click on the Manage tab. From there, click on Help Topics and then click "Add New Help Topic." For the sake of this lab, we will create four different tickets: Personal Computer Issues, Password Request, Business Critical Outage, and Equipment Reset. <br />
<h2>Final Word</h2>
osTicket configurations are now set up and complete. we have set up our very own ticketing system as if this were a real life situation. We can now assess each Help Topic from the Administration perspective and assign roles as needed. Click <a href="https://github.com/joshmadakorcc/ticket-lifecycle">here</a> to continue. 
<br />
</p>
<br />
