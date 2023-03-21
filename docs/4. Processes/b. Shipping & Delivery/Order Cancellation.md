# Order Cancellation Process
1. Once the customer contacts for order cancellation, first verify whether the order is already shipped (by internal order checking and see if tracking number is already available).
	1. If the order is not yet shipped (no tracking number available), reply with Macro: Spark Cancellation (Not Shipped) (Modify if needed).
	2. If the order is shipped (tracking number is available), reply with Macro: Spark Cancellation (Shipped) (ask the customer to refuse the shipment) (Modify if needed).
	3. If the order is delivered prior to the cancellation request, the order cannot be canceled and the customer must proceed with the sales return (SR) process.
2. Fill in the Supt-Logistics Form -> Cancellation request.
   
3. Once submitted, check back on Supt-Logistics Form (Responses) the next working day. 
	1. If the cancellation is successful, our logistics team will mark it as ‘Successful’. The agent can then escalate the ticket to Maines for refund. (<u>END</u>)
	2. If the logistics team marks it as ‘Unsuccessful’, it means the order is still shipped. Contact the customer and ask them to refuse the shipment (as in macro <u>Spark Cancellation (Shipped)</u> (Modify if needed)) if this is not yet communicated to the customer. (<u>Proceed with Step 4</u>)
	   
4. If the order is shipped and the customer is instructed to refuse the shipment, check back on the tracking number to verify if it’s returned to sender or delivered.
	1. If the tracking number shows ‘Return to Sender’, update it accordingly in Supt-Logistics Form (Responses). Then the agent can then escalate the ticket to Maines for refund. (END)
	2. If the tracking number shows ‘Delivered’, update it accordingly in the form. Contact the customer to ask if they still want to return the order and be refunded. (Proceed with Step 5)
   
5. If order is delivered and
	1. the customer wants to keep the order, update it accordingly in the form as ‘Order Kept’. Case can be closed. (END)
	2. the customer still wants to return the order for refund, update it accordingly in the form as ‘SR’ and proceed with the sales return process. (To be continued [[SR - Fail to Intercept]])