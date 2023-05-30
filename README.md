# Post-Installation-of-OsTicket
 <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>


Once you have Installed OsTicket, log in to the portal to open OsTicket.
<p>
  <img src="https://i.imgur.com/Zn7Rdgt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

 Once you're logged in we'll start to configure "Roles" 
 <p>
  <img src="https://i.imgur.com/MMLskFp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Navigating to Roles: Once you're in the admin panel, click on the "Admin" tab in the top navigation bar. From the dropdown menu, select "Roles & Permissions."
  
 Creating a New Role: To create a new role, click on the "Add New Role" button. Give the role a name that reflects its purpose or function.
  <p>
  <img src="https://i.imgur.com/nvg11uZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Defining Role Permissions: In the role settings page, you will see a list of available permissions. Enable or disable the checkboxes next to each permission to grant or restrict access for the role you're creating. The available permissions may vary based on the osTicket version and any plugins you have installed.

Permissions typically include actions like managing tickets, managing knowledgebase articles, managing departments, and accessing specific settings. Consider your organizational needs and the level of access each role should have.
 <p>
  <img src="https://i.imgur.com/oQAq1Ij.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Now We'll Go go over setting up Departments
 <p>
  <img src="https://i.imgur.com/huxaVTx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adding a New Department: To create a new department, click on the "Add New Department" button. Fill in the required information, including the department name and email address. The email address will be used to receive and assign tickets to this department.
 Configuring Department Options: In the department settings page, you can configure various options to customize the behavior and visibility of the department. Some common options include:

Department Signature: You can add a signature that will be appended to outgoing emails from this department.
Department Manager: Assign a manager to the department who will have additional privileges and responsibilities within the department.
Ticket Assignment: Determine how tickets are assigned within the department, such as "Round Robin" or "Direct Assignment."
Auto-Response: Set up an automatic response that is sent to users when they submit a ticket to this department.
Internal Notes: Choose whether internal notes are visible to the user or restricted to staff members only.
 <p>
  <img src="https://i.imgur.com/GCyxijN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
 Defining Department Permissions: By default, all staff members have access to all departments. However, if you want to restrict access to specific departments, you can edit individual staff members' profiles and limit their department access.

To do this, navigate to the "Staff" tab in the admin panel and select "Manage" and then "Staff Members." Edit a staff member's profile and choose the departments they should have access to by checking the appropriate checkboxes under the "Department Access" section.
<p>
  <img src="https://i.imgur.com/MvFsrZH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Navigating to Teams: Once you're in the admin panel, click on the "Admin" tab in the top navigation bar. From the dropdown menu, select "Manage" and then choose "Teams."
 
 Adding a New Team: To create a new team, click on the "Add New Team" button. Provide a name for the team and a brief description to help identify its purpose or function.
 <p>
  <img src="https://i.imgur.com/txf8Xrv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Configuring Team Options: You can configure additional options for the team, such as the team's email address and team signature. The team email address will be used for ticket assignment and collaboration purposes, while the team signature will be appended to outgoing emails from the team.

Defining Team Permissions: By default, team members have access to all tickets in the system. However, if you want to restrict team members to specific departments or ticket queues, you can edit individual staff members' profiles and limit their access.

To do this, navigate to the "Staff" tab in the admin panel and select "Manage" and then "Staff Members." Edit a staff member's profile and choose the departments or queues they should have access to by checking the appropriate checkboxes under the "Department Access" or "Queue Access" sections.
    
 
If you want to allow access for anyone to create tickets, make sure you're under admin, go to users, and then settings.
  (When you get to settings make sure you uncheck require registration and login box.)
 
  
 <p>
  <img src="https://i.imgur.com/hSEwOTT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

 
 To create agents panel and click "Add New Agent" 
 
 <p>
  <img src="https://i.imgur.com/SnQYK5N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
 From here you can assign agents different roles, permissions, and even place them into teams. 
 
 
 
Creating SLA Plans

In the admin dashboard, locate and click on the "Admin Panel" button in the top right corner.
In the Admin Panel, navigate to "Manage -> SLA".
Click on the "Add New SLA Plan" button.
 
 <p>
  <img src="https://i.imgur.com/LUCep2j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
 Configuring SLA Plan Details

Provide a name for the SLA plan in the "Title" field.
Set the priority level for this plan using the "Priority" drop-down menu. This defines the importance of tickets associated with this SLA plan.
Optionally, you can set a response time and resolution time by specifying the hours, minutes, and seconds in the corresponding fields. These times determine the target durations for responding to and resolving tickets.
Adjust any other settings according to your requirements.
 
  <p>
  <img src="https://i.imgur.com/wxD3bmB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
 Defining Escalation Rules

Under the "Escalation Rules" section, click on the "Add Rule" button.
Specify a name for the escalation rule in the "Title" field.
Set the duration after which the escalation rule should be triggered, using the "Duration" field. For example, if you want to escalate the ticket after 2 hours, enter "2" in the "Duration" field.
Choose the action that should be taken when the escalation rule is triggered using the "Action" drop-down menu. You can select options like "Send an Email," "Close the Ticket," etc.
Configure any other escalation rules you need for this SLA plan by clicking on the "Add Rule" button again and repeating the steps.
 
   <p>
  <img src="https://i.imgur.com/UrNZhTo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
 Creating Help Topics

In the admin dashboard, locate and click on the "Admin Panel" button in the top right corner.
In the Admin Panel, navigate to "Manage -> Help Topics".
Click on the "Add New Help Topic" button.
 
   <p>
  <img src="https://i.imgur.com/c3rxiSR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
