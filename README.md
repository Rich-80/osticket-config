<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure:
  - Roles
  - Departments
  - Teams
  - Agents
  - Users
  - Service Level Agreement (SLA)
  - Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="502" alt="image" src="https://github.com/user-attachments/assets/e4f27dfd-ed61-4713-bd4c-1ef7b12dbdd7" />


</p>
<p>
First, configure the role for Supreme Admin. Making sure you are in the Admin Panel (found in the top right), we will add a new role Agents>Roles>Add New Role. Name the role "Supreme Admin" and check all boxes in Permissions before creating.
</p>
<br />

<p>
<img width="506" alt="image" src="https://github.com/user-attachments/assets/eb634c0e-2202-4d79-b2a8-20fc0820d09a" />

</p>
<p>
Remaining in the Admin Panel, Agents>Departments>Add New Department. Name the department "System Administrators" and create.
</p>
<br />

<p>
<img width="532" alt="image" src="https://github.com/user-attachments/assets/c5089879-0e98-4a54-9e91-aa07cc931fd0" />

</p>
<p>
Remaining in the Admin Panel, Agents>Teams>Add New Team. Name the team "Level II Support", add appropriate members in the "Members" tab, and create team.
</p>
<br />

<p>
<img width="562" alt="image" src="https://github.com/user-attachments/assets/2319079e-e924-4e72-966e-e30434421741" />

</p>
<p>
In the Admin Panel, Agents>Agents>Add New Agent. Name the agent and provide a username for the agent. In the 'Access' tab, select the department and the role and add to a team in the 'Teams' tab, if appropriate. 
</p>
<br />

<p>
<img width="483" alt="image" src="https://github.com/user-attachments/assets/712a7cfd-36a4-44d0-b8f3-23e6d96c4866" />

</p>
<p>
Switching to the Agent Panel (located in the top right), we will create the users who can submit tickets. Provide the name and email of the user being added, and create.
</p>
<br />

<p>
<img width="583" alt="image" src="https://github.com/user-attachments/assets/5c337af7-72a6-4822-9286-c72597634359" />

</p>
<p>
Switching back to the Admin Panel, we will create the Service Level Agreements (SLA). Manage>SLA>Add New SLA. For this example, we will create three SLAs with different severities. SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), and SEV-C (8 hours, business hours).
</p>
<br />

<p>
<img width="599" alt="image" src="https://github.com/user-attachments/assets/01d4d309-ac52-4024-a008-41ff4eea509a" />

</p>
<p>
Lastly, we will create the topics. In the Admin Panel, Manage>Help Topics>Add New Help Topic. For this example, we will create four topics called "Business Critical Outage", "Personal Computer Issues", "Equipment Reset", and "Password Reset".
</p>
<br />
