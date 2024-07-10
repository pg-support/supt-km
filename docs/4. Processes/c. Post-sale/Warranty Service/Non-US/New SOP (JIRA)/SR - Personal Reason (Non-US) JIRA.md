# SR - Personal Reason (Non-US) JIRA

> **SR (Sales Return)**
> Personal Reason - Return (Paid by the customer) & Refund
> 
> The SR process only applies to orders that still within 30 days of delivery.
> 
> If the customer no longer has the original packaging for return, a $20 (USD) restocking fee needs to be charged and will be deducted from the refund (see [Spark Warranty FAQ](https://help.positivegrid.com/hc/en-us/articles/360060273211-Spark-Warranty-FAQ) for reference). Please explain this to the customer. (Applicable to ALL products.)

![[Pasted image 20240710155715.png]]
<br>
<br>
<br>
### 0 - Verify the product issue and the purchase date
Before proceeding, verify the user's name and email by comparing them with the Shopify order information to confirm if the order is still within 30 days of delivery.


### 1 - Inquire about basic info
Once confirmed the issue, insert Macro:  <u>[Service Center] SR (Regular) - 1</u>. Insert the correct country in the email subject. Submit as pending. (If the customer does not want replacement but refund instead, please modify the macro accordingly.)
   
![](https://lh6.googleusercontent.com/VWCN-i96sVs83WirSHbHUjLjE6IOMz_tEljtrtdN49Ku8VgFigOz_cE275qTC8_QTIU9UGzaP7dcyckopW74_JvDJBtfRRslCj1bil2P88Nod7buknQFs2nb2X5TB6VDXC0yx4HM3fVDeKj77K7VTp5_n4rGYeEgkfydUqVHygX-yywoKsjY20Ci_z1w)

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
	  SR (Personal Reason)
  
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
For Vix Hsieh:
>JIRA Status: 'To Do' 
>
>Assignee: Automatic (Vix Hsieh)
---

### 3 - Issue created, offer info for return
After Vix confirms the SR request, he will change the assignee to the agent.

Reply the Zendesk ticket with Macro: <u>[Service Center] SR (Regular) - 2</u>.

A. Ensure that the content in the macro corresponds accurately with the ticket subject for the correct RMA number.

![[Pasted image 20231208000324.png]]

Once the issue is created on JIRA, agent can get the RMA Number immediately.
![[Pasted image 20240115162002.png]]


B. Leave only the address for the customer’s located country. 
![[SR.jpg]]

C. Submit as pending.
<br>
<br>
<br>
### 4-1 - Check the tracking# for the return package 
After receiving the tracking number along with the corresponding carrier information from the customer, please add this information to the JIRA issue.

![[Pasted image 20231120143126.png]]
   
Reply the Zendesk ticket with a heads-up, for example:
   
> According to the tracking number you provided, the return package will be delivered on Dec 13, 23.
> 
> USPS 9534615060481056365290
> 
> I will issue the refund for your order right after the package is delivered. 
> 
> Please wait for further notice. Thank you.
<br>
<br>
<br>
### 4-2 - Check the registration status
Check the registration status by the serial number. Registered products must be deregistered before being sent back to Positive Grid.

Go to [Portal](https://portal.positivegrid.com/warranty/search-warranty-period) and remove the registered item if it's necessary.
![[Pasted image 20240710102318.png]]
<br>
<br>
<br>
### 5-1 - Check the status of the received package
Check the tracking with the corresponding carrier. On the ETA of the returning package, check the tracking# to verify if the service center has received it.  

Follow the refund process to issue a refund for the customer.

### 5-2 - Refund
#### Refund
If the case requires a refund, we need to wait for the package to be received by our service center. Once we can see the package is on the road, communicate with the customer as below:

> We can see that your package is on its way back to our service center. Please be advised that once our service center has received and verified the package, we'll offer the refund for you ASAP.
> 
> Kindly wait for further notice. Thank you.

When confirming the package is delivered, proceed with the [[Refund Process]].

After issuing a refund, close the support request on Zendesk.

### 6 - Close the JIRA issue
Add a comment with the process to the issue, for example, 'Refunded'.

When everything is done, close the JIRA issue by changing the status from "In Progress" to "Done". (END)

![[Pasted image 20231228105612.png]]