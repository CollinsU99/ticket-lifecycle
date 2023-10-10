<p align="center">
<img src="https://i.imgur.com/TDCIttW.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Post-Install Configuration</h1>
This tutorial provides a step-by-step guide to the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10 Pro (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p align="center">
<img src="https://i.imgur.com/cgtEXUX.png" height="80%" width="80%" alt="img"/>
</p>

We will create some tickets as end users and solve those tickets as a helpdesk support professional.

Paste this link (end users osTicket url): http://localhost/osTicket/ in your VM's web browser and click Enter.

On the osTicket support center page, click "Open a New Ticket".

<p align="center">
<img src="https://i.imgur.com/xAv0Pn0.png" height="80%" width="80%" alt="img"/>
</p>

Fill in Karen's information as shown in the image above. Select "Business Critical Outage" for Help Topic. Add an issue summary with more explanation, and click "Create Ticket".

<p align="center">
<img src="https://i.imgur.com/ZSV0Ffz.png" height="80%" width="80%" alt="img"/>
</p>

The ticket has now been created.

We will create a couple more tickets. Click the "Open a New Ticket" tab.

<p align="center">
<img src="https://i.imgur.com/olQPmFg.png" height="80%" width="80%" alt="img"/>
</p>

Let's create one as Ken. Fill in the information as shown in the above image, select a help topic, and write the issue summary. Click "Create Ticket

<p align="center">
<img src="https://i.imgur.com/ZtO34N1.png" height="80%" width="80%" alt="img"/>
</p>

Let's create one more ticket as Karen. Create the ticket as shown in the image above.

<p align="center">
<img src="https://i.imgur.com/YditKcY.png" height="80%" width="80%" alt="img"/>
</p>

We will now login into osTicket as a help desk support professional to try an solve the tickets

Go to: http://localhost/osTicket/scp/login.php 

We will login as Jane Doe, as shown in the image above.

<p align="center">
<img src="https://i.imgur.com/LCiNLJI.png" height="80%" width="80%" alt="img"/>
</p>

It seems like Jane Does doesn't have permission to solve tickets. Let's log out and log in as admin so we can make some changes to Jane's account and allow her to solve tickets.

Click Log Out at the top left of the page. 

<p align="center">
<img src="https://i.imgur.com/X9kr6ku.png" height="80%" width="80%" alt="img"/>
</p>

Log in as admin, as shown in the image above.

<p align="center">
<img src="https://i.imgur.com/1D6e6Xj.png" height="80%" width="80%" alt="img"/>
</p>

Click on the "Admin Panel" tab at the top right of the page.

<p align="center">
<img src="https://i.imgur.com/XWEfvaM.png" height="80%" width="80%" alt="img"/>
</p>

Click "Agents".

<p align="center">
<img src="https://i.imgur.com/4mwOYTO.png" height="80%" width="80%" alt="img"/>
</p>

Click "Jane Doe".

<p align="center">
<img src="https://i.imgur.com/5bnfHFX.png" height="80%" width="80%" alt="img"/>
</p>

Click the "Access" tab, add Jane Doe to "Support", select "Supreme Admin", and click "Save Changes". Click log out at the top right of the page.

<p align="center">
<img src="https://i.imgur.com/YditKcY.png" height="80%" width="80%" alt="img"/>
</p>

Let's log back in as Jane Doe.

<p align="center">
<img src="https://i.imgur.com/47Ro7m3.png" height="80%" width="80%" alt="img"/>
</p>

Jane Doe is now able to see the tickets we created as end users.

Let's observe the tickets and make some changes to them.

<p align="center">
<img src="https://i.imgur.com/Czo2HfA.png" height="80%" width="80%" alt="img"/>
</p>

Click the "Mobile banking is experiencing an outage" ticket.

<p align="center">
<img src="https://i.imgur.com/Czo2HfA.png" height="80%" width="80%" alt="img"/>
</p>

Let's change it's priority. Click "Normal".

<p align="center">
<img src="https://i.imgur.com/ki8W9Z9.png" height="80%" width="80%" alt="img"/>
</p>

Change the priority level to "Emergency", and click "Update".

<p align="center">
<img src="https://i.imgur.com/OtBq7IN.png" height="80%" width="80%" alt="img"/>
</p>

Click "Unassigned".

<p align="center">
<img src="https://i.imgur.com/5N5wQy1.png" height="80%" width="80%" alt="img"/>
</p>

Assign it to Jane Doe, and click "Assign".

<p align="center">
<img src="https://i.imgur.com/hrMZmzu.png" height="80%" width="80%" alt="img"/>
</p>

Click "Default SLA".

<p align="center">
<img src="https://i.imgur.com/Yn57TWU.png" height="80%" width="80%" alt="img"/>
</p>

Select "SEV-A", write some notes, and click "Update".

<p align="center">
<img src="https://i.imgur.com/K3qFKZQ.png" height="80%" width="80%" alt="img"/>
</p>

Click "Support" 

<p align="center">
<img src="https://i.imgur.com/eGHMB41.png" height="80%" width="80%" alt="img"/>
</p>

Select "System Administrators", write some notes, and click "Transfer".

<p align="center">
<img src="https://i.imgur.com/P75b28P.png" height="80%" width="80%" alt="img"/>
</p>

Write some notes, click "Post Reply", and click the "Tickets" tab at the top.

<p align="center">
<img src="https://i.imgur.com/rM9HAxo.png" height="80%" width="80%" alt="img"/>
</p>

As shown in the image above, the ticket has been assigned to Jon Does, and the priority has change.

Let's close the ticket by clicking it.

<p align="center">
<img src="https://i.imgur.com/edFAAbd.png" height="80%" width="80%" alt="img"/>
</p>

Update the note, select "Closed", and click "Post Reply".

<p align="center">
<img src="https://i.imgur.com/56dAiyz.png" height="80%" width="80%" alt="img"/>
</p>

As shown in the image above, the ticket is no longer on our list of open tickets.

Let's work on the "Adobe Reader is down" ticket. Click on it.

<p align="center">
<img src="https://i.imgur.com/KFBsZAA.png" height="80%" width="80%" alt="img"/>
</p>

As shown in the image above, change the priority to "High". Assign it to John Wood, and change the SLA to SEV-B.Write some notes and click "Post Reply".

<p align="center">
<img src="https://i.imgur.com/kNU7BMP.png" height="80%" width="80%" alt="img"/>
</p>

Click on the "When are we getting a hardware refresh" ticket.

As shown in the image above, change priority to "Low", assign it to Jane Doe, change SLA to SEV-C. Write some notes, mark it as "Resolved", and click "Post Reply".

<p align="center">
<img src="https://i.imgur.com/tQpWbqo.png" height="80%" width="80%" alt="img"/>
</p>

Now, we only have one ticket left. In order to work on the ticket, we need to sign in as John Wood, since it's assigned to him. Click the "Log out" tab at the top right of the page. 

<p align="center">
<img src="https://i.imgur.com/s84mThN.png" height="80%" width="80%" alt="img"/>
</p>

Log in as John Wood.

<p align="center">
<img src="https://i.imgur.com/09XSRnR.png" height="80%" width="80%" alt="img"/>
</p>

Click on the ticket.

<p align="center">
<img src="https://i.imgur.com/w9uGVLV.png" height="80%" width="80%" alt="img"/>
</p>

Update the note. Click "Post Note", and click the "Log Out" tab at the top right.

In order to close the ticket, we need to login as Admin and give John permission to close his own ticket.

<p align="center">
<img src="https://i.imgur.com/YhVxzSf.png" height="80%" width="80%" alt="img"/>
</p>

Let's log in as Admin, so that we can close the ticket.

<p align="center">
<img src="https://i.imgur.com/lSqVxm3.png" height="80%" width="80%" alt="img"/>
</p>

Click "Admin Panel".

<p align="center">
<img src="https://i.imgur.com/o1vv6pc.png" height="80%" width="80%" alt="img"/>
</p>

Move your cursor to the "Agents" tab and click "Departments".

<p align="center">
<img src="https://i.imgur.com/tRN50Dd.png" height="80%" width="80%" alt="img"/>
</p>

Click "Support".

<p align="center">
<img src="https://i.imgur.com/r5l59di.png" height="80%" width="80%" alt="img"/>
</p>

Click "Access".

<p align="center">
<img src="https://i.imgur.com/NXZ5f2M.png" height="80%" width="80%" alt="img"/>
</p>

Select "Supreme Admin", select "All Access", click "Save Changes", and log out.

<p align="center">
<img src="https://i.imgur.com/oSNxk9T.png" height="80%" width="80%" alt="img"/>
</p>

Let's log back in as John Wood.

<p align="center">
<img src="https://i.imgur.com/OvLAbcA.png" height="80%" width="80%" alt="img"/>
</p>

Open the ticket by clicking on it.

<p align="center">
<img src="https://i.imgur.com/GOlBXy9.png" height="80%" width="80%" alt="img"/>
</p>

Write some notes, select "Resolved", and click "Post Reply".

<p align="center">
<img src="https://i.imgur.com/KDGwW81.png" height="80%" width="80%" alt="img"/>
</p>

We no longer have any open tickets

<p align="center">
<img src="https://i.imgur.com/HXC4pWn.png" height="80%" width="80%" alt="img"/>
</p>

Click "Closed" to see all our closed tickets.

Congrats, you made it to the end :)












