# Amazon Support SOPs
> This guide covers a range of issues that may arise with Amazon orders and provides instructions on how to handle them.

## Verify the Amazon Order
> **Prior to handling the ticket, it is essential to verify whether an Amazon order is FBA or FBM.**

There are 2 types of Amazon orders: FBA & FBM.

### FBA
FBA stands for "**Fulfillment by Amazon**," which is a service provided by Amazon where sellers store their products in Amazon's fulfillment centers, and Amazon takes care of the picking, packing, shipping, and customer service. 

For any fulfillment issues for FBA orders (e.g. returns, wrong item shipped, tracking inquiries, etc.), **ask customers to directly contact official Amazon Support, as the order is fulfilled by Amazon.**

### FBM
FBM stands for "**Fulfillment by Merchant**," which means the seller is responsible for storing, picking, packing, shipping, and handling customer service for their products.

**If customers have any issues regarding FBM orders, we at PG Support should be responsible for such cases.**

### How to verify
- To distinguish between FBA and FBM orders, click on the menu button at the top-left corner in Amazon Seller Central.

![[Pasted image 20230411161756.png]]

- Find the 'Manage Orders' option under 'Orders'.
![[Pasted image 20230411161836.png]]

- Search for the Order ID in the search bar. 
![[Pasted image 20230411162048.png]]

- Check the "Fulfillment" section in the 'Order Summary' under 'Order Details'. **The 'Fulfillment' section will display 'Amazon' for FBA orders, and 'Seller' for FBM orders.**

FBA:
**![](https://lh4.googleusercontent.com/ZjkQK_4iCq_KnvTZnWG62H45uCC0qN7FTcBl3H00oCyn7KCfNNxlvEAse9OvmNRG_3Tr-ALqvXHUzTUzLuGPaim1X6MxbDc4-B4xgzHt-vI8NKsQqn_zkdo3C1HyezZN0rVNI6x_8_nCDBMRMYYuYIY)**

FBM:
**![](https://lh6.googleusercontent.com/kCPhVFRKwjCrHSf3dKshnVJlch_6q-ufh6xf0odPZ8CyUSRitVDYlPbathYR_GA12vlbsLjTnLjp3-V2E66TpcP5pjo5q9i4ItZbj3GF0xU81c5FTjb8H6jl9-VOb-JSJ0u-xA4RocAfgcbX5HL9Iw8)**

- **For shipping-related inquiries, we only need to handle the FBM orders (which is fulfilled by Positive Grid). On the other hand, we should redirect customers with FBA orders to Amazon Support for shipping-related inquiries.**


---
## Order Shipping Inquiry

Please refer to [[SKULabs Operation]] and [[Daily Catch-Up (JIRA)]] for further details on how to inquire about shipping status. 

### Important Notice
**We do NOT ask customers who bought from Amazon to sign claim forms.**
**We do NOT ask customers who bought from Amazon to sign claim forms.**
**We do NOT ask customers who bought from Amazon to sign claim forms.**

### Shipping Info Missing (for Amazon)

- Daily check the [Shipping Info Missing Follow-up](https://docs.google.com/spreadsheets/d/1JGEB4lF3NW7xdm78EnAu3EREmbbfI07jiRqdN3u9QWw/edit?usp=sharing) form for orders with missing shipping information. 

- Reach out to customers and ask them to verify the missing information:
  
  Amazon Seller Central > Manage Order > Search order number > Click recipient's name > Go to message page > Select 'Problem with order' > Ask for detailed information from the customer > Send message.
  
  Note: 'Problem with order' option might not be available for all Amazon stores for each region. If this option isn't available, simply select the closest option available.

![[Pasted image 20230412160550.png]]

![[Pasted image 20230412161446.png]]

- Once the correct information is verified, update it accordingly in the Shipping Info Missing Follow-up form (highlighted in red in the photo):

**![](https://lh5.googleusercontent.com/jn7V7Csk39aZxwaYxzJSVE8BM9nHxqMkl2TxI8zHiobX1wCm3X4eSbZ6ZHFkyfkLSK1Eei-pLFMkVMWbeJ8YalOeZOBlbzfzprNmGsFQBEUyikXnjtg9NGGH3e_S8p5zA8Pi-F4g6riMOPgUhjzjjmM)**

- Once the form is updated, the logistics team will modify the shipment information accordingly and ship out the order.


---

### Dummy Tracking

- In certain cases, we create 'dummy tracking number' (00000000) to meet Amazon's shipping time requirement.

- These situations can occur due to 

1. Unforeseen slow operation from the warehouse
   
2. Certain items being out of stock and having backlogs
   
3. Orders with incomplete shipping information

#### Unforeseen slow operation from the warehouse
In the case of unforeseen slow operation from the warehouse, the logistics team will sort out the problem and promptly update the correct tracking number for the customer.

#### Out of Stock
For items that are suddenly out of stock and in the backlogs, these orders will be logged onto the [Amazon Tracking (Out of Stock Record)](https://docs.google.com/spreadsheets/d/1nD-WXOWSqSGU1kPgPHjNBVsPenH3vGkMFp8H5ZvwpZQ/edit?usp=sharing) file, with the order ID and estimated delivery date provided by the logistics team. 

A support agent will contact the customer proactively to inquire on whether the customer would like to wait for the restock or cancel the order. If they'd like to cancel, then proceed with [[#Order Cancellation]]. 

If they can wait for restock, the case can be closed until the ETA comes, and then the support agent will reach out to the customer again to inform them about the tracking number.

![[Pasted image 20230412160550.png]]
#### Incomplete shipping information
For orders with incomplete shipping information, these orders should be first logged onto the [Shipping Info Missing Follow-up](https://docs.google.com/spreadsheets/d/1JGEB4lF3NW7xdm78EnAu3EREmbbfI07jiRqdN3u9QWw/edit?usp=sharing) file for support agents to contact the customer for the correct information. See [[#Shipping Info Missing for Amazon]] for further details.

If we fail to acquire the correct information from the customer before the required shipping time, such cases will also be given a dummy tracking number '0000' and logged onto [Amazon Tracking (Out of Stock Record)](https://docs.google.com/spreadsheets/d/1nD-WXOWSqSGU1kPgPHjNBVsPenH3vGkMFp8H5ZvwpZQ/edit?usp=sharing) (without the ETA as it's not out of stock) for further verification. An agent will contact the customer to verify the correct shipping information and feedback to the original [Shipping Info Missing Follow-up](https://docs.google.com/spreadsheets/d/1JGEB4lF3NW7xdm78EnAu3EREmbbfI07jiRqdN3u9QWw/edit?usp=sharing) file for our logistics team to update the order and ship.

---

## Order Cancellation

- For order cancellations, follow the similar process as [[Order Cancellation Process]]:

- If the order shows 'Not started / Opened / Delayed' in SKULab, manually cancel the order, and proceed by clicking the 'Cancel Order' option in the order details in Amazon Seller Central.

- If the order shows 'Awaiting Fulfillment', fill in the [Supt-Logistics Form](https://docs.google.com/forms/d/e/1FAIpQLSdd0Hei0HZSqwf_bzUTIdutMvE_a_N2VGuOc5fta-jwun69PA/viewform) -> Cancellation request. 
  If successful, proceed with clicking the 'Cancel Order' option in the order details in Amazon Seller Central; if unsuccessful, ask the customer to reject the shipment.

![[Pasted image 20230419114234.png]]

- If a customer submit a cancellation request (see below) via the system instead of writing us a support ticket, simply proceed to cancel the order and offer the refund. 
![[Pasted image 20230418175745.png]]


---
## Order Return
### Within 30 days

If the customer contacts us directly to request a return/refund, please ask them to follow Amazon's return policy directly.

When the customer request a refund/return on Amazon, the system automatically provides the following return instructions:

---
We understand that there may be situations where you need to return a purchased product. To ensure a smooth and hassle-free return process, please review the following instructions carefully:

- Returning Defective Products
  
If you believe that the product you received is defective or experiencing any issues, our dedicated Positive Grid support team is here to assist you in resolving the problem. Please reach out to our official support team for troubleshooting guidance. Should it be determined that the product is indeed defective after troubleshooting, we will provide you with a pre-paid return label for either an exchange or a refund.

- Returning Non-Defective Products
  
In cases where the product is not defective, but you still wish to initiate a return for other reasons, please follow these steps to request return authorization through Amazon:

1. Go to Your Orders to display your recent orders.
2. Choose the order and select Return or Replace Items.
3. Select the item you want to return. Then select an option from the Reason for return menu.
4. Choose how to process your return. If applicable, select to issue a refund.
5. Select your preferred return method.
6. Print your return label and return authorization.
7. Add your return label (if applicable) and package your items for return.

*For returning non-defective product, we strongly recommend using the return label generated by Amazon. This will expedite the return process and ensure prompt refund processing.

**Important Notes**

- Shipping Costs:
Customers are responsible for covering the shipping costs when returning products to us, unless the product is determined to be defective.

- Refund:
When returning a non-defective product, using the return label generated by Amazon will expedite the refund process without unnecessary delays. Your refund will be credited to your original payment method once the return is processed.

- Return Authorization (RA) Number:
Before returning any merchandise, please ensure that you have obtained an authorized RA (Return Authorization) number. Merchandise returned without this number or missing accessories may not be accepted.

- Repacking:
When preparing your return, please ensure that you repack the merchandise along with all original accessories, manuals, documentation, and registration materials in the original, unmarked packaging.

- Free Merchandise:
If you received a complimentary merchandise item with your purchase, kindly include it when returning the main merchandise as part of your return application.
These comprehensive guidelines are designed to assist you in navigating the return process, whether you are dealing with product issues or seeking to return a product for other reasons. If you have any further questions or require assistance, please do not hesitate to contact us.

---
### Returning Defective Products

#### Technical issues/Dead on Arrival
- For technical issues/troubleshooting, it's best to advise customers to contact our official support team for further assistance on Zendesk.

- Follow the troubleshooting guides and the DOA/RMA process.
  [[DOA (US)]] [[DOA (Non-US)]] [[RMA (US)]] [[RMA (Non-US)]]


- However, if a customer insists on returning/exchanging the product due to technical issues, ask them to proceed with the official return process (the customer will need to cover the shipping label). 

- Ask the customer to notify us after they ship the product(s). Once the product is on the road, we may proceed with either sending a replacement ([[Resend & Replacement (JIRA)]]) or [[#Order Refund]].


#### Cosmetic damages
- For cosmetic damage, it's best to advise customers to contact our official support team for further assistance on Zendesk.
  
- Ask customers for photos of the damages, as suggested in [[Delivery-induced Damage]] SOP.
  
- Once it's returned, proceed with either sending a replacement (by requesting a replacement as suggested in [[Resend & Replacement (JIRA)]]), or [[#Order Refund]].
  

### Returning Non-Defective Products

#### Personal Reason

Within 30 days of purchase, we should always ask customers to return their unit (no matter the reason) via Amazon's system. This will leave a return record on Amazon and would be easier for tracking:

1. Go to Your Orders to display your recent orders.
2. Choose the order and select Return or Replace Items.
3. Select the item you want to return. Then select an option from the Reason for return menu.
4. Choose how to process your return. If applicable, select to issue a refund.
5. Select your preferred return method.
6. Print your return label and return authorization.
7. Add your return label (if applicable) and package your items for return.

However if the customer is particularly irate about the situation and wants PG to offer a pre-paid return label, please highlight to WeiTing/Dans for further discussion.



### Over 30 days
There's no guaranteed return after 30 days. Ask the customer to contact our official support team for further assistance.


### (Reference Only) Amazon's A-to-Z Guarantee Refund
- A-to-Z refund is a policy offered by Amazon for buyers' protection.

- **It guarantees that customers can receive a refund or replacement for their purchase if they have not received their order or if the item is not as described, defective, or damaged.**

- Customers can file an A-to-Z Guarantee claim on the Amazon website, and Amazon will investigate the claim and take action to resolve the issue. If a claim is found to be valid, Amazon will issue a refund to the buyer, and the seller's account may be subject to penalties or suspension.

**-> We should avoid having customers filing A-to-Z claims at all cost, by attending to the customers diligently.**
**-> A-to-Z Guarantee claim is currently handled by Christine of the logistics team.**


---

## Order Refund

> Due to account restrictions, we are currently unable to process refunds for European orders (the refund option is also not visible on the order). 
> 
> To request a refund for a European order, please obtain the following information and  @Emma Liao in the amazon-support-internal channel (Slack):
> <br>
> 
> 1. Country
>    
> 2. Order number
>    
> 3. Tracking number for the return pacakage

- For returned items, **customer may notify us after they have shipped the product(s), and we'll proceed with the order refund process.** If the customer didn't notify us, they may wait for the system's automatic refund (which will take longer).

- If a customer claims to have not received a refund after proceeding with the Amazon return process, **ask for the carrier and tracking number, and check if it is in transit**. Once confirmed the item is **on its way back** (no need to wait for delivery), we may proceed with the refund.

- To refund an order, find the 'Refund Order' in the order details.
![[Pasted image 20230411175226.png]]

- Fill in all the details for refund and submit. 
![[Pasted image 20230411175441.png]]

- Inform the customer about the refund in the support channel.

---

## Price Matching
- For orders not yet placed, advise the customers 'make the purchase that best suit their needs'. **(It's against Amazon's policy to suggest customers go to somewhere else for purchase.)**

- For orders already placed, we only accept **price matching for offers from the same platform within a week**. Price-matching with other platforms (such as PG website) is NOT possible. 
  
  For Amazon offers price-matching, ask the customer to provide a screenshot of the offer within a week (that is also on Amazon). Once verified, we may offer partial refund.

---
## Repair Service
If the customer want to request for repair service, ask them to contact our official support team for further assistance.

---
## Change Address
Amazon's system does NOT support changing the address of an order. If the situations calls for it (special case), please fill in [[Daily Catch-Up (JIRA)]] to request changing the address at the warehouse side.

---
## Swap / Add / Deduct Items in an Order
Amazon's system does NOT support altering the items in an order. Proceed with [[#Order Cancellation]] process for such inquiries.
