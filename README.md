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


<h2>Intake</h2>

Tickets are received into osticket from the support center support ticket system screen. The following is a demonstration on what creating an end-user ticket looks like. If the settings were configured correctly, users do not need an account to create a ticket through the support center. Within this support center screen, the user “ken” will create a ticket.
Click on “Open a New Ticket” on the right hand corner of the screen. 

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%201.png" width="600" height="400" />

A form will show up. Within this form a user can provide an email address, their name, phone number, the help topic, and an issue summary section where a title and description can be provided. The picture below shows what an example user submitted ticket looks like.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%202.png" width="600" height="400" />


After all the fields have been filled, click on “Create Ticket” on the bottom of the screen to submit the ticket. 

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%203.png" width="600" height="400" />


Once the ticket is created, it will be sent to the appropriate help desk agents based on the settings that were configured within osticket. 




<h2>Assignment and Communication</h2>
Once a ticket has been created, it will show up on the osticket portal as shown below.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%204.png" width="600" height="400" />


“John” as a help desk agent will observe and assign the ticket in the following demonstration. To begin, click on the ticket to see its contents. Here on the top, help desk agents can change the status,priority, department settings, and assign SLAs as well as assign tickets to a specific person to better filter out tickets.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%205.png" width="600" height="400" />

Below is a more detailed breakdown of this section 

<h2>Status</h2>: there are 2 options available here once the word “Open” is clicked, these are Resolved and closed.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%206.png" width="600" height="400" />


<h2>Priority</h2> Within this section, a priority level can be assigned to the ticket. There are 4 options available once the word “Normal” is clicked. These are Low, Normal, High, Emergency. There is also a textbox to provide further context and reasoning for the change within this pop up window. 

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%207.png" width="600" height="400" />


<h2>Department</h2> Within this section, the user can assign the ticket to the appropriate department. The number of options here will be based on how many departments were created and configured within osTicket. There is also a textbox to provide further context and reasoning for the change within this pop up window. There is a check marked box that can be clicked and selected to maintain referral access to current departments.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%208.png" width="600" height="400" />

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%209.png" width="600" height="400" />

<h2>Assigned To</h2> Within this section, the user can assign the ticket to an appropriate agent. Within the pop-up window that shows up after “Unassigned” is clicked, the dropdown menu will have a number of options here based on how many agents were created and configured within osTicket. There is also a textbox to provide further context and reasoning for the change.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2010.png" width="600" height="400" />



<h2>SLA Plan</h2> Within this section, the user can select the appropriate SLA plan for the ticket. The number of options here will be based on how many SLA plans were created and configured within osTicket. There is also a textbox to provide further context and reasoning for the change within this pop up window.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2011.png" width="600" height="400" />


<h2>Help Topic</h2> Within this section, the user can select the appropriate help topic for the ticket. The number of options here will be based on how many help topics were created and configured within osTicket. There is also a textbox to provide further context and reasoning for the change within this pop up window.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2012.png" width="600" height="400" />



Help desk user “John” will make changes for the sample ticket shown at the beginning of this section. The “Assigned To”  will be changed to “Online Banking”. The “SLA Plan”  will be changed to “Sev-A”. The “Help Topic” will be changed to “Report a Problem/ Business Critical Outage”.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2013.png" width="600" height="400" />


<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2014.png" width="600" height="400" />


<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2015.png" width="600" height="400" />


In the next section, help desk user “Jane” will work the ticket to completion since she is a part of the online banking team.


<h2>Working the Issue</h2> 

Once a ticket has been properly assigned, the appropriate help desk agent can work the ticket to completion. For the following demonstration, “Jane” will be completing this ticket. “Jane” will assign the ticket to herself that way everyone in the online banking team knows she is working on it.

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2016.png" width="600" height="400" />


While the ticket is being worked on, the help desk agent can communicate with the user that submitted the ticket as well as post internal notes within the team that is working on the ticket. 

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2017.png" width="600" height="400" />

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2018.png" width="600" height="400" />

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2019.png" width="600" height="400" />


In the next section, the resolution process for the ticket will be discussed. 






<h2>Resolution</h2> 
Now that “Jane” has solved the issue, the ticket can be resolved within osticket. Within the ticket dashboard, click on “Open” next to “Status”

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2020.png" width="600" height="400" />



Within the pop-up screen, in the drop down menu next to “Status” select “Resolved”. Afterwards, click on “Close” on the bottom right corner of the screen. 


<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2021.png" width="600" height="400" />

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2022.png" width="600" height="400" />

Once “Close” is clicked, the user will get taken back to their open ticket dashboard. 

<img src="https://github.com/JosephRC777/ticket-lifecycle/blob/baafab6f2399651fdf8ca841cf33410751c2502a/images/osticket%20lifecycle%2023.png" width="600" height="400" />


This concludes the osTicket ticket lifecycle demonstration. 
