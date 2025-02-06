<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
This lab demonstrates the necessary changes I make to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/S33TPEZ.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/7HyoONM.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
After setting up osTicket, it’s time to configure it as a ticketing system. Keep in mind that I switch between the Admin and Agent panels, as each has its own settings. To know which panel you’re using, check the top right corner of the osTicket screen. If it says "Agent Panel," you're in the Admin panel, and vice versa.

The first step is to create a new role called "Supreme Admin." For this lab, I’ll create a role with all available permissions. To do this, go to the Admin panel, navigate to the Agents Menu, click on Roles, and create the new role from there.
</p>
<br />

<p>
<img src="https://i.imgur.com/EQnl5rh.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Next, create a new Department for System Administrators. To do this, go to the Admin panel, open the Agents menu, and click on Departments. From there, you can create the new Department in osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/d7WuRn8.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
A new Level II Support Team needs to be created to complement the existing Level I Support Team in osTicket. To do this, go to the Admin panel, open the Agents menu, click on Teams, and add the new teams as needed.
</p>
<br />

<p>
<img src="https://i.imgur.com/UnYyh3B.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/k0lElHH.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
New agents need to be created to handle tickets in the queue. To do this, go to the Admin panel, open the Agents menu, and click on "Add New Agent." From there, you can create the account credentials for each new agent. For this example, Jane and John Doe will be created as new agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/gHvbfS3.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
New users need to be created so they can submit tickets for the agents to receive and triage. To do this, go to the Agents panel, open the Users menu, and click on "Add User." From there, create the account credentials for each new user. In this case, Karen and Ken will be created as new users.
</p>
<br />

<p>
<img src="https://i.imgur.com/pI1Cf3Q.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Service Level Agreements (SLAs) need to be created to categorize tickets based on their level of impact. To create new SLAs, go to the Admin panel, open the Manage menu, and click on SLA. From there, you can create the necessary SLAs. In this case, SEV-A, B, and C are created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours, respectively.
</p>
<br />

<p>
<img src="https://i.imgur.com/v3zTkfy.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Finally, Help Topics need to be created to assist users in selecting the appropriate category that describes their issue, giving agents a better idea of the problem described in the ticket. To create a new Help Topic, go to the Admin panel, open the Manage menu, click on Help Topics, and then click on "Add New Help Topic." In this case, I’ve added the following topics to use later when creating tickets for resolution: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>
<br />

<h2>osTicket Configurations are Complete </h2>

Now that all the configurations are in place, I can start using osTicket as a fully functional ticketing system. I can create tickets and triage them just as I would in a real-world environment.
