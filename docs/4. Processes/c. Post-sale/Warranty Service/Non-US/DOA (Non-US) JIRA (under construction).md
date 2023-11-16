# DOA (Non-US) JIRA

> Before proceeding, please check the user's name & email and compare them with Shopify order information in order to verify the warranty. 


![[DOA.png]]


### 1 - Inquire about basic info
Once confirmed the issue, insert Macro: <u>[Service Center] DOA</u>. Insert the correct country in the email subject. Submit as pending. (If the customer does not want replacement but refund instead, please modify the macro accordingly.)
   
![](https://lh6.googleusercontent.com/VWCN-i96sVs83WirSHbHUjLjE6IOMz_tEljtrtdN49Ku8VgFigOz_cE275qTC8_QTIU9UGzaP7dcyckopW74_JvDJBtfRRslCj1bil2P88Nod7buknQFs2nb2X5TB6VDXC0yx4HM3fVDeKj77K7VTp5_n4rGYeEgkfydUqVHygX-yywoKsjY20Ci_z1w)

### 2 - Log into to RMA board (JIRA)

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJYyJaL00w9dJob_94CCS6jpHLrX6yDo7k1t2FjN_tHWuUxkFEVRRSzMDgvkg5Ejb1ya-ErAKwr-Hm/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

### 3 - Fill out a DOA request on JIRA

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT3YTE5A14litVIRHZIVjPCoR_HqXI1fQObNRUYf-hPGyRB2Wy6RypTH1-uKP0ZlxCZTD5ESO0g1B9y/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the customer replies with all the requested information, create a new RMA ticket on JIRA and select the correct Issue type based on the customer's country.

Provide required information:
1.  **Summary:** DOA / Order# / Agent's name, for example, 'DOA / PG-xxxxx / WT'.
2.  **Order Number (RMA):** Original order#.
3.  **RMA Number:** Leave blank, JIRA will generate an RMA number automatically later.
4.  **Service Type:** Select 'DOA'.
5.  **Product:** Select the product accordingly.
6.   **Invoice Amount:** Leave blank.
7.   **Invoice Address:** Leave blank.
8.  **Street & House / City / State / Country / ZIP:** Fill in the customer's full address.
9.  **Phone number / Email:** Fill in the customer's phone number & Email.
10. **Description:** Copy & paste the User Scenario / Frequency of Use / Defective Frequency.

![](https://lh6.googleusercontent.com/EAamxZ1yeMdxamyiDcaYoAPlFajXdWvGS-nQRkYgw-Z_6UeDMm8pbuQdKlKz5m0ChN8Cx8ZXu1jEfxA4X6Hhyxnun4jTPbyQwhn3yE04ZLP4ndwsHvnLK4Lr9zev145jlL6oclvqWIdxX095VpBeq9pwhZQCVuGiKR9QFcSkdBRc6I3x6R1TuCSqJXiG)


### 4 - Ticket created, awaiting return label
Once the ticket is created on JIRA, agents can monitor the case status on the [RMA board](https://positivegrid.atlassian.net/jira/software/projects/RMA/boards/63).
   
Reply the ticket with a heads-up, for example:
   
> Thanks for providing the information. 
> 
> I will keep you posted for the call tag/shipping label to return your package. Please wait for further notice. Thank you.

### 5 - Get the return label on JIRA
Our RMA specialist, Vix Hsieh, will tag the agent on JIRA, attach the **return label** to the ticket, and change the JIRA ticket status to changed to "progress" within 3 days. The ticket will be assigned to the agent who requests the RMA. 


Once attached, the agent will be notified, and they can proceed with the return process.
   
> *If no label shows up within 3 days, please reach out to Vix Hsieh.
   
Use the macro <u>Return Label</u> and forward all related information & return labels (attached to the email) to the customer.

Make sure to change the ticket's title and content in the macro to the correct RMA number (auto-generated when submitted). Submit as ‘Pending’.

![](https://lh4.googleusercontent.com/aFXpy4fy14uQl2hD2arD2cgokM_9v7Meim6stgbBx43Tj7T4L6CHq2I1xwgx1d3cfFO4kL-2Z2ckRdwDAsJbrXSDXoL7V5pSynZBnQgU3XU2aFRFGJ-Bf1mtV5vk66sHEkcXKOHuAuncPKdBH4pB2j62xjxyI6OGtDiRQ4ygHlFgYaETt0UL456f1H4H)

### 6 - Check the tracking# for the returned package
Check the tracking# with the corresponding carrier, if an ETA (estimated time of arrival) is available on the carrier's tracking site, please note it in the JIRA ticket and change the ticket status from "To Do" to "Pending -> In Progress":
![[Xnip2023-11-16_14-22-20.jpg]]

Additionally, verify whether the case requests a replacement or refund.

#### Replacement
If the case requires a replacement, it can be requested as soon as the package is on the road. 

To request a replacement, submit a replacement ticket on JIRA ([[Replacement (JIRA)]]).
   
Logistics team should send out the replacement within roughly 2 days. The shipping information will be available in SKULabs. Forward the tracking information to the customer when available. 

#### Refund
If the case requires a refund, we need to wait for the package to be received by our service center. Once we can see the package is on the road, communicate with the customer as below:

> We can see that your package is on its way back to our service center. Please be advised that once our service center has received and verified the package, we'll offer the refund for you ASAP.
> 
> Kindly wait for further notice. Thank you.

To request a replacement, proceed with the [[Refund Process]].

### 7. Close the JIRA ticket.
Close the JIRA by changing the status from "In Progress" to "Closed". (END)

![[Pasted image 20231116143311.png]]