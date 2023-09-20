<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticketing System Configuration</h1>
This tutorial outlines the configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/YHtQSnw.png">
</p>
<p>
Welcome to osTicket! This is our admin dashboard. Once we have tickets created, they will appear here. First, we must create our other admins.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/lAmQT3n.png">
</p>
<p>
Navigating to the Agents tab, you will see currently the only user is myself. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/WC1eutU.png">
</p>
<p>
From the Agents tab, click Roles, and Add New Role.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/IS3ZO03.png">
</p>
<p>
You can name your admin as you wish, but we are basically creating one admin that has full access. Click Add Role at the bottom once you've named your admin.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/0GXDbzd.png">
</p>
<p>
Click the permissions tab. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/z0Vy5gv.png">
</p>
<p>
You will see Tickets, Tasks, and Knoledgebase above the check boxes. Check all boxes on all three tabs.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/U6DbE83.png">
</p>
<p>
Check all boxes.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/avt7oYJ.png">
</p>
<p>
Last one. Click Add Role to complete.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/yh8d19u.png">
</p>
<p>
We have now successfully added our first role. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/Y6Jkhin.png">
</p>
<p>
We will now create Departments. Please navigate to the Departments tab.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/aqeCgaU.png">
</p>
<p>
Our first Department will be System Administrators. For this lab we will keep the other options default during this step. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/yBUNcdu.png">
</p>
<p>
Scroll down and click Create Dept.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/i13h2qz.png">
</p>
<p>
We now have a System Administrators Department. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/PfxL7uc.png">
</p>
<p>
Navigate to the Teams tab and click Add New Team. You will see there is already a Level I Support team. This has been added automatically during installation.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/33mkUsi.png">
</p>
<p>
So continuing on with our support teams, we will now create a Level II Support team. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/2jpA7kV.png">
</p>
<p>
Click the Members tab. We will create more users shortly, but for now add yourself as the user to the support team. Click Create Team.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/zjLqCvZ.png">
</p>
<p>
Navigate to Settings and Users, and make sure the highlighted box is <b>unchecked</b>. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/bOQrUOj.png">
</p>
<p>
Navigate to the Agents tab, and click Add New Agent.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/stHi6qA.png">
</p>
<p>
Here we will create our admin agents. I have entered generic login information above. Click Set Password.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/1QE911E.png">
</p>
<p>
Be sure to uncheck these two boxes if following for a lab. In a live enterprise setting we would of course keep these options, but for the lab, please <b>uncheck</b> these and enter a password. Click Set.
</p>
<br><br>


<p>
<img src="https://i.imgur.com/dSEgUtP.png">
</p>
<p>
Navigate to the Access tab. Under Primary Department please select the System Administrators department we created. Under Select Role you will also choose the Role you created.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/JpdjZqB.png">
</p>
<p>
Navigate to the Teams tab, select the Team we have created. Click Create.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/p0Ws2Z4.png">
</p>
<p>
We will now add another agent. Click the Agents tab, and click Add New Agent.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/iuM6Wld.png">
</p>
<p>
You can of course use any login information you like for the lab, I have entered generic information as shown. Don't forget to click Set Password, create a password, and uncheck the boxes as we did previously.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/oJI6nzJ.png">
</p>
<p>
Click the Access tab, and Select Department. We will add this user to the Support team. For Role we will select View Only. By choosing this we are indicating that are creating a lower tier user who will have limited permissions. Click Create.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/l4WM8v6.png">
</p>
<p>
Navigate back to the Dashboard and click the Agent Panel link. This will switch our Dashboard from the Admin panel to the Agent panel.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/1VSgjej.png">
</p>
<p>
We will now create our users. In an enterprise setting this would be where all members of each team who have permission to submit a support ticket would be. For the lab we will create a couple users to demonstrate ticket life cycles. Click Users and Add User.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/peE9iXe.png">
</p>
<p>
Once again you may name your user as you wish. I have entered generic information as shown. Click Add User.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/3PIMNFT.png">
</p>
<p>
Once again we will click Add User. The creation of the next user is not shown, but just as you did previously you may choose a name, and click Add User.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/1fzfMnq.png">
</p>
<p>
We now have 2 users able to submit support tickets.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/YiFQGht.png">
</p>
<p>
We will now define our SLA or Service Level Agreements. These will be the levels at which each ticket will be assigned according to urgency and time frame to be completed. Click Manage, SLA, and Add New SLA Plan.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/XCoej9J.png">
</p>
<p>
The first level we're creating is Severity Level A or SEV-A. This would be the level with the most urgency, and the least amount of time to complete. This would be used for catastrophic or emergency events needing immediate attention. Click Add Plan.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/if2wHtg.png">
</p>
<p>
Our next level SEV-B will be a mid tier. Click Add Plan.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/gLl4HPf.png">
</p>
<p>
And our last tier SEV-C will be for less urgent events. Click Add Plan.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/5PjrCeP.png">
</p>
<p>
We now have 3 SLA tiers to sort tickets into. 
</p>
<br><br>

<p>
<img src="https://i.imgur.com/BbMZSoP.png">
</p>
<p>
We have Default Help Topics available to us. We will expand on the Help Topics available to our users to select upon submitting their support tickets. Click the Help Topics tab, and Add New Help Topic.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/OrtJwwp.png">
</p>
<p>
We will add 4 new Help Topics. Not all will be shown because each will be exactly the same steps. Please click Add Topic after the creation of each.
</p>
<br><br>

<p>
<img src="https://i.imgur.com/4FAeKAI.png">
</p>
<p>
Here is the first Help Topic Created. Please create all of the following Help Topics:<br>
  <ul>
<li>Business Critical Outage</li>
<li>Personal Computer Issues</li>
<li>Equipment Request</li>
<li>Password Reset</li>
</ul>
</p>
<br><br>

<p>
<img src="https://i.imgur.com/6SLsKa1.png">
</p>
<p>
Once completed your list should look like this. We have now configured all aspects needed to continue with osTicket life cycles demonstration. Please navigate to <a href="https://github.com/annadotconnor/ticket-lifecycle">osTicket Life Cycles</a> to continue.
</p>
<br><br>


