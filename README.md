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

- Configuring Departments
- Configuring Agents
- Configuring users
- Configuring Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/VRH5XbA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here we're loggin in to osTicket as admin where we have full access over system setting, workflow configuration, setting up the structure, controlling access, and ensuring smooth operations for both agents and users.
</p>
<br />

<p>
<img src="https://i.imgur.com/b9r0LuF.png" alt="Disk Sanitization Steps"/>
</p>
<p>
To organize ticket visibility and responsibilities in osTicket, We configured different Departments through the Admin Panel. By navigating to Admin Panel → Agents → Departments.I created specific departments (SysAdmin) to ensure ensures that tickets are automatically routed to the appropriate team based on the issue type.
</p>
<br />



<p>
<img src="https://i.imgur.com/jIpWnbB.png" alt="Disk Sanitization Steps"/>
</p>
<p>
To set up the support staff in osTicket, We went to Admin Panel → Agents → Add New to create agent accounts. I added an agent named Jane Doe, assigning her to the SysAdmin department and giving her appropriate permissions to manage technical tickets
</p>
<br />

<p>
<img src="https://i.imgur.com/xbJOIYg.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We add end-user account through the Agent Panel → Users → Add New. We created a user named Will ben, who represents a typical customer needing IT support. Will can access the system through the public-facing osTicket portal to create, view, and respond to tickets
</p>
<br />


<p>
<img src="https://i.imgur.com/W5IJK81.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To guide users when submitting tickets, We configured Help Topics by navigating to Admin Panel → Manage → Help Topics. Users can select when creating a ticket, helping ensure their request is directed to the appropriate team. We created several useful topics, including Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other. These options help users describe their issue more clearly and allow helpdesk agents to prioritize and handle tickets more efficiently based on the nature of the request.
</p>
<br />
