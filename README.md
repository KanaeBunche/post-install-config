<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Admin/Analyst Login Page
- Configure End Users osTicket URL
- Configure Roles and Permissions
- Set Up Departments and Teams
- Enable Ticket Creation
- Configure Agents and Users
- Set Up Service Level Agreements (SLA)
- Configure Help Topics for Ticket Creation

<h2>Configuration Steps</h2>




<h3>Configure Roles (for grouping permissions)</h3>
<iframe width="396" height="361" src="https://www.youtube.com/embed/J0IAWFgxjSQ" title="osTickets Roles" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<h3>Configure Departments (for grouping permissions)</h3>
<iframe width="436" height="245" src="https://www.youtube.com/embed/JqwatCU4EqU" title="Configure Database" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


<h3>Configure Agents</h3>
<p>
  <img src="https://s7.ezgif.com/tmp/ezgif-7-cc24f5d579.gif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3> Configure Teams</h3>
 <img src="https://s6.ezgif.com/tmp/ezgif-6-4613958a27.gif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  
  <h3>Configure Users</h3>
<iframe width="396" height="361" src="https://www.youtube.com/embed/IRuOkFk-tJE" title="Add Users" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

  To configure Service Level Agreements (SLA), go to Admin Panel -> Manage -> SLA. For example, create SLA categories like:
  - Sev-A: Grace Period: 1 hour, Schedule: 24/7
  - Sev-B: Grace Period: 4 hours, Schedule: 24/7
  - Sev-C: Grace Period: 8 hours, Business Hours
</p>
<br />

<p>
  <img src="https://s6.ezgif.com/tmp/ezgif-6-51c91bf8ff.gif" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To configure Help Topics for when users create a ticket, go to Admin Panel -> Manage -> Help Topics. You can set up categories like:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other
</p>
<br />
