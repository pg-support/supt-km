# RMA (US)

> **RMA (Return Merchandise Authorization)**
> The RMA process applies to orders that are more than 30 days from delivery but still within the warranty period. 
> 
> For all RMA cases at this time, please proceed by sending a whole new item as a replacement.
> 
> Note that this process only applies to Shopify order. If you're processing an order from BigCommerce, please follow [[RMA (Non-US)]] instead.

![[Pasted image 20240710105314.png]]

### 0 - Verify the product issue and the purchase date
Before proceeding, please check the user's name & email and compare them with Shopify order information in order to verify the warranty.  

> If the customer bought from dealers/retailers, the agent must ask for the receipt in order to verify the warranty (if it’s still within 1 year of the purchase). Once verified, proceed with the RMA process. 
<br>
<br>
<br>
### 1 - Inquire about basic info
Once confirmed the issue, insert Macro: <u>[Service Center] RMA</u>. Insert the correct country in the email subject. Submit as ‘Pending’.  
    ![](https://lh4.googleusercontent.com/KAG8xtMlvQ-3LweFYg0IfjHp1oYumblzKyDrRke6hFIcQQfhsZ78Zfg4x0UOkhniW2zgzKsbNFfpeqRygj_j-HYHTrIXIzC1-eSbniT4qRXbCl1rmfhC5zLAPLCHhkl75TJdvztYKhWPiOz4qZTNlvcHOVpMVKzqx-sUTXnjGNpAuGcLKLYXQeJXV9uJ)  
<br>
 **Special Case:**
 <br>
 <br>
 a. The customer request to change address for the replacement
 <br>
After inquiring about basic info, if the customer provides a shipping address that differs from the one on the original order, process with step 2 in: [[Different Shipping Address for the Replacement]]

<br>
If the customer's order is a personalized product, please check **Special Case b**.
<br>
<br>

 b. The order included personalized grille
 <br>
After inquiring about basic info, if the customer's order includes a personalized grille, process with step 2 in: [[RMA, DOA Includes a Personalized Grille]]
<br>
<br>
c. Spark LIVE
- For Spark LIVE DOA/RMA (US) replacement, please create a request on JIRA.
- Only "Refund" cases can be processed on Aftership.
<br>
<br>
### 2-1 - Create a return on Aftership
Once the client replies with all the requested information, create a return as instructed below:

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ3Nvhf-NB8uydO3u-8-iXva9A48PbK1KLtv8HtoIg1T87MxTw33AXtGn1v_YJ_FyExsZRwLQdQ6DF3/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
<br>
### 2-2 - Check the registration status
Check the registration status by the serial number. Registered products must be deregistered before being sent back to Positive Grid.

Go to [Portal](https://portal.positivegrid.com/warranty/search-warranty-period) and remove the registered item if it's necessary.
![[Pasted image 20240710102318.png]]

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

### 4 - Check the tracking# for the return package

Aftership will monitor the tracking number and automatically generate a new order for the replacement once the return package is delivered.

Inform the customer that they will be provided with a new tracking number for the replacement. (END)


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