# SR - Personal Reason (Non-US) JIRA (under construction)

> Personal Reason - Return (Paid by the customer) & Refund
> 
> If the customer no longer has the original packaging for return, a $20 (USD) restocking fee needs to be charged and will be deducted from the refund (see [Spark Warranty FAQ](https://help.positivegrid.com/hc/en-us/articles/360060273211-Spark-Warranty-FAQ) for reference). Please explain this to the customer. (Applicable to ALL products.)


![[DOA.png]]


### 1 - Inquire about basic info
Once confirmed the issue, insert Macro:  <u>[Service Center] SR (Regular) - 1</u>. Insert the correct country in the email subject. Submit as pending. (If the customer does not want replacement but refund instead, please modify the macro accordingly.)
   
![](https://lh6.googleusercontent.com/VWCN-i96sVs83WirSHbHUjLjE6IOMz_tEljtrtdN49Ku8VgFigOz_cE275qTC8_QTIU9UGzaP7dcyckopW74_JvDJBtfRRslCj1bil2P88Nod7buknQFs2nb2X5TB6VDXC0yx4HM3fVDeKj77K7VTp5_n4rGYeEgkfydUqVHygX-yywoKsjY20Ci_z1w)

### 2 - Log into to RMA board (JIRA)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJYyJaL00w9dJob_94CCS6jpHLrX6yDo7k1t2FjN_tHWuUxkFEVRRSzMDgvkg5Ejb1ya-ErAKwr-Hm/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

### 3 - Fill out a SR request on JIRA

Once the customer replies with all the requested information, create a new RMA ticket on JIRA and select the correct Issue type based on the customer's country.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQvWZOSwZuJOcDUpmXQztHzGQv4YNVcNgYMCTEt5EFmEjXym_lbUMdePc9BR7AzVPC_NL2ZaBTg0wqL/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Provide required information:

-  **Summary:** SR / Order# / Agent's name, for example, 'SR / PG-xxxxx / WT'.

-  **Order Number (RMA):** Original order#.

-  **RMA Number:** Leave blank, JIRA will generate an RMA number automatically later.

-  **Service Type:** Select 'SR'.

-  **Product:** Select the product accordingly.

-  **Invoice Amount:** Leave blank.

-  **Invoice Address:** Leave blank.

-  **Street & House / City / State / Country / ZIP:** Fill in the customer's full address.

-  **Phone number / Email:** Fill in the customer's phone number & Email.

-  **Description:** Copy & paste the User Scenario / Frequency of Use / Defective Frequency.

![](https://lh6.googleusercontent.com/EAamxZ1yeMdxamyiDcaYoAPlFajXdWvGS-nQRkYgw-Z_6UeDMm8pbuQdKlKz5m0ChN8Cx8ZXu1jEfxA4X6Hhyxnun4jTPbyQwhn3yE04ZLP4ndwsHvnLK4Lr9zev145jlL6oclvqWIdxX095VpBeq9pwhZQCVuGiKR9QFcSkdBRc6I3x6R1TuCSqJXiG)

>JIRA Status: 'To Do' 
>Assignee: Automatic (Vix Hsieh)

Once the ticket is created on JIRA, the ticket will be automatically assigned to "Awaiting Tracking" section.

### 4 - Offer info for return
Reply the ticket with Macro: <u>[Service Center] SR (Regular) - 2</u>.

A. Insert the corresponding RMA number in the subject & context. 

![](https://lh3.googleusercontent.com/RX4JW2MkM0d3daOB8j3Wqsqrl1Gv8gN5NgDmdOPMxoVpc2y_uiBf_2Kqq6w_9Fp0XVh60LNc6EXyYSaRloHn3asoyQ0dGj4V7jzMinSZ8aqGRoyax2bjjIEZdtsNQs5X984FfTlavbegvX_eaaRZvR7CA9ugHq9BmoBzxrOe86uUjxvtjNGisc3aQNNx)

B. Leave only the address for the customer’s located country. 
![[SR.jpg]]

C. Submit as pending.

### 5 - Check the tracking# for the returned package 
Check the tracking number with the corresponding carrier. If an estimated time of arrival (ETA) is available on the carrier's tracking site, please add it to the JIRA ticket.

![[Pasted image 20231120143126.png]]
   
Reply the ticket with a heads-up, for example:
   
> Thanks for providing the information. 
> 
> I will keep you posted for the call tag/shipping label to return your package. Please wait for further notice. Thank you.

### 6 - Check the status of the received package
Check the tracking with the corresponding carrier. On the ETA of the returning package, check the tracking# to verify if the service center has received it.  

Follow the refund process to issue a refund for the customer.

#### Refund
If the case requires a refund, we need to wait for the package to be received by our service center. Once we can see the package is on the road, communicate with the customer as below:

> We can see that your package is on its way back to our service center. Please be advised that once our service center has received and verified the package, we'll offer the refund for you ASAP.
> 
> Kindly wait for further notice. Thank you.

When confirming the package is delivered, proceed with the [[Refund Process]].

After issuing a refund, close the support request on Zendesk.

### 7. Close the JIRA ticket
When everything is done, close the JIRA by changing the status from "In Progress" to "Closed". (END)

![[Pasted image 20231116143311.png]]