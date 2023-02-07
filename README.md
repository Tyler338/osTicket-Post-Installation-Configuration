# osTicket-Post-Installation-Configuration
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
- Allow anyone to create tickets
- Configure Agents/Users
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/9FrG9KM.png" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Configure Roles</h2>


- Upon login, toggle to Admin panel
- Select "Agents" from top menu bar
- Select "Roles" from lower menu bar
- Select "Add New Role" to create as many Roles needed for the organization. The Roles are set up according to what access levels each group of members needs depending - upon their departments and abilities to assign or close tickets etc.

</p>
<br />

<p>
<img src="https://i.imgur.com/wSc78ot.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2> Configure Deparments</h2>

- Toggle to Admin panel
- Select "Agents" from the top menu bar
- Select "Departments" from lower menu bar and click "Add New Department" From here, choose the appropriate settings that will apply to the different access levels for the newly created department. Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department.

</p>
<br />

<p>
<img src="https://i.imgur.com/zGuuw77.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Configure Teams</h2>

- Toggle to the Admin panel
- Toggle to "Agents"
- Select "Teams" from lower menu bar and click to "Add New Team" From here, choose the appropriate members for the team and set the access levels that will apply. Configuring Teams will allow Agents from different Departments to be organized to handle a specific issue or user via a Help Topic or Ticket Filter, regardless of the parameters of the Agents' Department rules.
</p>
<br />

<img src="https://i.imgur.com/KSJUyEG.png" width="80%" alt="Disk Sanitization Steps"/>
<h2>Allow anyone to create tickets</h2>

- Toggle to the Admin panel
- Toggle to "Settings" and then select "User Settings"
- Click the "Registration Required" box to allow users to create tickets.
- Click save changes




<img src="https://i.imgur.com/e0SRYX2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/M5LfJIk.png"80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Configure Agents</h2>

- Toggle to the Admin panel
- Select "Agents" from the top menu bar and then select the second "Agents" icon that is located a bit lower to the left of the first one we clicked.
- Select "Add New Agent" to add new workers and assign their Departments and Roles.
- Fill out the information for the added agent by creating login credentials. You can also assign "Access" and "Permissions" here.
- Agents with access to the help desk are responsible for responding to and resolving tickets. Assigning them to a primary department and role helps to ensure that tickets are properly organized and assigned to the most appropriate agent.



<img src="https://i.imgur.com/ikQi1bB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Configure Users</h2>

- Toggle to the Agent panel
- Toggle to "Users" and then click "Add User"
- Fill out information for user and click "Add User" to finalize.

<img src="https://i.imgur.com/dqtso6n.png" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rh1fc92.png" width="80%" alt="Disk Sanitization Steps"/>
<h2>Configure SLA</h2>

- Toggle to the Admin panel
- Toggle to "Manager" and click "SLA"
- Click "Add New SLA Plan"
- Here you can choose the appropriate grace period hours and schedule allowed to respond to Service Level Agreements (SLA Plans). SLA plans are set to provide a length of time for the help desk workers to close a ticket.


<img src="https://i.imgur.com/G0cNTNu.png" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/POGmUmg.png" alt="Disk Sanitization Steps"/>

<h2>Configure Help Topics</h2>

- Toggle to the Admin panel
- Select "Manage" and click "Help Topics"
- Select "Add New Help Topic" and create your own Help Topic.
-Help Topics will help streamline your end user's help desk experience to ensure proper assignment and prompt response to the ticket. Create as many Help Topics as needed. 

