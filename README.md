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

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To configure the Admin/Analyst login page, navigate to the following URL:
  [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php).
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  For End Users, the osTicket URL is: [http://localhost/osTicket](http://localhost/osTicket). Users can access the ticketing system and create support requests.
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To configure roles (grouping permissions), go to the Admin Panel -> Agents -> Roles. You can assign roles like Supreme Admin based on user access levels.
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To configure departments (ticket visibility), go to Admin Panel -> Agents -> Departments. You can add different departments like SysAdmins, Help Desk, and Networking for visibility control.
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Configure teams by going to Admin Panel -> Agents -> Teams. Teams allow you to group agents from different departments, such as Online Banking, for ticket assignment and visibility.
</p>
<br />

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
  To configure agents (workers), go to Admin Panel -> Agents -> Add New. You can add agents like Jane (Dept: SysAdmins) and John (Dept: Support).
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To configure users (customers), go to Agent Panel -> Users -> Add New. You can add users like Karen and Ken to the system for ticketing purposes.
</p>
<br />

<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
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
