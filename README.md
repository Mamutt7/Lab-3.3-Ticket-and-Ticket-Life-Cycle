<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
I will demonstrate the Ticket and Ticket Life Cycle in this home lab using osTicket. I will perform some made-up scenarios as both the end-user and the agent working tickets till resolved.<br />

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

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

In this lab, we will be creating tickets as end users
Observing all the ticket properties and responding to them as help desk professionals

●	Change the SysAdmins Department to a Top Level Department
●	DELETE the Maintenance Department (not archive)
________________________________________

As an end-user, create the following ticket
entire mobile/online banking system is down ![image](https://github.com/user-attachments/assets/47710e23-7bd7-4a9e-994e-bc04e24e093a)


As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To ![image](https://github.com/user-attachments/assets/6e803834-c5e5-4f7c-94fe-8848aea8119e)


Set Properties to the ticket
●	Sev-A (1 hour, 24/7)
●	Online Banking Department ![image](https://github.com/user-attachments/assets/de7d3578-53d2-41b7-ac3e-6d3804b0a9c5)


Attempt to observe the ticket again as “john”. Can you view or change?

Work the ticket to completion as jane ![image](https://github.com/user-attachments/assets/5d0f379d-d90a-4420-958d-f9df5b66ac9c)


________________________________________

As an end-user, create the following ticket
accounting department needs adobe upgrade, broken

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
●	Sev-B (4 hours, 24/7)
●	Support

Work the ticket to completion as john  ![image](https://github.com/user-attachments/assets/c526e756-a485-43ca-9119-ce7e28a9679e)


________________________________________

As an end-user, create the following ticket
CFO’s laptop will no longer turn on

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
●	Sev-B (4 hours, 24/7)
●	Support

Work the ticket to completion as john  ![image](https://github.com/user-attachments/assets/a7d69049-4242-45c5-acf7-1c3254961521)

________________________________________

<h2>Takeaways and Key Skills Developed</h2>

In this project, I demonstrated the ticket lifecycle in osTicket by creating and resolving tickets as both an end-user and a help desk agent. I set ticket properties such as priority, department, and SLA, then worked through each stage of the lifecycle, including intake, assignment, communication, and resolution. This hands-on experience helped me understand the full process of ticket management and the roles and permissions within osTicket.
