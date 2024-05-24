# PGBot Commands
'PGBot (pgv2)' is a bot created by our backend team for checking and adjusting users' licenses, account information, and hardware registrations.

PGBot can be found in Positive Grid's Slack channel.

![](https://lh3.googleusercontent.com/jyIsuqypaWBPVDX2F6JBlXxa43BSILTxPS9KqaNL8xOppZKkPkRC2FVW_qv5oX43o3DQN4DoFW-U3gxceNilHAbubIhQ-WVEP3lCBJg3CgWofgSkbsEvznNDzdbQOVuX8ONA-j717712_CHeoHKpgQ)


### Warranty Check Tool
[Warranty Check Tool](https://slack.com/shortcuts/Ft06PZBB8LNL/a086370d6e6b7366b08a351b5f5b6c22)
![[Xnip2024-05-23_17-27-33.jpg]]

This tool helps the support team check a customer’s warranty status using the serial number. 

After the first usage, you’ll be able to summon the bot by typing /Extend warranty expired date” (or simply type “/w” or “e”/).

**The SN should be 100% identical to the label shown (all caps)!**

![[2222.jpg]]

- Result 1: "Failed"
  
The customer has not registered their product yer.
	
	![[Pasted image 20240524134203.png]]
	
	
Or the SN doesn't 100% match to the label shown.
	![[Pasted image 20240524134258.png]]
<br>
<br>
- Result 2: "The warranty expiration calculation is not complete yet!!"
The customer has registered their product, but has not verified its warranty.
	
	![[Pasted image 20240524133845.png]]
<br>
<br>
- Result 3: "Warranty End Date"
The customer verified their product's warranty and the warranty end date will be displayed in the result.
	
The extend warranty feature is currently unavailable, please ignore it.
If you’d like to share the status with the customer, cut off the lower part (Extend Date).
	![[Pasted image 20240524133520.png]]



### Software / Account
>PGBot commands mostly apply to desktop software licenses. Mobile license may or may not show up correctly. 
>
>Ask @ferrari in # backend-issue for further details if necessary (also see [[Backend issue report]])

[How to Activate a Software License]

- Purchase completed (order shown in Shopify)
- Account registered (with the same email on the order)
- License registered (automatically, under the same account)
- Program installed and logged in (with the same correct account)
- License activation not exceeding limit (5 activations max)
- If the user has exceeded 5 activations, they can go to the user center to remove their past activations.
![[Pasted image 20230424112817.png]]

### Check activation records
1. Enter the account email and find the ‘Show Activation Info’ option under the license you want to check.
2. You’ll see the activation record of the software license, including the total activation records.
3. If the activation reaches 5 computers, the user will not be able to further activate on a new computer. Proceed by resetting the license activation records for the user.

![](https://lh6.googleusercontent.com/8D0DarTbDcUaibaiUjj6HaK51n7k3xwpCZMvCIQtZyqEVsRFQX_OxhrGchILIWDOcNBEzfQyz83fKyF22bOBrsLG9JMj0jdQ-zSC09KNd_KLI2ye66hRYEanJ5D-bId7kRlr_AfSiUvON1A_uV9KQQ)

![](https://lh3.googleusercontent.com/9SAfgL1yRLOAef4j_B-MtZtZdmAQsUsF2eH7QHNUVecT_TZsvAzDsWMpRGGaj3Zl2NRTsrzWicVbLZJ2--WU1MUPKc57w_ItgfNIxnkaKewgjqu4nutBI4bvqU-8nsrHaIO-pxOX8s7zYSMytYajpQ)

### Reset license activation records (Desktop)
> Scenario: User has reached the activation limit (5 computers), resulting in demo mode in their software. 

1. Find the ‘Deactivate all devices’ button under /pg_license, if the user’s license has activation records. 
   If there’s no such button, it means the license hasn’t been activated yet. 
2. Email reply:
   
> Thanks for taking the time to write to us. 
> 
> We've reset your license activations from the back-end system. Please logout and login to ToneCloud again to see the changes. 
> 
> Let me know if everything's working correctly. Thank you.

**![](https://lh5.googleusercontent.com/zhJ0Yd4oS4nsju2N4pg_g7mXKB3Y4vUgKea79dgrbyV6CnELnsgy1cxYNbF86bnPeFfvIxiLncmj7UOSpQw9wcmvrDr2Almt9h32SCwwYbJDH-H44wmyaZk0W0UrCv1KDtK-GqGtgzbMmQ3mPiakug)**

### Reset license activation records (Mobile)
> Scenario: User has reached the activation limit (5 devices), the app (BIAS FX 2 Mobile/Spark app) shows activation limit message.

To deactivate the license, please navigate to the related relevant topic in "backend-issue" channel on Slack:
https://positivegrid.slack.com/archives/C4H4P850X/p1690251649714899


1.Before you use this tool, you have to click "Start Workflow" button from the link below:
[https://positivegrid.slack.com/docs/T0250SJH7/F05JH75JULC](https://positivegrid.slack.com/docs/T0250SJH7/F05JH75JULC)

![[Xnip2023-08-08_15-03-20.jpg]]

2.Select "backend-issue" to run this workflow:
   
 ![[Xnip2023-08-08_15-03-42.jpg]]

3.Type in the customer's Positive Grid account and select BIAS FX 2:
   
![[Xnip2023-08-08_15-06-14.jpg]]

4.The result will be listed in the "backend-issue" channel:

![[Xnip2023-08-08_15-07-28.jpg]]

Once you use the tool, you will be able to use the command on Slack in the future.
*This command is only available in the "backend-issue" channel*

Command: /iap



If you can't find the command, please follow the steps from the top again.

![[Xnip2023-08-08_16-08-02.jpg]]


### Transfer license
> Scenario: User wants to give away a number of licenses to another user.

1. Insert /pg_license (<u>email</u>) and hit enter.
2. Hit ‘Transfer license’ and insert the account email you want to transfer the license to.

**![](https://lh3.googleusercontent.com/6mWuHdkturXmtQr0B8-DN2lDUr_eIycv_rVl9lfLRYghX55ir9Rc6cppZdspiA0BkvbguhdcBd2cMSapQxC6sjHLsZ4yUclpmT6K4Q7mOkeC5TvcuOQ0_c_tZdRsCichvLEut0IZWXewtzU3OI-vAg)**

**![](https://lh3.googleusercontent.com/lrvHTj0N8qej3kyPatYiG1g6Jqq849Fxy5hT77-NW2o6a8ATiIVHuH0PTNgI-XiRHQ_xWmyZpx7Sr_eIEogKzy3Q87Ty7NiWS9sPOXE09iNqaitt9UuPEhQ9c1WuL0i81ZKZgLrgr68kgt_qnvMevA)**

**![](https://lh5.googleusercontent.com/rtVtJwwjLxnTw_xM4KVsQX9AIJvJm_sze7pJD2RrezRhrmUadfPGQ98kYcF-_FK0nR20-U8TYDFb-BBbg_LPk28GSbBNQUyRXaoLN411926lb5bSGCFH22LgxstM5H8CK3wR1hrPpXj2GY14UsKyKg)**

### Convert license to another product
1. Find ‘Convert license to other product’ button under /pg_license.
2. Find the product you want to convert to. 
3. The bot will ask you to double check.

**![](https://lh3.googleusercontent.com/-vU-h3FFqoUrMpG88Wd88SjkflEAxiiDXvRETUnnZxZUw07HxJ_Y96Br0zjWIjsg7xLStudqXADISrfVsrmHT8z9UdcXEAtur0W0lMkHrQPdwDQxOnvfplkNx6aXBnU2rx2su20txrlL0-gSYB0Rsg)**

**![](https://lh3.googleusercontent.com/NkSrjpFtjAr3sja4qAQn9UHoUedTm7lw_9JBzaJpusH0NrbpE-jjIRywivZY6LVdv3xCrBE5pmiqeRBicHe0uCNs8xmwiGm_UaFx74tHzBQxgFsez1maFa_6TYpNkSK7uX5xh1t9gFiByMWlsPPAlA)**

### Find redeem code
> Scenario: Find the license details of a certain redeem code, as the user is having issue redeeming a code. (Normally, redeem codes are provided by 3rd party vendors or support team.)

Insert /pg_find_redeem (<u>code</u>) to find further information on a code, whether it’s redeemed or not. 

![[Pasted image 20230302134732.png]]

![[Pasted image 20230302134817.png]]

### Migrate account (move all licenses)
Scenario: User wants to move all licenses to another account, or wants to change their login email (since we don’t allow changing the account email, user must sign up a new account for us to migrate the old one into).

***Note: Inform the customer that the Cloud Banks feature in BIAS FX 2 is linked to the Positive Grid account. After the successful migration of two accounts, Cloud Banks associated with those accounts will be removed.*** 

1. Insert /pg_user_info (<u>username or email</u>) to find the customer’s user data.
2. Hit the ‘Migrate account’ button and insert the account email you want to migrate to.
3. The bot will list out all the details and ask you to double check. 
4. Email reply:

> Thanks for getting back.
> 
> Your account is successfully migrated. Please login and check if everything's working for you.
> 
> Feel free to let us know if you have any other questions. Thank you.

![](https://lh4.googleusercontent.com/RMKqmL_BMmnlmyAV51w6R5RfBnawkfelxSqm26YHcN6jN3Zg7pqR56DaSvrKnwLnvyeoWy-JEWv7-LxyoX06rzxZgFg7QrZjZccLR8mt5h7PZyUfoQ6s3xFbUspiyLb1hCHJJ8tyH_P0kOMBC5ssaQ)

**![](https://lh4.googleusercontent.com/w8P3gpJUmqMGsGzSdKARjE-_-W37J7jlk3nqLyYjN9EeNYIBRU_ga2OlOAQ2wss4a8PMimyOf4aa0xsa6G-DYxrf2-J7F0KWP-V-W4BDAMEn_xamNH8qJWxYIm9ssyDXox6AP6JdwDWHrdJpU1Whvg)

![](https://lh3.googleusercontent.com/Lrtnun92z8XHK3i6b19twkhWxfeIwTLLFhDpB3a_LKNHH9Tww-PfgVeOFDtV_r90t0rHJxLLY0ZfQ_00618Jl9UVRlqla8zSuHk4CQIrPYVXDFgnv68ywxnsMQ4zCQE_B9xExcT6hi-zhQbpHcj1ew)

![](https://lh6.googleusercontent.com/UMcTxsFYDCoKlgy3fx4BY7bV-53jnLr5FofpcRBZA8_B-GVVYK_WLzUsZI9WGC_OQLptcN5i02KFxPLVZm1GhwoWGnhhzBiOiWPg_wVawh7G_B6l2l1n54LGSBJGXTdeP59D1P4evxrKEoRH9l_wNw)

![](https://lh3.googleusercontent.com/SabtgWl0N7QUeQcPi68XaPOmPTBWn2BrQDVZcGg8cQPiZ0wbBa3kLEfNj0Cd2QBK76xhLVX9j_q1v6sTu3pdOsYOAfdJhNVY0jKNUh41YpK9V-B4yOu3NphKnHG4TL4MOFQVCyAF_v1N7qAEDUOnPg)


### Reset password
> Scenario: User wants to reset password, or cannot fulfill the password requirement for some reason thus needs us to help reset their password.

1. Find the ‘Reset password’ button under /pg_user_info. 
2. After hitting the reset button, the new password will be generated. 
3. Email reply:
> Thanks for taking the time to write to us and sorry for any inconvenience.
> 
> We've reset your account info to the following:
> 
> Account: (Paste accordingly)
> Password: (Paste accordingly)
> 
> Please try login again and see if that works. 
> 
> See also:
> [How to reset my password?](https://help.positivegrid.com/hc/en-us/articles/210353033-How-to-reset-my-password-)
> 
> Hope that helps. If you have any further questions feel free to shoot me an email. Thank you.

**![](https://lh5.googleusercontent.com/MvVzZxLygBn9ag3BClk6GKs6lVdJR_ooQsLCG1VWbHD422uvXqh5nFL9zPNdLdtCqVKQYCGYcl8CL7rGflWqXgMJ7_M9zqXSu_iv0nZ17sJzwjhwyFITxQjj-vHS3FnUeuGEdsXmqxwY521_vQ8RIw)**

**![](https://lh6.googleusercontent.com/4mwHyYcQmfnPd9kt_f9znQ3Lmf1BsHbccwQm8DocKJ5gs3aA3vB76p-8JIq_SUcT8MwFNqwj-SJgvehRrcAyNmpbeZF64RvMWxzhgmS70uXEF8dUVQH33Ib6CIJYwkwLncDZ5eudrFa_DsmZjW5RXg)**

---

## Hardware SN / Activation

### Inject Spark SN into database
>*This first command is solely for injecting unrecognized Spark SN into the database. Please make sure to verify the user’s Spark amp purchase or get a photo of their Spark’s SN before registering the SN for the user.

/hw_sn_assign (<u>SN</u>)

![](https://lh6.googleusercontent.com/1fIH7UOn6XWN7sK0x_YYahnDCuq68Dnzhjs8TINWsEWWryvWr0rneWfLtSVlNhmRVYORxfrnpkwmWaa6Z2M2I_lxTOcj6G3LlCTUqkfxlDXsDOqgmud0lr2RcymAcgNJUzxaJgQMUaZKny5abLCjftI)

![](https://lh3.googleusercontent.com/qbFsjRXBjup_0O2gv-xy3RdqhtgceUyBGw8ryzb4HNRXfG-Of3hkgYYwqjUOjwSPSZmxFNnbpe9fDZBBqZzG1MrIiuCEEyBej3QULz06R5qs-t1ZIeomWWtTudqZFscmbbNgqSne3woQQaY__FLxoMs)



> The following commands apply to all hardware products that allow SN registration, such as Spark 40, Spark MINI, BIAS Head, BIAS Rack, BIAS MINI.
> 
> Use slack commands to implement these tools. You can type `/hard….` and the full command should automatically come up.

### Get helping messages
/hardware_activation help 

**![](https://lh6.googleusercontent.com/m_uPV1S07L3cnwa_ATreXjxCPXl3dZHVEXFXPkJwrvbeBKVJ3nSAhDVH6HcJ5jYSAnl4qXzbg1cMwcgqcmUBy80OQvENooI1UAHoJBr0gHbzU7mg9pS4PaXKuB2g4cAQvN6IKlBBG6nQUQ5EqkdDSQ)**

### Search SN / user email
/hardware_activation (<u>search term</u>) -  Search term supports SN & user email address.

- PGBot shows ‘Not support search term format’ - PGBot cannot recognize the format. Please ask the customer to clarify the SN and make sure it’s typed correctly.

- PGBot shows ‘Series Number not exist’ - PGBot can recognize the format (as our product) but cannot find it in the database. Verify the product SN and use /hw_sn_assign to inject it to the database.


###  ![](https://lh3.googleusercontent.com/N-k9XX4vEXJGddr4mc0eqWa7WMatEdttI87_ri0Uxwc9YOLZaa5kXvjAupkx7UFB3rmZ-pEErr-5_rGbfmvTRVMBktprIi06fubtw6kbWST87M7DuVODXNA1ViItnHAp9mpIDEl21KsWaBbeX6YJLw)

![](https://lh5.googleusercontent.com/fhYlEgma09tbypTmcn7p4gEgu7JM30bzNPD2gAiLkRIk0HiHc2NtTuuBG3-Ge32XCWX5adkgiUYRHCxrwF2_D4FJSACjhysnwvLLNSOtPyS47gS6cCkcP9_upXFEXuRbgAllSj9w48tBDm-zw0qKrA)**


### Deactivate SN activation record
> Scenario: Only applies when the currently-registered user requests their SN activation to be deactivated. 

/hardware_activation deactivate (<u>SN</u>)

- When entering a SN, the system will verify if the SN is valid or not.

**![](https://lh4.googleusercontent.com/TGdcBD-dfMxUPlaTWMFRUIAiUZDjif3NPV-tPbuq7-6jZi1OL-jO9M_5VpTiHPlvnRmFQWS-vw6uDva7nNJ8gUQAcmxVOksDNvyHd_kD1g8T5aD9tMrElTVN3YWfTo8oJBaeI5CzMe62BLfZmgjF4A)**

- When a valid SN is entered, it’ll return with such a message.

**![](https://lh4.googleusercontent.com/RL7rCRib-iusDHJR-lSItgJhuxUlF0VbZYYS73iEd15L_EUdA9F1tLjGB8l92urZsJJ3v7BUBohOYhLqWgfptlL7j7ZZrgaB0-3EiQ7zJJUv_Q3PGTlp-ZWKq0EPetqGAUhFwuS4ODRcn657gdC_eQ)**