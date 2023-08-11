# Order Cancellation Process
> If the order is delivered prior to the cancellation request, the order cannot be canceled and the customer must proceed with the regular sales return ([[SR - Personal Reason (Non-US)]]) process.

## Verify the shipment status

1). Log in to SKULabs and navigate to the order management page.

2). Find the order that needs to be cancelled and check its **shipment status**, which is located at the top left corner of the order details page.
   
   ![[Pasted image 20230209170313.png]]
   
3). Determine whether the order is eligible for cancellation. The order can only be cancelled if it is in 'not started', 'opened', or 'delayed' status. If the order is in 'awaiting fulfillment' or 'shipped' status, it cannot be cancelled and we'll need to ask the customer to refuse the shipment. 
   
   ![[Pasted image 20230209170529.png]]

### Not started / Opened / Delayed 

1). If the order is eligible for cancellation, click on the 'Menu' option in SKULabs and select 'Cancel Order'. Confirm the action and wait for the order status to be changed to 'cancelled'.
   
   ![[Pasted image 20230322170508.png]]
   
2). Once the order is cancelled in SKULabs, proceed with [[Refund Process]]. 

> For refunding Amazon orders, please refer to [[Amazon Support SOPs]].

### Awaiting fulfillment

1). If the order is in 'Awaiting fulfillment', reply the customer with Zendesk Macro: Spark Cancellation (Not Shipped) (Modify if needed).

2). 1. Go to JIRA and create a ticket in Project: "Logistics Support (LS)":
    Issue Type: Cancellation  

3). Once submitted, check back on Logistics Support (LS) the next working day. 

1. If the cancellation is successful, our logistics team will mark it as ‘Successful’. Proceed with the [[Refund Process]]. (<u>END</u>)

2. If the logistics team marks it as ‘Unsuccessful’, it means the order is still shipped. Contact the customer and ask them to refuse the shipment (as in macro <u>Spark Cancellation (Shipped)</u> (Modify if needed)) if this is not yet communicated to the customer. (Proceed with Step 4)

4). If the order is shipped and the customer is instructed to refuse the shipment, check back on the tracking number to verify if it’s returned to sender or delivered.

1. If the tracking number shows ‘Return to Sender’, update it accordingly in [Logistics Support (LS)](https://positivegrid.atlassian.net/jira/software/projects/LS/boards/47). Proceed with the [[Refund Process]]. (END)

2. If the tracking number shows ‘Delivered’, update it accordingly in the form. Contact the customer to ask if they still want to return the order and be refunded. (Proceed with Step 5)
   
5). If order is delivered and

1. the customer wants to keep the order, update it accordingly in the form as ‘Order Kept’. Case can be closed. (END)

2. the customer still wants to return the order for refund, update it accordingly in the form as ‘SR’ and proceed with the sales return process. (To be continued in [[SR - Fail to Intercept (Non-US)]])


### Shipped

1). If the order is shipped (tracking number is available), reply with Macro: Spark Cancellation (Shipped) (ask the customer to refuse the shipment) (Modify if needed).

2). If the order is shipped and the customer is instructed to refuse the shipment, check back on the tracking number to verify if it’s returned to sender or delivered.

1. If the tracking number shows ‘Return to Sender’, update it accordingly in [Logistics Support (LS)](https://positivegrid.atlassian.net/jira/software/projects/LS/boards/47). Proceed with the [[Refund Process]]. (END)

2. If the tracking number shows ‘Delivered’, update it accordingly in the form. Contact the customer to ask if they still want to return the order and be refunded. (Proceed with Step 5)
   
3). If order is delivered and

1. the customer wants to keep the order, update it accordingly in the form as ‘Order Kept’. Case can be closed. (END)

2. the customer still wants to return the order for refund, update it accordingly in the form as ‘SR’ and proceed with the sales return process. (To be continued in [[SR - Fail to Intercept (Non-US)]])

