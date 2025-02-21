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
To set up user roles and permissions in osTicket, I first defined access levels by navigating to Admin Panel → Agents → Roles and creating a Supreme Admin role for system-wide management. Then, I organized Departments under Agents → Departments, assigning categories like SysAdmins and Networking to control ticket visibility. Finally, I structured Teams under Agents → Teams, grouping agents from different departments—such as an Online Banking team—to enhance collaboration and improve ticket management efficiency.<br />
<p></p>
<p>
  <br />
  User & Agent Management
  <p></p>
<img width="955" alt="3  Agent-Jane" src="https://github.com/user-attachments/assets/1abc76fa-c093-4b3c-84fd-f605f44e4e57" />
</p>
<p>
For managing users and agents in osTicket, I began by configuring Agents, who handle support tickets. In the Admin Panel, I navigated to Agents → Add New, created agent accounts, and assigned them to the appropriate departments, such as Jane in SysAdmins and John in Support. Then, I set up Users, who submit tickets, by going to the Agent Panel → Users → Add New and adding users like Karen and Ken to ensure they could request assistance seamlessly.
</p>
<br />
Set Up Ticket Management Rules
<p></p>
<img width="960" alt="4  SLA's" src="https://github.com/user-attachments/assets/2d512799-bbd1-43e5-ae96-e4a778c50bee" />
<p>
<p></p>
To set up ticket management rules in osTicket, I began by configuring the ticket submission policies. In the Admin Panel → Settings → User Settings, I disabled the option "Unregistered users can create tickets" so users don’t have to register before submitting a ticket. Next, I moved on to setting up Service Level Agreements (SLA) under Admin Panel → Manage → SLA. I established different response times based on urgency: Sev-A required a 1-hour response time (24/7), Sev-B was set to 4 hours (24/7), and Sev-C had an 8-hour response time (Business Hours) to ensure efficient ticket handling.
</p>
<br />
Customize Help Topics for Ticket Submission
<p></p>
<img width="954" alt="5  Help Topics" src="https://github.com/user-attachments/assets/6e87bc4a-17d6-400d-a922-31d85b5e6253" />
<p>
To customize help topics for ticket submission in osTicket, I organized predefined ticket categories to streamline user requests. I navigated to Admin Panel → Manage → Help Topics and set up structured categories to help users select the most relevant option when submitting a ticket.
First, I added Business Critical Outage for urgent system-wide issues. Then, I created categories for Personal Computer Issues and Equipment Requests to handle technical support and hardware needs. Additionally, I included Password Reset to assist users with login problems and an Other category for miscellaneous requests.
Setting up these help topics ensures that users can efficiently submit tickets under the correct category, making ticket routing and resolution more effective.

