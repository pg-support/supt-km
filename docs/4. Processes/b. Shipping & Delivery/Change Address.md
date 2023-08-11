# Change Address
> If a customer requests their order address to be changed, first verify the shipment status to determine whether the address can still be changed.

## Verify the shipment status

1). Log in to SKULabs and navigate to the order management page.

2). Find the order and check its **shipment status**, which is located at the top left corner of the order details page.
   
   ![[Pasted image 20230209170313.png]]
   
3). Determine whether the order is eligible for changing address. The order is only eligible for changing address if it is in 'not started', 'opened', or 'delayed' status. If the order is in 'awaiting fulfillment' or 'shipped' status, the address cannot be changed as our warehouse is already processing the shipment. 
   
   ![[Pasted image 20230209170529.png]]


## Not started / Opened / Delayed 
1. If the order is eligible for changing address, find the order in Shopify and click the 'Edit shipping address' option. 
   ![[Pasted image 20230516170805.png]]
   
2. Fill in all required fields for the new shipping address, then click 'Save'. That's it for the process. (END)


## Awaiting fulfillment / Shipped

If the order is already in 'Awaiting fulfillment' or 'Shipped' in SKULabs, inform the customer that the order is already being processed by our warehouse for shipment / is already shipped, and **additional fee (USD $20 for all regions within the same country) is required for address update**. 

>*We do not support changing addresses across different countries. 

Ask the customer to provide their PayPal account email (or regular email if they don’t have PayPal) if they’re willing to pay the fee. 

This could lead to 2 scenarios:

### Scenario A: Customer will pay the fee
1. Go to JIRA and create a ticket in Project: "Logistics Support (LS)":
   
    Issue Type: Daily Catch-up  
    
    Support Request: Change Address 
    
    Make sure to fill in the PayPal account. 
2. Go Shopify and also update the shipping address on the order.
3. Maines should issue the PayPal invoice directly to the customer’s inbox/PayPal account, and add a comment “Sent” in the Support Comment.
4. Once the customer has paid off the fee, please update the comment  to “Paid”. 
5. Logistics team will then change the address and send out the order. TRK# should be available within 2 days since their update. 

### Scenario B: Customer wants to cancel 
- Proceed with [[Order Cancellation Process]].


## Delivered
- If the package ends up delivered to the original/wrong address, we assume no further responsibility. 

