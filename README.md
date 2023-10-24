<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Setup (Part 2)</h1>
<p>Following the installation, let's ensure proper configuration for managing roles, departments, teams, tickets, agents, users, SLAs (Service Level Agreements), and help topics. Let's proceed with clear and user-friendly steps.</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines: Windows 10 recommended for this guide)
- MacBook Air
- RD Client
- Internet Information Services (IIS)

<h2>Operating Systems Employed</h2>

- Windows 10 Pro

-----

<h2>1) Configure Roles</h2>

- Access the Admin Panel.
  
- Navigate to Agents and select Roles.

- Establish a "Supreme Admin" role.

<h2>2) Configure Departments</h2>

- In the Admin Panel, go to Agents and click on Departments.
  
- Create a "System Administrators" department.
  
<h2>3) Configure Teams</h2>

- Still in the Admin Panel, find Agents and choose Teams.

- Establish teams named "Level I Support" and "Level II Support."

<h2>4) Allow Anyone to Create Tickets</h2>

- In the Admin Panel, access Settings and select User Settings.

- Enable "Registration Required" to ensure users must register and log in to create tickets.

<h2>5) Configure Agents (Workers)</h2>

- Within the Admin Panel, under Agents, click on "Add New."

- Add agents like "Jane" and "John."

<h2>6) Configure Users (Customers)</h2>

- Visit the Agent Panel and go to Users, then click "Add New."

- Add users such as "Karen" and "Ken."

<h2>7) Configure SLA (Service Level Agreements)</h2>

- From the Admin Panel, head to Manage and select SLA.

- Set up SLAs like "Sev-A" (1 hour, 24/7), "Sev-B" (4 hours, 24/7), and "Sev-C" (8 hours, business hours).

<h2>8) Configure Help Topics</h2>

- Lastly, go to the Admin Panel, then Manage, and choose Help Topics.

- Create topics such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."

-----

<h1>Conclusion</h1>
By following these straightforward steps, you've successfully configured your platform to manage roles, departments, teams, tickets, agents, users, SLAs, and help topics. Your setup is now prepared to meet your needs effectively.

-----

# [Next: osTicket - Ticket Lifecycle: Intake Through Resolution (Part 3)](https://github.com/stanguerrero/ticket-lifecycle)
