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
- Working on the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
  A ticket will begin its life here at the end-user support center ticket system This is where a ticket will be created by the end-user for example here we have Karen she is a online mobile bank user however the online banking system is down so she can't access it the image below shows an example of what a possible ticket can be created by someone which should have a help topic a quick summary and usually will have a open text box where you can include more details and a brief explanation
  <img width="1440" alt="Screenshot 2025-04-24 at 9 23 14 PM" src="https://github.com/user-attachments/assets/2799de8a-3afe-415d-93ef-9a69de3246d0" />
</p>
<p>
Now, after the ticket is created, it will be sent into the database and stored. Now, it will be received and viewed by an agent who will start investigating the ticket and possibly find In this example, we will observe the ticket as John(Help Desk Agent). First, we will need to log in as him
<img width="1440" alt="Screenshot 2025-04-24 at 9 28 21 PM" src="https://github.com/user-attachments/assets/db8314b0-7a9e-4669-89f5-934b8c30a0ee" />
Now that we logged in, we see it appears on our dashboard(Image Above) We will click the ticket so that we can see who created it and when it was created, and the description of the issue the users will have.
  <img width="1440" alt="Screenshot 2025-04-24 at 9 30 44 PM" src="https://github.com/user-attachments/assets/b9aceb2a-d1c3-436f-8de9-825af54cab4c" />
For the most part, once a ticket is created, it will be organized generically, and as the help desk agent, we should be able to make the ticket information as concise as possible by implementing an SLA and assigning it  to a specific agent or department. For this example, the ticket explains that mass impact is occurring to employees, stating the online banking is down, so for example, this would fall under Sev-A because it is causing a severe and wide impact, and need immediate priority, also we will be picking the more precise help topic which is one of the ones we created called Report a Problem/Business Critical Outage
<img width="1440" alt="Screenshot 2025-04-24 at 9 43 10 PM" src="https://github.com/user-attachments/assets/bc5b65a3-de23-4365-b4b6-f35694023a02" />
Most tickets will have a record and history of the ticket and changes, and comments that have been made to the ticket, and it allows agents and admins to be able to see what has been done to get one step closer to resolving the issue. It will look like this
  <img width="1440" alt="Screenshot 2025-04-24 at 9 50 02 PM" src="https://github.com/user-attachments/assets/f886059d-7595-43fe-96e3-91d2ad766fd5" />
Some tickets might require you, as a help desk, to transfer them to a specific admin or department that might be better suited to solve the problem. In this example, we will be assigning this ticket to Jane as a SysAdmin
  <img width="1440" alt="Screenshot 2025-04-24 at 9 54 09 PM" src="https://github.com/user-attachments/assets/7d936e8d-d51d-4565-baa7-10e09920a7c7" />
  From this point on, John won't be able to see or change any information on the ticket once we refresh the page. The ticket won't appear on our end as (John). Next, we will sign out as John and log in as Jane and complete this ticket 
<img width="1440" alt="Screenshot 2025-04-24 at 10 00 31 PM" src="https://github.com/user-attachments/assets/bbc66ad8-0a03-42f7-93e2-cffaf53b3da3" />
Here we can see that the ticket was assigned to Jane successfully. Now we will complete the ticket to completion as Jane
<img width="1440" alt="Screenshot 2025-04-24 at 10 14 45 PM" src="https://github.com/user-attachments/assets/d549d94f-334e-4b20-bcca-23047ee3b836" />
At this point the ticket is solved 
  <img width="1440" alt="Screenshot 2025-04-24 at 10 15 10 PM" src="https://github.com/user-attachments/assets/9b84b83d-9998-4c22-9c6a-ff70fcb216d3" />
