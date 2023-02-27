<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>


<p>
In your browser go to localhost/osTicket/  Then click in Open a new ticket
</p>
<p>
<img src="https://i.imgur.com/IytC7W7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Enter email, full name and phone number, then in the help topic select what type of problem are you having. After that, an issue summary will appear, write the summary of your issue there, under issue summary there will be a white board, there you have to write the specific of the problem as detail as possible so the IT team can work to solve the problem. Create as many ticket as you want to practice and see what the end user will experience. When you are done, select Create ticket. 
</p>
<p>
<img src="https://i.imgur.com/075vVUB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now let’s go back to localhost/osTicket/scp/login.php, and let’s try login in as one of the Agents created in the previous tutorial. Enter the user name and password given when the agent was created. After you log in as an Agent, you should be able to see the tickets that you created as a user in the previous step 
Note: if you are not able to see the tickets, it probably something to do with the permissions, go back as an admin and give the require permissions so the agent can work on the tickets. 
</p>
<p>
<img src="https://i.imgur.com/8z46Pso.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Click one of the tickets created and see what is inside. There you can configure the status, the priority, the department, SLA and others.. it’s important that the tickets are assigned so go ahead and click “Assigned To” to assign the ticket to one of the Agents. Then depending on the situation, respond to the ticket. Then click Post reply so the user can see what you are doing to resolve the issue.
</p>
<p>
<img src="https://i.imgur.com/OVyBwmh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Play around with the tickets and the options. When you solve the problem of the ticket, select ticket status -> “resolved” and click post reply, when you do so, the ticket will disappear from the front page 
</p>
<p>
<img src="https://i.imgur.com/cvlrsyE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
