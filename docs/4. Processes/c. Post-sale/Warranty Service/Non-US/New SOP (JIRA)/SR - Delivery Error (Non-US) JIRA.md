# SR - Delivery Error (Non-US) JIRA

> Delivery Error - Return Only (Paid by PG)

![[DOA.png]]

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

Once the customer replies with all the requested information, create a new RMA ticket on JIRA and select the correct Issue type based on the customer's country.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQvWZOSwZuJOcDUpmXQztHzGQv4YNVcNgYMCTEt5EFmEjXym_lbUMdePc9BR7AzVPC_NL2ZaBTg0wqL/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Provide required information:

-  **Summary:** SR / Order# / Agent's name, for example, 'SR / PG-xxxxx / WT'.

-  **Order Number (RMA):** Original order#.

-  **RMA Number:** Leave blank, JIRA will generate an RMA number automatically later.

-  **Service Type:** Select 'SR - Delivery Error'.

-  **Product:** Select the product accordingly.

-  **Invoice Amount:** Leave blank.

-  **Invoice Address:** Leave blank.

-  **Street & House / City / State / Country / ZIP:** Fill in the customer's full address.

-  **Phone number / Email:** Fill in the customer's phone number & Email.

-  **Description:** Fill in the situation: the customer received an extra item or received a wrong item.


>JIRA Status: 'To Do' 
>Assignee: Automatic (Vix Hsieh)


### 3 - Ticket created, awaiting the return label
Once the ticket is created on JIRA, agents can monitor the case status on the [RMA board](https://positivegrid.atlassian.net/jira/software/projects/RMA/boards/63).
   
Reply the ticket with a heads-up, for example:
   
> Thanks for providing the information. 
> 
> I will keep you posted for the call tag/shipping label to return your package. Please wait for further notice. Thank you.

### 4 - Get the return label on JIRA
Our RMA specialist, Vix Hsieh, will tag the agent on JIRA, attach the **return label** to the ticket, and change the JIRA ticket status to 'In Progress' within 3 days. The ticket will be assigned to the agent who requests the RMA. 

![[Xnip2023-11-16_16-46-21.jpg]]

---
For Vix Hsieh:
>JIRA Status: 'To Do' -> 'In Progress' 
>Assignee: Vix Hsieh -> Agent who requests the RMA

![[Xnip2023-11-16_14-22-20.jpg]]


Once attached, the agent will be notified, and they can proceed with the return process.
   
> *If no label shows up within 3 days, please reach out to Vix Hsieh.
   
Use the macro <u>Return Label</u> and forward all related information & return labels (attached to the email) to the customer.

Make sure to change the ticket's title and content in the macro to the correct RMA number (auto-generated when submitted). Submit as ‘Pending’.

![](https://lh4.googleusercontent.com/aFXpy4fy14uQl2hD2arD2cgokM_9v7Meim6stgbBx43Tj7T4L6CHq2I1xwgx1d3cfFO4kL-2Z2ckRdwDAsJbrXSDXoL7V5pSynZBnQgU3XU2aFRFGJ-Bf1mtV5vk66sHEkcXKOHuAuncPKdBH4pB2j62xjxyI6OGtDiRQ4ygHlFgYaETt0UL456f1H4H)


### 5 - Check the tracking# for the return package
Check the tracking number with the corresponding carrier. If an estimated time of arrival (ETA) is available on the carrier's tracking site, please add it to the JIRA ticket.

![[Pasted image 20231116170835.png]]


Check the tracking with the corresponding carrier and verify if the item is returned, contact the customer and mention the following:

#### Received an extra item
Thank the customer for cooperation and close the ticket, no further action needed. (END)
<br>
<br>
#### Received a wrong item

Aftership will monitor the tracking number and automatically generate a new order for the replacement once the return package is delivered.

Inform the customer that they will be provided with a new tracking number for the replacement:

> We can see that your package is on its way back to our service center. Please be advised that once our service center has received the package, we’ll issue the resend the correct item ASAP. Please wait for further notice. Thank you.

(END)