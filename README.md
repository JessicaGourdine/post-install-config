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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments and Teams
- Configure Agents (help desk workers) and Users
- Configure SLAs
- Configure Help Topics


<h2>Configuration Steps</h2>
<p>Click <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a> and login with the credentials you created when setting up os Ticket<p>
<h3>1. Configure Roles</h3>
<ul>
  <li>Make sure you're in the Admin panel (when you're in the Admin panel, Agent will show as an option and vice versa)</li> <p>
<p>
<img width="410" alt="osTicket_Admin Panel" src="https://github.com/user-attachments/assets/0126a883-93fe-4df3-9f7f-5f0d31ffefee">

</p>
<p>
<ul>
  <li>Click Agents -> Roles</li>
  <li> Click Add New Role and name it Supreme Admin</li>
  <li> Click Permissions tab and choose all permissions in Tickets, Tasks and Knowledgebase then save changes</li>
</ul><p></p>
<img width="615" alt="osTicket_Admin Roles" src="https://github.com/user-attachments/assets/42bbeaf2-1c8b-42bd-bef1-ef124aaff660">
<h3>2. Configure Departments</h3>
<ul>
  <li>From the Admin panel, select Agents -> Departments</li>
  <li> Select Add New Department</li>
  <li>Name it System Administrators and save</li>
</ul> 
<p></p>
<img width="495" alt="osTicket_New Dept" src="https://github.com/user-attachments/assets/f00cf013-8ee5-4a9a-ab3c-6d344d786d44"> <p>
</p>
<h3>3. Configure Teams</h3>
<ul>
  <li>From the Admin Panel, select Agents -> Teams</li>
  <li>Choose Add New Team</li>
  <li> Name team Level II support (if Level I support isn't listed by default, add it)</li>
</ul>
<br />
<h3>4. Allow Anyone to Create Tickets</h3>
<ul>
  <li>From the Admin Panel, choose Settings -> Users</li>
  <li> Make sure Registration Required box is unchecked</li>
</ul><p>
  
</p>
<img width="643" alt="osTicket_RegUnchecked" src="https://github.com/user-attachments/assets/cac4dad5-9ddc-43e1-88b5-661976f22f99">

<p>

<h3>5. Configure Agents</h3>
<ul>
  <li>From the Admin panel, choose Agents -> Add New Agents</li>
  <li>Name: Jane Doe</li>
  <li>Email: jane.doe@osticket.com</li>
  <li>username: jane.doe</li>
  <li>Click Set Password, input Password1, uncheck both boxes then click set</li>
  <p>(Make a note of the username and password)</p>
  <img width="669" alt="osTicket_Password Set" src="https://github.com/user-attachments/assets/784ace54-9ec1-4d1a-8c15-b4b61d8bd0bf"><p></p>
  <li>Choose the Access tab and select the System Administrator Dept and the Supreme Admin Role</li>
  <li>Choose the Teams tab and select Level II Support</li>
  <li>Click Create</li> 
  
  </ul>


</p><h4>Repeat Process for New Agent</h4>
<ul>
  <li>From the Admin panel, choose Agents -> Add New Agents</li>
  <li>Name: John Doe</li>
  <li>Email: john.doe@osticket.com</li>
  <li>username: john.doe</li>
  <li>Click Set Password, input Password1, uncheck both boxes then click set</li>
  (Make a note of the username and password)
  <li>Choose the Access tab and select the Support Dept and the View Only Role</li>
  <li>Click Create</li> 
  </ul>

<br />
<h3>6. Configure Users</h3>
<ul>
  <li>Switch to the Agent panel (when you're in the Agent panel, Admin will show as an option and vice versa)</li> <p>
    <img width="395" alt="osTicket_Agent Panel" src="https://github.com/user-attachments/assets/902df972-8ebc-4231-b3d9-75f1638c115f">
    <ul>

<p>

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
