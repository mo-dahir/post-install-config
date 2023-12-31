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
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics


<h2>Configuration Steps</h2>

 STEP 1:
  *Configuring roles*
1. Admin Panel -> Agents -> + Roles
2. Definition: Supreme Admin > Permissions: Check off all the boxes

<p>
<img src="https://i.imgur.com/oMMM7iM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  STEP 2:
*Configure Departments*
1. Admin Panel -> Agents ->  + Departments
2. Name: System Administrators > + Create Department
<p>
<p>
<img src="https://i.imgur.com/MpMCBbD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  STEP 3:
  *Configure Teams*
 1. Admin Panel -> Agents ->  + Teams
2.  Name: Level I Support > Members > Add any agent
3. Name: Level II Support > Members > Add any agent
</p>
<p>
<p>
<img src="https://i.imgur.com/jLdNMrT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  STEP 4:
  *Allow anyone to create tickets*
  1. Admin Panel -> Settings -> User Settings
2. Registration Required: Require registration and login to create tickets (can or uncheck the box)
</p>
<p>
<p>
<img src="https://i.imgur.com/AAFUaSX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

   STEP 5:
*Configure Agents (workers)*
1. admin Panel -> Agents -> + Add New
2. Name: Jane Doe > Email Address: Jane.Doe@osticket.com > Username: Jane.Doe > Password: Password1 > Set
3. Name: John Doe > Email Address: John.Doe@osticket.com > Username: John.Doe > Password: Password1 > Set
</p>
<p>
<p>
<img src="https://i.imgur.com/Tw6z9Sl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  STEP 6:
  *Configure Users (customers)*
  1. Agent Panel -> Users -> + Add User (User Directory)
2. Email Address:Karen@osticket.com > Full Name: Karen Karen
3. Email Address:Ken@osticket.com > Full Name: Ken Ken
</p>
<p>
<p>
<img src="https://i.imgur.com/sf7PH5r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  STEP 7:
  *Configure SLA*
  1. Admin Panel -> Manage -> + SLA
2. Sev-A (1 hour, 24/7)
3. Sev-B (4 hours, 24/7)
4. Sev-C (8 hours, business hours)
</p>
<p>
<p>
<img src="https://i.imgur.com/QCLr8iU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  STEP 8:
  *Configure Help Topics*
1. Admin Panel -> Manage -> + Help Topics
2. + Business Critical Outage
3. + Personal Computer Issues
4. + Equipment Request
5. + Password Reset
</p>
<p>
<p>
<img src="https://i.imgur.com/U9eIPCD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
