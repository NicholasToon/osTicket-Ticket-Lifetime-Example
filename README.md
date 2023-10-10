
![Image](https://i.imgur.com/BQKsviY.png)

# osTicket - Ticket Lifecycle: Intake Through Resolution #
In this tutorial, I'll walk you through the journey of a ticket within osTicket. We'll cover everything from its creation to its resolution. (This is a short tutorial. The tutorial will be confusing if you have not followed the previous prerequites and configuration tutorials). 


## Environments and Technologies Used 

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket                                         

## Operating Systems Used 

- Windows 10 (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## Ticket Lifecycle Examples

![Image](https://i.imgur.com/ejPZZ1Z.png)

![Image](https://i.imgur.com/8S1CJoh.png)

### Go into your browser and enter http://localhost/osTicket/ to open tickets as a customer/(End) User

## Stage 1: Intake

![Image](https://i.imgur.com/mvnz6Vb.png)
           
This is the stage when a new ticket is created. There are a couple of ways to submit a ticket—either by filling out a form, like the one shown here, or by sending an email to a designated ticketing address. To ensure that your issue is resolved (provided you find yourself submitting a ticket), you will want to enter your contact information, describe the topic/issue, and provide all the necessary details about the problem. 
           
## Step 2: Assignment 

![Image](https://i.imgur.com/IrCiizx.png)

![Image](https://i.imgur.com/VDsqAOj.png)

### Return to http://localhost/osTicket/scp/login.php 

Get to the Staff Control Panel by signing into the account you desginated as Admin and go to the agent panel. You will now see the Ticket we created and will be able assign the agent that will be working on it and the ticket severity AKA SLA. In this example, I change priority to "Normal," the SLA plan to "SEV-B," and assign it to the "Support" department. If I had any agents in my "Support" department, I would then assign it to said agent for this scenario.
           

## Stage 3: Working the Issue 

![Image](https://i.imgur.com/BijdBMr.png)

![Image](https://i.imgur.com/R6J9osU.png)

![Image](https://i.imgur.com/c48GwN6.png)

The ticket has now been assigned to the apprpriate department, the IT team can start working on a solution to the issue. During this process, any changes of note will appear in the Ticket Thread. Thankfully, a password reset is typically easy. Forward the"Send Password Reset Email" to the designated user that is requesting a reset and they can take care of the rest.    

## Stage 4: Resolution 

![Image](https://i.imgur.com/QJ4NMSK.png)

After the issue has been successfully addressed, you have the option to label the ticket as "closed." Within the osTicket system, as part of this process, tickets that are marked as closed are moved from the "Open" section to the "Closed" section.

That was the four stages of a Ticket! I hope this guide was helpful for others in their understanding of everday IT scenarios.
     


