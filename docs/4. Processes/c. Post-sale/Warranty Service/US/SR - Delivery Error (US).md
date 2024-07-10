# SR - Delivery Error (US)

> **SR (Sales Return)**
> Delivery Error - Cases which we sent an extra item (return only) or sent a wrong item (return & resend).
> 
> The SR process only applies to orders that still within 30 days of delivery.
> 
> If the customer didn't receive one of the items in the order, please follow [[Received Wrong & Missing Items]].
> 
> Positive Grid will cover all the return label fee.

![[Pasted image 20240710105445.png]]

### 0 - Verify the return reason and the purchase date
Before proceeding, verify the user's name and email by comparing them with the Shopify order information to confirm if the order is still within 30 days of delivery.
<br>
<br>
<br>
### 1 - Inquire about basic info
Once confirmed the customer has received an extra or incorrect item, insert Macro: <u>[Service Center] SR (PG pay)</u>. 
   
- Insert the correct country in the email subject. 
   
   ![](https://lh6.googleusercontent.com/B9WsXkXUGJz2mZjdxPtBNdhj_RA0aMjHmyLJj1KIXhqP0qyvR96VTB1p2ZomNWsFZtsHzU-wiEU_l1jXmEAYUXnDFZco-3TAy3lpaN5J4E5txpc1ENwka_Cs8pbb0Th4-LZ78YfyNngGE_Wpgq3Yceoxndy_vkQcL1eCB4I6OxGB84Kw_yzcHsSZLcrc)
   
- Delete the line “Once the returning item has been delivered and verified by our local service center, we'll issue the refund for you ASAP.” as there’ll be no refund for such cases.
   
   ![](https://lh6.googleusercontent.com/N6UjSRypjb4qMUMHjU8ZLXO2a4XNNP1oqzhmxkbDTZy1avS17DF0zp15XND4wpMGMxARZtSASalri-Z5XPhQDw8VxLigczn9-YI9LQeUS3VuolNhY7SCRetZ1odnGtgCLZ9nk8ZmVOvWEiDbzCYHz1vdT5o_Ze9P3e6iWozUuWWu92VJbAKovsUajk95)
   
- Submit as pending. 

<br>
### 2-1 - Create a return on Aftership
Once the client replies with all the requested information, create a return as instructed below:

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ3Nvhf-NB8uydO3u-8-iXva9A48PbK1KLtv8HtoIg1T87MxTw33AXtGn1v_YJ_FyExsZRwLQdQ6DF3/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

On silde#6:

If the customer received a wrong item, please select 'Replace with the same item'.

If the customer received an extra item, please select 'Refund to original payment method'.
<br>
### 2-2 - Check the registration status
Check the registration status by the serial number. Registered products must be deregistered before being sent back to Positive Grid.

Go to [Portal](https://portal.positivegrid.com/warranty/search-warranty-period) and remove the registered item if it's necessary.
![[Pasted image 20240710102318.png]]

<br>
### 3 - Offer return label

- Method#1:

Click "Get return label", the label will be downloaded on your computer.

Attach the label to the email and send it to the customer.

![[Pasted image 20230723141922.png]]

<br>
- Method#2:
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQs3QqZKzBN0o5ipV_h_uIw4eBwK-XNbrj_6iTlMcildrtbDwsA2egFFqC7HB3QwTvN3DW-MHCIRhek/embed?start=false" frameborder="0" width="760" height="456" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the return label is sent to the customer, instruct them to follow the guidance in the email to return the item.
![[Screen Shot 2023-04-24 at 5.49.56 PM.png]]


### 4 - Check the tracking# for the return package
Once the package is on its way, verify whether the case is an operation error (the customer received an extra item) or will require a resend (the customer received a wrong item).

Check the tracking with the corresponding carrier and verify if the item is returned, follow the instructions below:

#### Received an extra item
Thank the customer for cooperation and close the ticket, no further action needed. (END)
<br>
<br>
#### Received a wrong item

Aftership will monitor the tracking number and automatically generate a new order for the replacement once the return package is delivered.

Inform the customer that they will be provided with a new tracking number for the replacement:

> We can see that your package is on its way back to our service center. Please be advised that once our service center has received the package, we’ll arrange a shipment of the correct item ASAP. Please wait for further notice. Thank you.

(END)