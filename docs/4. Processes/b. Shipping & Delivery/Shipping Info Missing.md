# Shipping Info Missing

1 . Orders that are missing certain information in their addresses, will be shown as “Opened” in shipping status (in SKULabs), and also listed in the [Shipping Info Missing Follow-up](https://docs.google.com/spreadsheets/d/1JGEB4lF3NW7xdm78EnAu3EREmbbfI07jiRqdN3u9QWw/edit?usp=sharing), each with its rejected reason.  

The order will be listed on the Shipping Info Missing form due to the following reasons:

- Invalid address (wrong zip code, non existent address).
- Invalid phone number.
- Invalid recipient. 
- The initial shipment was returned to the sender (sent back to Positive Grid's warehouse). 
- Address includes P.O. box.
<br>
<br>
2 . Agent needs to ask the customer to provide the renewed information according to the rejected reason. 

***Always search on Zendesk with the order number to check for any existing tickets before sending a new ticket to the customer.***
<br>
<br>
3 . Create a new ticket and apply the macro accordingly:

For the cases include invalid address, phone number, recipient or the package was sent back to our warehouse (return to sender), use the macro:

<u>#Shipping Info Missing::Return to Sender</u>

For cases involving addresses that include a P.O. box, use the following macro:

<u># Shipping Info Missing::POBox</u>

To effectively follow up the case, the macro will rename the ticket title to "Order#PG-xxxxx / Shipping Info Missing".
<br>   
<br>   
4 . Once sent/updated (new address updated in Shopify), fill in the form (END).  
macro: <u>#Shipping Info Missing::Address Updated</u>
   <br>
5 . Logistics team will follow up on the form and ship out the updated orders.
<br>
6 . Don't forget to close the ticket **with a proper reason**, e.g. "No reply from the customer, refunded" or "RS item delivered, Order#RS-PGXXXXX", and update the status to **Order Shipped / Delivered / Resolved** on [Shipping Info Missing Follow-up](https://docs.google.com/spreadsheets/d/1JGEB4lF3NW7xdm78EnAu3EREmbbfI07jiRqdN3u9QWw/edit?usp=sharing). 
<br>
<br>
We only need to manage orders on Shopify and Amazon, please disregard any other orders.

Shopify orders: PG-xxxxx, EU-xxxxx, UK-xxxxx, etc...

Amazon order: xxx-xxxxxxx-xxxxxxx 
(begins with three number and dash)
Please tag the agent responsible for Amazon operations this month in the Supt-Private channel and inform them of the situation.

![[Xnip2023-08-08_16-16-29.jpg]]