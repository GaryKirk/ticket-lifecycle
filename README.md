<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
The aim of this lab is to explore the lifecycle of a help desk ticket from start to finish in osTicket. I completed this lab to gain experience in traiging common ticket issues that a Desktop Support Technician may work on throughout a regular day in an IT department.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2) </b>

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>1. In Remote Desktop, connect to the Windows VM using the public IP address found in Microsoft Azure. Use your VM login details to connect. After connection to the VM, open a browser window and go to <a href="http://localhost/osTicket/">http://localhost/osTicket/</a>. This is the URL for end users osTicket. It's used by users to open new tickets and check on the staus of current tickets. </p>
<img src="https://github.com/GaryKirk/ticket-lifecycle/assets/137613637/ab509891-47ff-49f7-a692-e04291083b2b" alt="End User OS Ticket" width="500" length="500"/><br /><br />

<p>2. You can now enter the details of IT issues by clicking the 'Open New Ticket' button.  Use the information of the users and help topics that were created before. Input three different tickets, such as:</p>

<ul>- The whole online banking system is down, which affects all customers</ul>
<ul>- The accounting department is having trouble getting Adobe Reader to open documents</ul>
<ul>- A manager is looking to find out when their team will receive new devices</ul>

Next, go to <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a>to login to osTicket. Use the agent credentials that were setup previously. As long as the Agent's permissions have been setup correctly, you should now be able to view the tickets that were created by the user.</p> 
<img src="https://github.com/GaryKirk/ticket-lifecycle/assets/137613637/fc6751f8-753d-4a7f-8daf-7a6a713d2f2c" alt="Input Tickets" width="500" length="500"/><br /><br />

<p>3. Open the online banking outage ticket. This is a business critical issue, so set the 'Priority' to 'Emergency' using the drop-down menu. Add a note to explain that it's a business impacting event. Assign the ticket to yourself and set the 'SLA' to 'SEV-A'. Transfer the ticket to 'System Administrators' with notes to explain why the ticket has been transferred. Add notes as the agent to say that the ticket is being worked on. Finally, add notes to explain how the issue was rectified and close the ticket. </p>
<img src="https://github.com/GaryKirk/ticket-lifecycle/assets/137613637/c2e9276a-fabf-42d7-8a4f-c3241b3546da" alt="Emergency Ticket" width="500" length="500"/><br /><br />

<p>4. Open the ticket from the accounting department about Adobe Reader. Set the 'Priority' to 'High' because this is an issue that impacts a key department within the organiztion. Assign the ticket to a different agent and set the 'SLA' to 'SEV-B'. Assign the ticket to an agent. Add notes to explain the changes you have made to the ticket. Log out of osTicket and login to the system as the other assigned agent. You should now see the open ticket on the dashboard. Open the ticket, read the notes, and add a reply to say that you have rolled back an Adobe update and that you investigte why the update caused Adobe to fail. Log out of osTicket and log back in as the original agent. You can view the reply to the ticket, add notes to say that the ticket is resolved and close it.</p>
<img src="https://github.com/GaryKirk/ticket-lifecycle/assets/137613637/e096a777-7ff4-4673-967f-afa8b0948bd1" alt="High Priority Ticket" width="500" length="500"/><br /><br />

<p>5. Open the ticket from the manager about when their team will receive new devices. Set the 'Priority Level' to 'Low'. Assign the ticket to the current agent and set the 'SLA' to 'SEV-C'.  Finally, reply to the message to explain that the hardware refresh is taking place soon and they can start testing the devices today. Mark the ticket as closed.</p>
<img src="https://github.com/GaryKirk/ticket-lifecycle/assets/137613637/f25704e3-b093-4225-9562-aa212761b28d" alt="Low Priority Ticket" width="500" length="500"/><br /><br />

The ticket queue should now be clear.
