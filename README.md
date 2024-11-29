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

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Departments (for grouping permissions)</h3>
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Configure Roles (for grouping permissions)</h3>
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<h3>Configure Teams (for grouping permissions)</h3>
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  To allow anyone to create tickets, go to Admin Panel -> Settings -> User Settings and uncheck "Unregistered users can create tickets." If registration is required, enable "Require registration and login to create tickets."
</p>
<br />
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
<h3>Configure Agents (for grouping permissions)</h3>
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  <h3>Configure Users (for grouping permissions)</h3>
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  To configure Service Level Agreements (SLA), go to Admin Panel -> Manage -> SLA. For example, create SLA categories like:
  - Sev-A: Grace Period: 1 hour, Schedule: 24/7
  - Sev-B: Grace Period: 4 hours, Schedule: 24/7
  - Sev-C: Grace Period: 8 hours, Business Hours
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
