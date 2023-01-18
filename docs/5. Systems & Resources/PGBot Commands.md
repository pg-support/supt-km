
### Software / Account
*PGBot commands mostly apply to desktop software licenses. Mobile license may or may not show up correctly. (Ask @ferrari in # backend-issue for further details if necessary)

	[How to Activate a Software License]
	- Purchase completed (order shown in Shopify)
	- Account registered (with the same email on the order)
	- License registered (automatically, under the same account)
	- Program installed and logged in (with the same correct account)
	- License activation not exceeding limit (5 activations max)


#### Transfer license
Scenario: User wants to give away a number of licenses to another user.

	1. Find pgv2 in Slack
	2. Insert /pg_license <email> and hit enter.
	3. Hit ‘Transfer license’ and insert the account email you want to transfer the license to.


#### Check activation records
	1. Enter the account email and find the ‘Show Activation Info’ option under the license you want to check.
	2. You’ll see the activation record of the software license, including the total activation records.
	3. If the activation reaches 5 computers, the user will not be able to further activate on a new computer. Proceed by resetting the license activation records for the user.


#### Reset license activation records
Scenario: User has reached the activation limit (5 computers), resulting in demo mode in their software. 

	1. Find the ‘Deactivate all devices’ button under /pg_license, if the user’s license has activation records. 
	   If there’s no such button, it means the license hasn’t been activated yet. 
	2. Email reply:
	   
	Thanks for taking the time to write to us. 
	
	We've reset your license activations from the back-end system. Please logout and login to ToneCloud again to see the changes. 
	
	Let me know if everything's working correctly. Thank you.


#### Convert license to another product

	1. Find ‘Convert license to other product’ button under /pg_license.
	2. Find the product you want to convert to. 
	3. The bot will ask you to double check.

#### Find redeem code
Scenario: Find the license details of a certain redeem code, as the user is having issue redeeming a code. (Normally, redeem codes are provided by 3rd party vendors or support team.)

	Insert /supt_find_redeem <code> to find further information on a code, whether it’s redeemed or not. 


#### Migrate account (move all licenses)
Scenario: User wants to move all licenses to another account, or wants to change their login email (since we don’t allow changing the account email, user must sign up a new account for us to migrate the old one into).

	1. Insert /pg_user_info <username or email> to find the customer’s user data.
	2. Hit the ‘Migrate account’ button and insert the account email you want to migrate to.
	3. The bot will list out all the details and ask you to double check. 
	4. Email reply:
	Thanks for getting back.
	
	Your account is successfully migrated. Please login and check if everything's working for you.
	
	Feel free to let us know if you have any other questions. Thank you.


#### Reset password
Scenario: User wants to reset password, or cannot fulfill the password requirement for some reason thus needs us to help reset their password.

	1. Find the ‘Reset password’ button under /pg_user_info. 
	2. After hitting the reset button, the new password will be generated. 
	3. Email reply:
	   Thanks for taking the time to write to us and sorry for any inconvenience.
	
	We've reset your account info to the following:
	
	Account: (Paste accordingly)
	Password: (Paste accordingly)
	
	Please try login again and see if that works. 
	
	See also:
	[How to reset my password?](https://help.positivegrid.com/hc/en-us/articles/210353033-How-to-reset-my-password-)
	
	Hope that helps. If you have any further questions feel free to shoot me an email. Thank you.


### Hardware SN / Activation
*This first command is solely for injecting unrecognized Spark SN into the database. Please make sure to verify the user’s Spark amp purchase or get a photo of their Spark’s SN before registering the SN for the user.


#### Inject Spark SN into database
	/hw_sn_assign <sn>


> The following commands apply to all hardware products that allow SN registration, such as Spark 40, Spark MINI, BIAS Head, BIAS Rack, BIAS MINI.
> Use slack commands to implement these tools. You can type `/hard….` and the full command should automatically come up.


#### Get helping messages
	/hardware_activation help 


#### Search SN / user email
	/hardware_activation search <term> -  Search term supports SN & user email address.

>PGBot shows ‘Not support search term format’: PGBot cannot recognize the format. Please ask the customer to clarify the SN and make sure it’s typed correctly.
>
>PGBot shows ‘Series Number not exist’: PGBot can recognize the format (as our product) but cannot find it in the database -> Escalate to T2 for further assistance.


#### Deactivate SN activation record
Scenario: Only applies when the currently-registered user requests their SN activation to be deactivated. 

	/hardware_activation deactivate <SN>

>When entering a SN, the system will verify if the SN is valid or not.
>
>When a valid SN is entered, it’ll return with such a message.
