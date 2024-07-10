# OOW (US - Spark 40 Repair)

> **OOW (Out of Warranty)**
> This SOP is for OOW - US - Spark 40 only.
> 
> The OOW process applies to orders that are out of warranty or the customers who can't provide a valid receipt/order number of the products.
> 
> For everything else, please refer to [[OOW (Non-US)]]

![[Pasted image 20240710112145.png]]

### 0 - Verify the warranty
Before proceeding, please check the user's name & email and compare them with Shopify order information in order to verify the warranty.

If the customer bought from another dealer, the agent must ask for the receipt in order to verify the warranty (if it’s already over 1 year of the purchase). Once verified, proceed with the OOW process. 

If the customer bought the amp second hand, ask the customer for the purchase date.


### 1 - Inform about the paid repair
Once confirmed, insert Macro: <u>[Service Center] OOW (US Spark 40 Repair)</u>.

### 2 - Fill out an OOW request on JIRA

Log into to RMA board (JIRA):
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTJYyJaL00w9dJob_94CCS6jpHLrX6yDo7k1t2FjN_tHWuUxkFEVRRSzMDgvkg5Ejb1ya-ErAKwr-Hm/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Once the customer replies with all the requested information, create a new RMA ticket on JIRA and select the correct Issue type based on the customer's country.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRr5jPrbx3hS4wyH8A093YDTfpIu82_297NrIpQNgzxNciJc2v7_CvnSa3LJeWhHCtfqRGMVZQ2W96F/embed?start=false&loop=false" frameborder="0" width="760" height="560" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

Provide required information:

-  **Summary:** OOW

-  **RMA Number:** Leave blank, JIRA will generate an RMA number automatically later.

-  **Service Type:** OOW.
  
-  **Order Number (RMA):** Original order#.
> *If the unit is purchased via another dealer, put the dealer’s name in ‘Order Number’, for example, '1163206831 (Guitar Center)''.
> 
> If the unit is a second hand purchase, put the purchase date in ‘Order Number’, for example, '231029'.

-  **Product:** Select the product accordingly.

-  **Serial Number**: Fill in the product's serial number.

-  **Accessory:** Fill in if it's necessary

-  **Invoice Amount:** Select 'US Repair: Spark 40'.

-  **Invoice Address:** Fill in invoice address

-  **Street & House / City / State / Country / ZIP:** Fill in the customer's full address.

-  **Phone number / Email:** Fill in the customer's phone number & Email.

-  **Description:** Copy & paste the User Scenario / Frequency of Use / Defective Frequency.

![](https://lh6.googleusercontent.com/EAamxZ1yeMdxamyiDcaYoAPlFajXdWvGS-nQRkYgw-Z_6UeDMm8pbuQdKlKz5m0ChN8Cx8ZXu1jEfxA4X6Hhyxnun4jTPbyQwhn3yE04ZLP4ndwsHvnLK4Lr9zev145jlL6oclvqWIdxX095VpBeq9pwhZQCVuGiKR9QFcSkdBRc6I3x6R1TuCSqJXiG)

---
For Vix Hsieh:
>JIRA Status: 'Invoice Needed' 
>
>Assignee: Automatic (Vix Hsieh)
---
### 2-2 - Check the registration status
Check the registration status by the serial number. Registered products must be deregistered before being sent back to Positive Grid.

Go to [Portal](https://portal.positivegrid.com/warranty/search-warranty-period) and remove the registered item if it's necessary.
![[Pasted image 20240710102318.png]]

### 3 - Offer info for return
Once the request is submitted, follow the steps below and offer the info for return:

A. Insert the corresponding RMA number in the subject & context. 

![](https://lh6.googleusercontent.com/pxkKNAaNDkH6QfDu8fZRZ81_TESes5OuLWqK-Qlxbapc1XRTK6e8NtxoZfbRQY4gqks_ZM-CytI-K3jRn5Q8kUqlvCYj8xaMmYraqknWl4ZUeOiM1zrT-pIoVV8FNqJ80GihxJ7vLZ5-a9jWRym-nMDikYLeqQzbHBpMmmZ_ZMi3d-IzVBfjxsjqbb6W)


B. Ask the user to send the item back to the following address (already informed in the first email), and provide the TRK#:

Name: Jeff Stielau  
Company: Shoreline Electronics & Sound / SES AUDIO  
Address: 344 East Main Street, Clinton, CT 06413  
Phone: (860)-399-1861
Mail: fixmyamplifier@aol.com

C. Submit as pending.

### 4 - Check the tracking# for the returned package
After receiving the tracking number along with the corresponding carrier information from the customer, please add this information to the JIRA ticket.

![[Pasted image 20231116170835.png]]

Once the TRK# is logged, inform the customer that the repair will be done within 10 business days and the repaired unit will be shipped back in the timely manner. 

When everything is done, close the Zendesk and JIRA ticket. (END)

![[Pasted image 20231116143311.png]]
