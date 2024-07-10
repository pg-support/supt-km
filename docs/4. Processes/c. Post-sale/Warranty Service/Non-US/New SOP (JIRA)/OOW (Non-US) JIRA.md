# OOW (Non-US) JIRA

> **OOW (Out of Warranty)**
> 
> The OOW process applies to orders that are out of warranty or the customers who can't provide a valid receipt/order number of the products.
> 

![[Pasted image 20240710160728.png]]

<br>
<br>
### 0 - Verify the warranty
Before proceeding, please check the user's name & email and compare them with Shopify order information in order to verify the warranty.

If the customer bought from another dealer, the agent must ask for the receipt in order to verify the warranty (if it’s already over 1 year of the purchase). Once verified, proceed with the OOW process. 

If the customer bought the amp second hand, ask the customer for the purchase date.


### 1 - Inform about the charge upfront
Once confirmed the issue, please first check with the customer whether he/she is willing to pay for the replacement/repair upfront, pricing listed as below:
   
- Spark 40: $80
- Spark MINI: $60
- Spark GO: $40
- Spark Control: $40
- RIFF: $40


  ==- Special Case:==
- Spark 40 (US Repair): For US OOW only.
- Others (Please leave the amount in Description section): For the special offer only.

### 2 - Inquire information for payment
Once confirmed the customer is willing to proceed and pay for the repair/replacement, insert Macro: <u>[Service Center] OOW - 1</u>.

Insert the correct country in the email subject. Submit as ‘Pending’.

![[Pasted image 20231117175406.png]]


### 3 - Fill out a OOW request on JIRA

Log into to RMA board (JIRA):
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJYyJaL00w9dJob_94CCS6jpHLrX6yDo7k1t2FjN_tHWuUxkFEVRRSzMDgvkg5Ejb1ya-ErAKwr-Hm/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the customer replies with all the requested information, create a new RMA issue on JIRA and select the correct Issue type based on the customer's country.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRr5jPrbx3hS4wyH8A093YDTfpIu82_297NrIpQNgzxNciJc2v7_CvnSa3LJeWhHCtfqRGMVZQ2W96F/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
Provide required information:

-  **Summary:** 
	  OOW

-  **RMA:** 
	  Leave blank, JIRA will generate an RMA number automatically later.

-  **Service:** 
	  OOW

-  **Return Reason:** 
	   Select the RMA reason.

-  **Order Number (RMA):** 
	   Original order#.
> *If the unit is purchased via another dealer, put the dealer’s name in ‘Order Number’, for example, '1163206831 (Guitar Center)''.
> 
> If the unit is a second hand purchase, put the purchase date in ‘Order Number’, for example, '231029'.


-  **Product:** 
	   Select the product accordingly.

-  **Serial Number**: 
	   Product's serial number.

-  **Accessory:** 
	   Fill in if it's necessary.

-  **Invoice Amount:** 
	  Select the correct OOW price for the defective items.

-  **Invoice Address:** 
	  Customer's invoice email address.

-  **Email:** 
	  Customer's email.
  
-  **Full Address:** 
	  Customer's full address.

-  **Description:** 
	  Copy & paste the User Scenario / Frequency of Use / Defective Frequency.
	  ![](https://lh6.googleusercontent.com/EAamxZ1yeMdxamyiDcaYoAPlFajXdWvGS-nQRkYgw-Z_6UeDMm8pbuQdKlKz5m0ChN8Cx8ZXu1jEfxA4X6Hhyxnun4jTPbyQwhn3yE04ZLP4ndwsHvnLK4Lr9zev145jlL6oclvqWIdxX095VpBeq9pwhZQCVuGiKR9QFcSkdBRc6I3x6R1TuCSqJXiG)


---
For Vix Hsieh:
>JIRA Status: 'Invoice Needed' 
>
>Assignee: Automatic (Vix Hsieh)
---

### 4 - Issue created, offer info for return
Once the issue is created on JIRA, agent can get the RMA Number immediately.

The RMA Number can be found in the JIRA issue:
![[Pasted image 20240115155134.png]]

Navigate to the Zendesk ticket and change the subject title to the RMA#:
![[Pasted image 20240115161228.png]]


The agent should ask the customer to check their inbox for the invoice and inform us once it's paid off, for example:
   
> I have requested our RMA specialist to prepare an invoice, and they will send it to your inbox.
> 
> Please inform me once payment has been made, as it will help expedite the process.
> 
> If you do not receive the invoice within 3 days, please let me know.

---
For Vix Hsieh:
>Issue Invoice on PayPal.
>
>Reply to the issue and attach the Invoice.
>
>JIRA will automatically assign the issue back to the reporter and update the issue status from 'Invoice Needed' to 'Awaiting Payment'.
---
<br>
<br>
<br>
### 5 - Confirm payment & offer info for return

Once the customer paid for the amount, tag Vix / Maines / WeiTing on the Supt-Private Channel to confirm the payment status. The agent can check the payment status by scanning the QR code on the invoice.

![[Pasted image 20240219143325.png]]

Vix will also check the payment status once a day and assign the JIRA issue back to agent.

Once the invoice is confirmed as paid, please updated the JIRA issue status from 'Awaiting Payment' to 'To Do'. 

---
For who is going to do this:
>JIRA Status: 'Awaiting Payment' -> 'To Do' 
>
>Assignee: Agent who requests the RMA


The agent can then insert Macro: <u>[Service Center] OOW - 2</u>:

A. Ensure that the content in the macro corresponds accurately with the Zendesk ticket subject for the correct RMA number.

![[Pasted image 20240115162317.png]]

B. Leave only the address for the customer’s located country. 

![](https://lh3.googleusercontent.com/ewy-lJjRb1kBlsRAnYgwIxiN5Y_hVxZrkqVLXeCXo7KCECm41GV_ZvLNwtw6UmpkECgbr7xiAoRrhKGjQOXHcbPNr4q7OsJbZen8I40EARFxJ2LFABD0A9RgvmLR2BV0YLCnWfZT_4fGuVAPnT6jtcqiOw5anhXf3VgD8PBrO2jzU5f8f7y-lns2jaGo)

C. Submit as pending.

### 6-1 - Check the tracking# for the returned package
After receiving the tracking number along with the corresponding carrier information from the customer, please add this information to the JIRA issue.

![[Pasted image 20231116170835.png]]

### 6-2 - Check the registration status
Check the registration status by the serial number. Registered products must be deregistered before being sent back to Positive Grid.

Go to [Portal](https://portal.positivegrid.com/warranty/search-warranty-period) and remove the registered item if it's necessary.
![[Pasted image 20240710102318.png]]


### 7 - Request for replacement

#### Replacement
Once the tracking# is provided so we can confirm the returned package is on the way, the agent can proceed and request a replacement by submitting a replacement issue on JIRA ([[Replacement, Resend (JIRA)]]).

Logistics team should send out the replacement within roughly 2 days. The shipping information will be available in [SKULabs](https://docs.google.com/presentation/d/1mV6JgZ9rcZR58MPT-T2y8dGSshv2lfZfOS2Niw2qFRs/edit?usp=sharing).

Forward the tracking information to the customer when available. Close the support request on Zendesk.

#### Repair (US Only)
Inform the customers that Jeff will contact them directly at a later time.

### 8 - Close the JIRA issue
Add a comment with the process to the issue, for example, Replacement requested with RE order number (or RE JIRA issue).

![[Pasted image 20231120171356.png]]

When everything is done, close the JIRA issue by changing the status from "In Progress" to "Done". (END)

![[Pasted image 20231228105612.png]]


### 7 (opt.) - Reopen the JIRA issue
If the customer responds on Zendesk regarding a closed request on JIRA, the agent can reopen the ticket.

a. Search the closed request with the RMA number.
	   ![[Search.jpg]]
	  
	  
b. Change the status from "Close" or "Done" to "Reopen"  
	  ![[Reopen.jpg]]