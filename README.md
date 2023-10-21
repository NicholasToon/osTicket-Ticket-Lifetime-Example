
![Image](https://i.imgur.com/BQKsviY.png)

# osTicket - Ticket Lifecycle: Intake Through Resolution #
In this tutorial, I'll walk you through the journey of a ticket within osTicket. We'll cover everything from its creation to its resolution. (Please note that this is a short tutorial and may be confusing if you have not followed the previous prerequisites and configuration tutorials).

*Always delete your resource groups and other environments in Azure to avoid incurring any unwanted charges on your free credits or actual money. Keep resources open at your own discretion.*


## Environments and Technologies Used 

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection (RDC)
- Internet Information Services (IIS)
- osTicket                                         

## Operating Systems Used 

- Windows 10 Pro (22H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## Ticket Lifecycle Examples

![Image](https://i.imgur.com/ejPZZ1Z.png)

![Image](https://i.imgur.com/8S1CJoh.png)

Go into your browser and enter http://localhost/osTicket/ to open tickets as a customer/(End) User

## Stage 1: Intake

![Image](https://i.imgur.com/mvnz6Vb.png)
           
This is the stage when a new ticket is created. There are a couple of ways to submit a ticket—either by filling out a form, like the one shown here, or by sending an email to a designated ticketing address. To ensure that your issue is resolved (if you find yourself submitting a ticket), you will want to enter your contact information, describe the topic/issue, and provide all the necessary details about the problem.           

## Step 2: Assignment 

![Image](https://i.imgur.com/IrCiizx.png)

![Image](https://i.imgur.com/VDsqAOj.png)

### Return to http://localhost/osTicket/scp/login.php 

To access the Staff Control Panel, sign in using the account you designated as Admin and navigate to the agent panel. Here, you will find the ticket we created and will be able to assign an agent to work on it and set the ticket severity, also known as SLA. In this example, I change the **Priority** to "Normal," the **SLA Plan** to "SEV-B," and assign it to the "Support" department. If I had any agents in my "Support" department, I would then assign it to one of those agents for this scenario.

## Stage 3: Working the Issue 

![Image](https://i.imgur.com/BijdBMr.png)

![Image](https://i.imgur.com/R6J9osU.png)

![Image](https://i.imgur.com/c48GwN6.png)

The ticket has now been assigned to the appropriate department, and the IT team can begin working on a solution to the issue. During this process, any noteworthy changes will appear in the Ticket Thread. Fortunately, a password reset is usually straightforward. Forward the "Send Password Reset Email" to the designated user who is requesting a reset, and they can take care of the rest.

## Stage 4: Resolution 

![Image](https://i.imgur.com/QJ4NMSK.png)

After the issue has been successfully addressed, you have the option to mark the ticket as "closed." Within the osTicket system, as part of this process, tickets that are marked as closed are moved from the "Open" section to the "Closed" section.

---

## That was the four stages of a Ticket! I hope this guide was helpful for others in their understanding of everday IT scenarios. Thank you for your Time.
     


