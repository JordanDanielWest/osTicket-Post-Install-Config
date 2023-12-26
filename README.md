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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Make Ticket creation available to anyone
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<h3>Configure Roles</h3>
</p>
<p>
- Switch to Admin Panel
  
![image](https://github.com/JordanDanielWest/osTicket-Post-Install-Config/assets/96628562/4d3c02ca-88a0-4637-9a59-9454104fd7c5)

- Under the Agents tab select Roles
- Add New Role

![image](https://github.com/JordanDanielWest/osTicket-Post-Install-Config/assets/96628562/62a09a8e-ce23-4a21-9ae9-f38f84cac66f)

- Name: Supreme Admin
- Permissions: Select all ticket features and tasks
- Click Add Role

<h3>Configure Departments</h3>
</p>
<p>
  
- Under Agent Tab select Departments
- Add New Department
- Name: System Administrators
- Add Department

<h3>Configure Teams</h3>

- Under Agent Tab select Teams
- Add New Team
- Name: Level II Support
- Create Team

<h3>Allow anyone to create tickets</h3>

- Under the Setting Tab select Users
- Ensure "Require registration and login to create tickets" box is not checked

<h3>Configure Agents</h3>
<h4>Jane Doe the System Administrator</h4>

- Under the Agents tab select Agents
- Add New Agent
- Name: Jane Doe
- Email Address: jane.doe@helpdesk.com
- Username: Jane
- Select Access Tab
- Primary Department: System Administrators
- Supreme Admin
- Exteneded Access: Support
- Create

<h4>John Doe Helpdesk Tech</h4>

- Under the Agents tab select Agents
- Add New Agent
- Name: John Doe
- john.doe@helpdesk.com
- Primary Department: Support
- All Access
- Create

<h3>Configure Users(Customers)</h3>

In osTicket users are associated with their email address in the User Directory of the help desk

- Select Agent Panel at the top of the screen

![image](https://github.com/JordanDanielWest/osTicket-Post-Install-Config/assets/96628562/4ebf6623-7cf5-4942-a232-0e6e9d9c9303)
- 


- 

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
