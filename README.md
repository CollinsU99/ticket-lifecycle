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

Click "Access" tab, add Jane Doe to "Support", select "Supreme Admin", and click "Save Changes". Click log out at the top right of the page.

<p align="center">
<img src="https://i.imgur.com/YditKcY.png" height="80%" width="80%" alt="img"/>
</p>

Let's log back in as Jane Doe.





























