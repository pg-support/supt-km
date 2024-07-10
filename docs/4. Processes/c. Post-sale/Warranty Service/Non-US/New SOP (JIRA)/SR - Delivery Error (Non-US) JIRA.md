# SR - Delivery Error (Non-US) JIRA

> **SR (Sales Return)**
> Delivery Error - Cases which we sent an extra item (return only) or sent a wrong item (return & resend).
> 
> The SR process only applies to orders that still within 30 days of delivery.
> 
> If the customer didn't receive one of the items in the order, please follow [[Received Wrong & Missing Items]].
> 
> Positive Grid will cover all the return label fee.

![[Pasted image 20240710152945.png]]
<br>
<br>
### 0 - Verify the product issue and the purchase date
Before proceeding, verify the user's name and email by comparing them with the Shopify order information to confirm if the order is still within 30 days of delivery.


### 1 - Inquire about basic info
Once confirmed the customer has received the order that was requested to be canceled, insert Macro: <u>[Service Center] SR (PG pay)</u>. 
   
- Insert the correct country in the email subject. 
   
   ![](https://lh6.googleusercontent.com/B9WsXkXUGJz2mZjdxPtBNdhj_RA0aMjHmyLJj1KIXhqP0qyvR96VTB1p2ZomNWsFZtsHzU-wiEU_l1jXmEAYUXnDFZco-3TAy3lpaN5J4E5txpc1ENwka_Cs8pbb0Th4-LZ78YfyNngGE_Wpgq3Yceoxndy_vkQcL1eCB4I6OxGB84Kw_yzcHsSZLcrc)
   
- Delete the line “Once the returning item has been delivered and verified by our local service center, we'll issue the refund for you ASAP.” as there’ll be no refund for such cases.
   
   ![](https://lh6.googleusercontent.com/N6UjSRypjb4qMUMHjU8ZLXO2a4XNNP1oqzhmxkbDTZy1avS17DF0zp15XND4wpMGMxARZtSASalri-Z5XPhQDw8VxLigczn9-YI9LQeUS3VuolNhY7SCRetZ1odnGtgCLZ9nk8ZmVOvWEiDbzCYHz1vdT5o_Ze9P3e6iWozUuWWu92VJbAKovsUajk95)
   
- Submit as pending. 
<br>
<br>
### 2 - Fill out a SR request on JIRA

Log into to RMA board (JIRA)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJYyJaL00w9dJob_94CCS6jpHLrX6yDo7k1t2FjN_tHWuUxkFEVRRSzMDgvkg5Ejb1ya-ErAKwr-Hm/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the customer replies with all the requested information, create a new RMA issue on JIRA and select the correct Issue type based on the customer's country.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vR4R-4dck26t__9OVUQLloF3Px4LqawBbLJqoNzx8rb8ewUzXKSCVKu-UUOq_otvBDSdsffClVQkKbL/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


Provide required information:

-  **Summary:** 
	  SR

-  **RMA:** 
	  Leave blank, JIRA will generate an RMA number automatically later.

-  **Service:** 
	  SR (Delivery Error)
  
-  **Return Reason:** 
	   Select "Others" and add the reason in Description section.
  
-  **Order Number (RMA):** 
	   Original order#.

-  **Product:** 
	   Select the product accordingly.

-  **Serial Number**: 
	   Product's serial number.

-  **Accessory:** 
	   Fill in if it's necessary.

-  **Invoice Amount:** 
	  Leave blank.

-  **Invoice Address:** 
	  Leave blank.

-  **Email:** 
	  Customer's email.
  
-  **Full Address:** 
	  Customer's full address.

-  **Description:** 
	  Copy & paste the User Scenario / Frequency of Use / Defective Frequency.
	  ![](https://lh6.googleusercontent.com/EAamxZ1yeMdxamyiDcaYoAPlFajXdWvGS-nQRkYgw-Z_6UeDMm8pbuQdKlKz5m0ChN8Cx8ZXu1jEfxA4X6Hhyxnun4jTPbyQwhn3yE04ZLP4ndwsHvnLK4Lr9zev145jlL6oclvqWIdxX095VpBeq9pwhZQCVuGiKR9QFcSkdBRc6I3x6R1TuCSqJXiG)
	  
	  Add the reason for return.

--- 
For Vix:
>JIRA Status: 'To Do' 
>
>Assignee: Automatic (Vix Hsieh)
---

### 3 - Issue created, awaiting the return label
Once the issue is created on JIRA, agent can get the RMA Number immediately.

The RMA Number can be found in the JIRA issue:
![[Pasted image 20240115161957.png]]

Navigate to the Zendesk ticket and change the subject title to the RMA#:
![[Pasted image 20240115162131.png]]

Reply the ticket with a heads-up, for example:
   
> Thanks for providing the information. 
> 
> I will keep you posted for the call tag/shipping label to return your package. Please wait for further notice. Thank you.
<br>
<br>
<br>
### 4 - Get the return label on JIRA
Our RMA specialist, Vix Hsieh, will tag the agent on JIRA, attach the **return label** to the issue within 3 days. The issue will be assigned to the agent who requests a label. 

![[Xnip2023-11-16_16-46-21.jpg]]

---
For Vix Hsieh
>Reply to the issue and attach the label.
>
>JIRA will automatically assign the issue back to the reporter.
---

Once attached, the agent will be notified, and they can proceed with the return process.
   
> *If no label shows up within 3 days, please reach out to Vix Hsieh.

Download the label from JIRA and update the JIRA issue status from 'To Do' to 'In Progress'.
![[Pasted image 20231208001612.png]]

Use the macro <u>Return Label</u> and forward all related information & return labels (attached to the email) to the customer.

Ensure that the content in the macro corresponds accurately with the Zendesk ticket subject for the correct RMA number.

Submit as ‘Pending’.
![[Pasted image 20240115162509.png]]


### 5-1 - Check the tracking# for the return package
Because the label is prepared by Positive Grid, once the package is en route to the service center, the agent can proceed with the followings:
<br>
<br>
<br>
### 5-2 - Check the registration status
Check the registration status by the serial number. Registered products must be deregistered before being sent back to Positive Grid.

Go to [Portal](https://portal.positivegrid.com/warranty/search-warranty-period) and remove the registered item if it's necessary.
![[Pasted image 20240710102318.png]]
<br>
<br>
<br>
### 6 - Received an extra item/a wrong item
#### Received an extra item
Thank the customer for cooperation and close the Zendesk ticket, no further action needed. 
<br>
<br>
#### Received a wrong item
If the case requires a replacement, it can be requested as soon as the package is on the road. 

To request a replacement, create a replacement issue on JIRA ([[Replacement, Resend (JIRA)]]).
   
Logistics team should send out the replacement within roughly 2 days. The shipping information will be available in [SKULabs](https://docs.google.com/presentation/d/1mV6JgZ9rcZR58MPT-T2y8dGSshv2lfZfOS2Niw2qFRs/edit?usp=sharing).

Forward the tracking information to the customer when available. Close the support request on Zendesk.


### 7 - Close the JIRA issue
Before close the JIRA issue, please add a comment with the process to the issue, for example, Replacement requested with RE order number (or RE JIRA issue).

![[Pasted image 20231120171356.png]]

When everything is done, close the JIRA issue by changing the status from "In Progress" to "Done". (END)

![[Pasted image 20231228105612.png]]


### 7 (opt.) - Reopen the JIRA issue
If the customer responds on Zendesk regarding a closed request on JIRA, the agent can reopen the ticket.

a. Search the closed request with the RMA number.
	   ![[Search.jpg]]
	  
	  
b. Change the status from "Close" or "Done" to "Reopen"  
	  ![[Reopen.jpg]]
	  
