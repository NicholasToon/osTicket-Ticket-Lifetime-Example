
<p align="center">
<img src=https://i.imgur.com/BQKsviY.png"/></P>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this tutorial, I'll walk you through the journey of a ticket within osTicket. We'll cover everything from its creation to its resolution. (This is a short tutorial. The tutorial will be confusing if you have not followed the previous prerequites and configuration tutorials). <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket                                         

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Ticket Lifecycle Examples</h2>

<p>
<img src=https://i.imgur.com/ejPZZ1Z.png" />
<img src=https://i.imgur.com/8S1CJoh.png" />           
</p>
<p>
<h3> Go into your browser and enter http://localhost/osTicket/ to open tickets as a customer/(End)  User. </h3>
</p>
<br />

<h2> Stage 1: Intake</h2>
<p>
<img src=https://i.imgur.com/mvnz6Vb.png" />
</p>
<p>
This is the stage when a new ticket is created. There are a couple of ways to submit a ticket—either by filling out a form, like the one shown here, or by sending an email to a designated ticketing address. To ensure that your issue is resolved (provided you find yourself submitting a ticket), you will want to enter your contact information, describe the topic/issue, and provide all the necessary details about the problem. 
</p>
<br /
           
                      

<p>
<h2> Step 2: Assignment <h2>
<p>
<img src=https://i.imgur.com/IrCiizx.png" />
<img src=https://i.imgur.com/VDsqAOj.png" />           
</p> 
<h3> Return to http://localhost/osTicket/scp/login.php </h3>
Get to the Staff Control Panel by signing into the account you desginated as Admin and go to the agent panel. You will now see the Ticket we created and will be able assign the agent that will be working on it and the ticket severity AKA SLA. In this example, I change priority to "Normal," the SLA plan to "SEV-B," and assign it to the "Support" department. If I had any agents in my "Support" department, I would then assign it to the said agent for this scenario.
           
</p>
<br />           

<p>
<h2> Stage 3: Working the Issue </h2>
<img src=https://i.imgur.com/BijdBMr.png" />
<img src=https://i.imgur.com/R6J9osU.png" />
<img src=https://i.imgur.com/c48GwN6.png" />
</p>

          
<p>
The ticket has now been assigned to the apprpriate department, the IT team can start working on a solution to the issue. During this process, any changes of note will appear in the Ticket Thread. Thankfully, a password reset is typically easy. Forward the"Send Password Reset Email" to the designated user that is requesting a reset and they can take care of the rest.
</p>
<br />       


