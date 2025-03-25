<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration</h1>
This tutorial outlines the configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments

- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)

- Allow people to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets

- Configure Users (customers)
Agent Panel -> Users -> Add New

- Configure SLA
Admin Panel -> Manage -> SLA

- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
