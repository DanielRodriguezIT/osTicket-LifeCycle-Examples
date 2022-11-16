<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - LifeCycle Examples Setup</h1>
</p>
This tutorial demonstrates the creation of tickets as an end user .<br />

</p>
</p>
</p>
<p>
Ken is creating a ticket, the help topic is "Business Critical Outage" because customers are reporting that they cannot access mobile banking. 
</p>
<img src="https://i.imgur.com/lRduIb2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Agents will be able to see live tickets in the agent panel. Queue managers will assign priority tickets to the appropriate agents as well as assigning proper SLAs. 
</p>
<br />
<p>
<img src="https://i.imgur.com/ISfE0G7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this example we are setting the priority level of the ticket. The priority has been set to Emergency since we are dealing with an issue that can effect an entire portion of the business. We have changed the SLA plan and assigned the ticket to a top level technician. In some ticketing system customers can set their own SLA plans. 
</p>
<br />
<p>
<img src="https://i.imgur.com/uJtuLaK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

</p>
<br />
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
