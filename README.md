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

- Configure Roles <br>

- Configure Departments <br>

- Configure Teams <br>

- Configure Agents <br>

- Configure Users <br>

- Set up Service Level Agreements (SLAs) <br>

- Configure Help Topics <br>

<br><br>


<h2>Configuration of Roles</h2>

1. Admin Panel > Agents > Roles
   
2. Supreme Admin

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/0cb28f10-dc4b-4f6b-9eaf-8ffbc65d84ab">

</p>

Set up the 'Supreme Admin' role and grant it the necessary permissions for complete control, in line with its high-level administrative function.

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/bc96d30d-fc37-43c3-884d-c1e4b7ae13e0">

</p>

<br><br>


<h2>Configure Departments</h2>

1. Admin Panel > Agents > Departments

2. System Administrators

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/1446fc05-8417-48a7-9af8-68e227822562">

</p>

<br><br>


<h2>Configure Teams</h2>

1. Admin Panel > Agents > Teams

2. Level I Support

3. Level II Support

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/147a29e4-f9fd-419d-9580-a80816751215">

</p>

<br><br>


<h2>Allow Anyone to Create Tickets</h2>

1. Admin Panel > Settings > User Settings

2. Registration Required: Require registration and login to create tickets

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/c3b39bdf-2adc-4928-88ae-03f18922c62a">

</p>

<br><br>



<h2>Configure Agent</h2>

1. Admin Panel > Agents > Add New

- Harper
- Liam

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/ce3679a8-225e-4e37-a3bd-cee723b4966d">

</p>

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/5ebd7ea0-08fe-429f-8d5f-08ba0df42e8d">


<br><br>



<h2>Configure Users</h2>

1. Agent Panel > User > Add New User

- Ava
- Jackson

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/0efea3ef-1f89-4744-8d6d-1d0349d73ae2">

</p>

<br><br>


<h2>Configure SLA</h2>

1. Admin Panel > Manage > SLA

- Sev-A (1 hour, 24/7)
 
- Sev-B (4 hour, 24/7)
  
- Sev-C (1 hour, 24/7)

   
<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/f29fb889-53c4-471a-907e-f737902b9af6">

</p>

<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/830d5133-1ef7-41b9-97f6-808d59c6a4f8">
</p>

<br><br>

<h2>Configure Help Topics</h2>

1. Admin Panel > Manage > Help Topics
  
  - Business Critical Outage
  
  - Personal Computer Issues
  
  - Equipment Request
  
  - Password Reset
  
<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/5e9fa100-f249-47af-b0fa-4e3e883b0bf4">


<p align="center">
<img src="https://github.com/AmyMcCarrell/post-install-config/assets/137266179/7ff03e88-5f59-48a1-b513-5e5857a32261">

</p>

<br>

Next tutorial, [Tickets & Ticket Lifecycle](https://github.com/AmyMcCarrell/ticket-lifecycle)
  



