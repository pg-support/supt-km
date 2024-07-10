# DOA (US)

> **DOA (Dead on Arrival)**
> The DOA process only applies to orders that still within 30 days of delivery.

![[Pasted image 20240710151748.png]]

### 0 - Verify the product issue and the purchase date
Before proceeding, verify the user's name and email by comparing them with the Shopify order information to confirm if the order is still within 30 days of delivery.
<br>
<br>
<br>
### 1 - Inquire about basic info
After confirming the issue, insert Macro: **<u>[Service Center] DOA</u>**. 
Insert the correct country in the email subject. Submit as pending. (If the customer does not want replacement but refund instead, please modify the macro accordingly.)
   
![](https://lh6.googleusercontent.com/VWCN-i96sVs83WirSHbHUjLjE6IOMz_tEljtrtdN49Ku8VgFigOz_cE275qTC8_QTIU9UGzaP7dcyckopW74_JvDJBtfRRslCj1bil2P88Nod7buknQFs2nb2X5TB6VDXC0yx4HM3fVDeKj77K7VTp5_n4rGYeEgkfydUqVHygX-yywoKsjY20Ci_z1w)

<br>
<br>
 **Special Case:**
 <br>
 a. The customer requests to change the address for the replacement
 <br>
After inquiring about basic info, if the customer provides a shipping address that differs from the one on the original order, process with step 2 in: [[Different Shipping Address for the Replacement]]

<br>
If the customer's order is a personalized product, please check **Special Case b**.
<br>
<br>

 b. The order included a personalized/crimson grille
 <br>
After inquiring about basic info, if the customer's order includes a personalized grille, process with step 2 in: [[RMA, DOA Includes a Personalized Grille]]

<br>
<br>
c. Spark LIVE
- For Spark LIVE DOA/RMA (US) replacement, please create a request on JIRA.
- Only "Refund" cases can be processed on Aftership.
<br>
<br>
<br>
### 2-1 - Create a return on Aftership
Once the client replies with all the requested information, create a return as instructed below:
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ3Nvhf-NB8uydO3u-8-iXva9A48PbK1KLtv8HtoIg1T87MxTw33AXtGn1v_YJ_FyExsZRwLQdQ6DF3/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
<br>
<br>
<br>
### 3 - Offer return label

- Method#1:

Click "Get return label", the label will be downloaded on your computer.
*If you don't see this button, please refresh the page.*

Attach the label to the email and send it to the customer.

![[Pasted image 20230723141922.png]]


- Method#2:
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQs3QqZKzBN0o5ipV_h_uIw4eBwK-XNbrj_6iTlMcildrtbDwsA2egFFqC7HB3QwTvN3DW-MHCIRhek/embed?start=false" frameborder="0" width="760" height="456" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the return label is sent to the customer, instruct them to follow the guidance in the email to return the item.
![[Screen Shot 2023-04-24 at 5.49.56 PM.png]]
<br>
<br>
<br>
### 4-1 - Check the tracking# for the return package
Check the tracking with the corresponding carrier and verify if the item is returned.
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
### 5 - Replacement/Refund

Verify whether the case requests a replacement or refund.

#### Replacement

Aftership will monitor the tracking number and automatically generate a new order for the replacement once the return package is delivered.

Inform the customer that they will be provided with a new tracking number for the replacement. Zendesk ticket can be closed.
(END)
<br>
<br>
#### Refund
If an estimated time of arrival (ETA) is available on the carrier's tracking site, you can proceed with the [[Refund Process]]  (because the label is provided by Positive Grid) and communicate with the customer using the following message:

> We can see that your package is on its way back to our service center. To expedite up the process, I've issued a refund for your order.
> 
> Kindly wait for further notice. Thank you.

Zendesk ticket can be closed.
<br>
(END)
<br>
<br>
#### How to find the tracking number for the replacement?
*Customer will receive the tracking number when the replacement is shipped. Instructions below will show you how to find the tracking for the replacement manually*

Aftership will change the status of the order to "Received" when the package is delivered to the service center.
![[Pasted image 20230911141544.png]]

![[Pasted image 20230911141605.png]]

And it will create a new order for the replacement automatically.
![[Pasted image 20230911141805.png]]
![[Pasted image 20230911141845.png]]

Click on the Exchange order, it will redirect you to the exchange order page on Shopify.
![[Pasted image 20230911142124.png]]