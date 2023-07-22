<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

Create 
- Roles
- Departments
- Teams
- Allow tickets to be made
- Agents
- User(customers)
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="800" alt="Screen Shot 2023-07-13 at 2 39 06 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/b357c595-65ff-4c11-9237-6d40e51f3c29">

</p>
<p>
With osTicket freshly installed, it's time to set up the ticketing system to make it more like a real environment. The first step is to find the Admin/Agent tab that will be in the top right of osTicket. I will be using both panels for this lab. 

Within the admin panel, I will create a role called "Supreme Admin". roles are the permissions given to an agent(worker) per department that they will have access to. For the sake of the lab, I will be giving every permission that can be granted to the Supreme Admin role allowing us to configure the next steps in the lab. To create a new role, open the Admin panel and enter the Agents menu, click on Roles, and create the role needed.
</p>
<br />

<p>
<img width="800" alt="Screen Shot 2023-07-13 at 2 41 28 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/2066b82e-1bc1-4af3-86d3-6c12e7579b32">

</p>
<p>
The second step is to configure a new Department for System Administrators. To create a Department I will be in the Admin panel, open the Agents menu, and click on Departments. Creating the new department "system Administrators".
</p>
<br />

<p>
<img width="800" alt="Screen Shot 2023-07-13 at 2 43 27 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/a251805c-0014-4a88-8a68-191ca895d2e3">

</p>
<p>
Third step is a new Level II Support Team will be created. To go where I need to be I will be in the Admin panel and open the Agents menu. Click on Teams and add a new Level II support Team. osTicket would already have a Level I support team the one I create will serve as a Support team with more experience. 
</p>
<br />

<img width="800" alt="Screen Shot 2023-07-13 at 2 48 40 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/d62f4ae1-0521-478f-b755-f37ed50554af">

</p>
<p>
After the teams are created I will be configuring Agents(workers) these accounts would be the ones receiving tickets with the intent to respond and solve each ticket that comes through the system. To create Agents I will need to go to the Admin panel, Click on Agents, and create new. For this lab, I will create a few for the sake of the lab Angel being the one osTicket created when I configured a new role. Jane and John Doe will be the agents I create. I will select the system administrators department and the role of supreme admin. John will be selected for the maintenance department an auto-generated department with the role of view only.   
</p>
<br />

<img width="800" alt="Screen Shot 2023-07-13 at 2 50 41 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/6d222914-c75c-4e38-9d84-21d6a1e515aa">

</p>
<p>
Next step is to configure users, these users will be the ones sending in the tickets that will be worked on by the agents. But before that, I will make sure that anyone is allowed to create a ticket. To allow this I will be within the Admin panel and click on the settings tab go to user settings and make sure the required registration box is unchecked. 

Now to create the users that will be the customers sending each ticket switching to the Agents panel is needed. Within the Agents panel, I will select users and then add new users Ken and Karen. 
</p>
<br />

<img width="800" alt="Screen Shot 2023-07-13 at 2 53 04 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/bf5b9227-5aeb-402c-8e35-1fb38fb66c0a">

</p>
<p>
For the sixth step, The SLAs will need to be created the SLA(service level agreement) is needed solely to determine the severity of the ticket and give the agents the length of time needed to resolve the ticket. To configure the SLAs I will switch back to the Admin panel and select the Manage menu then click the SLA tab.
For the Lab, I will be creating three SLA options that will be given to the tickets once created. SLA-A (1 hour, 24/7, SLA-B (4 hours, 24/7), and SLA-C (8 hours, business hours).
</p>
<br />

<img width="800" alt="Screen Shot 2023-07-13 at 2 56 15 PM" src="https://github.com/angelmartinez4147/post-install-config/assets/131706484/09a3039d-9365-49ef-ab25-248d93c6f5d1">

</p>
<p>
And for the final step of this lab, I will create some help topics the users can use with creating their tickets. These help topics can help gauge what SLA the ticket will fall under. To configure this the Admin panel will be used Click on the Manage menu then the Help Topics tab. Create the following help topics Business Critical Outage, Personal Computer Issues, Equipment Request, and Password reset. With these help topics, the users will choose one that closely relates to their issue. From there either a system or Surpreme Admin will choose the proper SLA that will be suited for the ticket with SLA-A being reserved for the most critical of tickets.
</p>
<br />


<h1>osTicket - Post-Install Configuration Completed</h1>

</p>
<p>
Now after completing the post-install configuration, I can use osTicket like like a real Ticketing System sending in tickets and working them as an agent. Being able to respond and resolve each ticket that I send in as a user. Allowing me to practice and gain experience with each completion of the lab.
</p>
<br />
