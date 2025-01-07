<p align="center">
<img src="https://i.imgur.com/jVXNdR2.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Tickets, Experimentation & Realistic Applications</h1>

<h2>Operational Necessities</h2>

- Microsoft Azure (personal Virtual Machine platform of choice) (local VM optional)
- Internet Information Services (IIS) (contained within Windows)

<h2>Operating System</h2>

- Windows 10</b>

<h2>Overview of the full Ticket cycle</h2>

- End-User Ticket Creation
- Internal communication and work assignment
- Actively working the issue/ Follow-ups
- Resolved issue/Report

<h2>Step by Step Showcase</h2>

<p>
<img src="https://i.imgur.com/KKcBDkq.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/utprG3Z.png" height="95%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/b9uQqWT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To Start off, I recommend attempting a login using one of your agent logins that we have created and to get a feel for things. If you run into issues or you cannot recall the password for an agent, you always have the ability to log back in with your admin account and within the Admin panel, you will be able to manage all agents, including the ability of changing the password. Next, it is now time to create some tickets. For this, go to the enduser portal, where tickets can be created. The default page for this should always be under http://localhost/osTicket/. Once there, you select "Open a new Ticket". now input the user info outlined in my previous tutrorial (name, email address). Now you will start to see the adjustments that have been made come into play. Choose from one of your help topics that you have created, or a default one. Then you can summaize the issue briefly and afterwards provide details that are neccessary regarding the issue. When finished, click "Create Ticket". You will receive a confimation.
<br />
<p>
<img src="https://i.imgur.com/gFmmlnB.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/jctg0PV.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/lWv8LOM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now it's time to login as an agent. Use your personally created info to log into one of your agent's account on the standard osTicket login page at http://localhost/osTicket/scp/login.php. From here, you will be greeted by the tickets page, as it is the almost exclusively used part of the software as an agent. If you cannot see your created ticket here, go ahead and log out at the top and try your other agent account and you will see it appear then. This shows how only the agents in a certain dept. or team can see new tickets relevant for them. As you may have noticed, there is a spelling error in the ticket's title, let's edit the ticket. Click on the ticket link and you will see all ticket details and you will have many options, e.g. to print ticket info. Click on the edit sign and if your agent has the proper access, you will be able to edit the whole ticket. Add another detail to the ticket if you'd like. Click "Save" and you are finished. Now go back to the ticket details and you will see all neccesary info. Below, you can notice the ticket thread, which looks very much like an online forum. There, the system also logs all the important updates to the ticket. And finally on the bottom, you will be able to post your reply and alternatively post an internal note, which will only be visible to agents or admins within the given institution.
</p>
<br />
<p>
<img src="https://i.imgur.com/MFDn3zW.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/KAppvfU.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now let's look at the information given in a real help desk context. You will see the user's contact infomation, in many cases also the phone number. If the matter is urgent, or if you have more questions, it is best to call the user/customer to get a live update on the situation, in some cases an email can be sent as well, however communication through phone calls is often crucial to this position. Now obsever the SLA plan. It isset to a default SLA as none has been assigned so far. Click on the current plan and you will be able to select your created SLA's. As I have deemed as this agent, this ticket is of standard importance, I will select Priority three. You will have the opporetunity to provide your reasoning for selecting the SLA. Click on "Update". Feel free to update more parts of the ticket based on the severity of the issue. As you can see, the ticket is not assigned to a specific agent or team, click on "Unassigned". This time, let's take this ticket as the currently active agent. We can leave a comment that I, as an agent will now take care of this issue.
<br />
<p>
<img src="https://i.imgur.com/Oq1iN6g.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/CNqe4bO.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/u4PNcxE.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
As we are now actively working on this ticket, let's post a reply. Describe your plan to fix the issue and what might come next. Afterwards, document your resolution to the issue that you might have discovered in your case example in a separate reply. The ticket resolution has been reached and as a result, you can now edit the ticket status, click on "Resolved" at the top. You will be ableto provide an internal comment about the completion if you would like. Right as you close the ticket, you will now be returned to the tickets page and the list will be empty now. At the top, open, closed ,personal tickets and more can be shown, and you will find your resolved ticket at the closed section. I highly suggest thinking of more tickets that could be worked on to get used to the whole system and how to use all the functions. If you are finished and would not like to keep going or practicing more, I recommend deleting the virtual machine in azure now, otherwise, you may stop the VM for now to return to it later. 
This concludes my tutorials for setting up osTicket all the way to the everyday use of the ticketing system and working tickets to their resolution.
