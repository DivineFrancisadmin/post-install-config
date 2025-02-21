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

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Access osTicket Admin/Analyst Panel
- Configure User Roles and Permissions
- User & Agent Management
- Set Up Ticket Management Rules
- Customize Help Topics for Ticket Submission

<h2>Configuration Steps</h2>

<p>
Access osTicket Admin/Analyst Panel
<p></p>
<img width="1032" alt="1  Admin:agent pannel" src="https://github.com/user-attachments/assets/18b4d0ed-7b39-4e4f-98e8-7df114b21b28" />

</p>
<p>
To access the osTicket Admin and Analyst panels, I first ensured that I could reach the necessary interfaces. I opened my browser and navigated to http://localhost/osTicket/scp/login.php to access the Admin/Analyst Login Page, where system administrators and support agents manage ticketing operations. For end users who need to submit and track tickets, I used http://localhost/osTicket. I also familiarized myself with the difference between the Agent Panel, which is used by support staff to handle tickets, and the Admin Panel, where system configurations, roles, and settings are managed.</p>
<br />

<p>
Configure User Roles and Permissions
<p></p>

<img width="1032" alt="2  Assigning Roles" src="https://github.com/user-attachments/assets/a8530bac-fe03-47b4-b360-a13e7d93d7b4" />
</p>
<p>
To configure user roles and permissions in osTicket, I started by defining roles to control access levels. In the Admin Panel, I navigated to Agents → Roles and created a role called Supreme Admin to manage system-wide settings. Next, I set up Departments under Agents → Departments, organizing them based on ticket visibility, such as SysAdmins and Networking, ensuring that tickets were assigned to the appropriate teams. Finally, I structured Teams by going to Agents → Teams and grouping agents from different departments, such as an Online Banking team, to streamline ticket management and improve workflow efficiency.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
