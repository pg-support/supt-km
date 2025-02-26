# Regular PSU requests- Check Basecamp for updates
> In the initial release of Spark 40, the power supply units (PSU) we offered were ungrounded. Many customers thus encountered humming noise in their Spark amp. Since then, we’ve been offering grounded PSUs for customers who bought the amp that comes with ungrounded PSU.
> 
> Grounded PSU has been added to the manufacturing of Spark amp since 2020, thus these days most newly-bought Spark amps should have the grounded PSU included. We must verify if the customer’s issue really is related to ungrounded PSU, or otherwise.


1. To verify the PSU, use Macro <u>Spark Hum 1</u>, submit as pending. A grounded power supply should look like the photo on the left. Only proceed with the rest of this process if the customer's PSU is verified to be ungrounded (right).

 ![[Pasted image 20230118173334.png]]
   
2. If the customer has a grounded power supply (left) instead, please inform them about it, as grounding should not be an issue for them. If they still have persistent hum noise, the unit could be faulty. Proceed with proper troubleshooting.
3. Use macro <u>Hum 2</u> to inquire about the customer’s current contact information and product SN#. 
4. Once the customer submits the address, compare it with the corresponding Shopify/BigCommerce order information and make sure the addresses are matched. If they don’t match, double check with the customer. 
5. Once the customer confirms the info to be correct or provides updated info, proceed with the next step.

### US

- Proceed as a free Service Part purchase, see [[Service part request (US) - Check Basecamp for updates]]. (TBC)

### Non-US

1. Request a service part request by submitting a ticket on JIRA ([[Replacement, Resend (JIRA) - Check Basecamp for updates]]).
2. Make sure to fill in full contact information (submitted by the customer during “Hum 2” macro) in the form.
3. After requesting service part on JIRA, please use the macro “Hum 3,” submit as ‘On-hold’ and wait for the tracking number.
4. PSU will be shipped within roughly 2 days. Check back for TRK# and provide it to the customer. (END)