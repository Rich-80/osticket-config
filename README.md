<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Configuration Objectives</h2>

- Configure:
  - Roles
  - Departments
  - Teams
  - Agents
  - Users
  - Service Level Agreement (SLA)
  - Help Topics

<h2>Configuration Steps</h2>

![Screenshot 2025-04-21 165356](https://github.com/user-attachments/assets/52636b1e-5ae2-49cd-a23a-17f87c5f97c6)



</p>
<p>
First, configure the role for Supreme Admin. Making sure you are in the Admin Panel (found in the top right), we will add a new role Agents>Roles>Add New Role. Name the role "Supreme Admin" and check all boxes in Permissions before creating.
</p>
<br />

![Screenshot 2025-04-21 165415](https://github.com/user-attachments/assets/e4c75b03-3f03-467e-8c52-7e195db1faa0)


</p>
<p>
Remaining in the Admin Panel, Agents>Departments>Add New Department. Name the department "System Administrators" and create.
</p>
<br />

![Screenshot 2025-04-21 165434](https://github.com/user-attachments/assets/3383c276-4b6b-4dd4-98b1-3c99a460c9de)


</p>
<p>
Remaining in the Admin Panel, Agents>Teams>Add New Team. Name the team "Level II Support", add appropriate members in the "Members" tab, and create team.
</p>
<br />

![Screenshot 2025-04-21 165452](https://github.com/user-attachments/assets/89f7f1b6-e651-4717-b4ac-23bda87a23eb)


</p>
<p>
In the Admin Panel, Agents>Agents>Add New Agent. Name the agent and provide a username for the agent. In the 'Access' tab, select the department and the role and add to a team in the 'Teams' tab, if appropriate. 
</p>
<br />

![Screenshot 2025-04-21 165508](https://github.com/user-attachments/assets/5b449b4c-bb25-4a5d-ad12-0b6c7e25e170)


</p>
<p>
Switching to the Agent Panel (located in the top right), we will create the users who can submit tickets. Provide the name and email of the user being added, and create.
</p>
<br />

![Screenshot 2025-04-21 165524](https://github.com/user-attachments/assets/0892cf94-ab2a-4825-8993-026c52008a1b)


</p>
<p>
Switching back to the Admin Panel, we will create the Service Level Agreements (SLA). Manage>SLA>Add New SLA. For this example, we will create three SLAs with different severities. SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), and SEV-C (8 hours, business hours).
</p>
<br />

![Screenshot 2025-04-21 165538](https://github.com/user-attachments/assets/e9ab273e-69aa-476c-b66f-d62f52c55fd7)


</p>
<p>
Lastly, we will create the topics. In the Admin Panel, Manage>Help Topics>Add New Help Topic. For this example, we will create four topics called "Business Critical Outage", "Personal Computer Issues", "Equipment Reset", and "Password Reset".
</p>
<br />
