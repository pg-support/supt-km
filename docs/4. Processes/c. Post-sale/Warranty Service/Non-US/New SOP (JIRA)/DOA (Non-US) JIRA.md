# DOA (Non-US) JIRA

> **DOA (Dead on Arrival)**
> The DOA process only applies to orders that still within 30 days of delivery.'


![[Pasted image 20240710152239.png]]



### 0 - Verify the product issue and the purchase date
Before proceeding, verify the user's name and email by comparing them with the Shopify order information to confirm if the order is still within 30 days of delivery.
<br>
### 1 - Inquire about basic info
After confirming the issue, insert Macro: <u>[Service Center] DOA</u>. Insert the correct country in the email subject. Submit as pending. (If the customer does not want a replacement but a refund instead, please modify the macro accordingly.)
   
![](https://lh6.googleusercontent.com/VWCN-i96sVs83WirSHbHUjLjE6IOMz_tEljtrtdN49Ku8VgFigOz_cE275qTC8_QTIU9UGzaP7dcyckopW74_JvDJBtfRRslCj1bil2P88Nod7buknQFs2nb2X5TB6VDXC0yx4HM3fVDeKj77K7VTp5_n4rGYeEgkfydUqVHygX-yywoKsjY20Ci_z1w)
<br>
<br>
<br>
### 2 - Fill out a DOA request on JIRA

Log into to RMA board (JIRA)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJYyJaL00w9dJob_94CCS6jpHLrX6yDo7k1t2FjN_tHWuUxkFEVRRSzMDgvkg5Ejb1ya-ErAKwr-Hm/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the customer replies with all the requested information, create a new RMA issue on JIRA and select the correct Issue type based on the customer's country.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT3YTE5A14litVIRHZIVjPCoR_HqXI1fQObNRUYf-hPGyRB2Wy6RypTH1-uKP0ZlxCZTD5ESO0g1B9y/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Provide required information:

-  **Summary:** 
	  DOA

-  **RMA:** 
	  Leave blank, JIRA will generate an RMA number automatically later.

-  **Service:** 
	  DOA
  
-  **Return Reason:** 
	   Select the RMA reason.
  
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

---
For Vix Hsieh
>JIRA Status: 'To Do' 
>
>Assignee: Automatic (Vix Hsieh)
---
<br>
<br>
<br>
### 3 - Issue created, awaiting the return label
Once the issue is created on JIRA, agent can get the RMA Number immediately.

**Spark LINK:**
We do not require customers to return defective **Spark LINK**. For Spark LINK cases where the unit is dead on arrival (DOA), please proceed directly to refund or replacement.


The RMA Number can be found in the JIRA issue:
![[Pasted image 20231207234913.png]]

Navigate to the Zendesk ticket and change the subject title to the RMA#:
![[Pasted image 20231207235302.png]]

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
For Vix Hsieh:
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
![[Pasted image 20231208000245.png]]



### 5-1 - Check the tracking# for the returned package
Because the label is prepared by Positive Grid, once the package is en route to the service center, the agent can proceed with either the Replacement Request or Refund.
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
### 6 - Replacement/Refund

Verify whether the case requests a replacement or refund.

#### Replacement
If the case requires a replacement, it can be requested as soon as the package is on the road. 

To request a replacement, create a replacement issue on JIRA ([[Replacement, Resend (JIRA)]]).
   
Logistics team should send out the replacement within roughly 2 days. The shipping information will be available in SKULabs. 

Forward the tracking information to the customer when available. Close the support request on Zendesk.

#### Refund
If the case requires a refund, we need to wait for the package to be received by our service center. Once we can see the package is on the road, communicate with the customer as below:

> We can see that your package is on its way back to our service center. Please be advised that once our service center has received and verified the package, we'll offer the refund for you ASAP.
> 
> Kindly wait for further notice. Thank you.

When confirming the package is delivered, proceed with the [[Refund Process]].

After issuing a refund, close the support request on Zendesk.

### 7 - Close the JIRA issue
Before close the JIRA issue, please add a comment with the process to the issue, for example, Replacement requested with RE order number (or RE JIRA issue) or Refunded.

![[Pasted image 20231120171356.png]]

When everything is done, close the JIRA issue by changing the status from "In Progress" to "Done". (END)

![[Pasted image 20231228105612.png]]


### 7 (opt.) - Reopen the JIRA issue
If the customer responds on Zendesk regarding a closed request on JIRA, the agent can reopen the ticket.

a. Search the closed request with the RMA number.
	   ![[Search.jpg]]
	  
	  
b. Change the status from "Close" or "Done" to "Reopen"  
	  ![[Reopen.jpg]]
	  
