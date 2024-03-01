# Spark 40 Firmware Troubleshooting
> Firmware update fail, unsuccessful. 
> Issue/No sound after firmware update.

If the customer has a Spark but never ran the firmware before, refer to 'Firmware Update for Spark 40 with Super Old Firmware Version' 


> If the customer encounters any issue during/after the firmware v1.7.5 update and fail to perform it successfully, please follow the following steps:
 
### 1 - General troubleshooting
Reply with Macro: <u># Spark Amp::Firmware Update Troubleshooting</u>

The macro includes the general workarounds and the information required (Spark 40 SN) for our team to further investigate. It also adds the tag "firmware_new" for us to monitor the trend of this issue.

If the workarounds resolve the issue, the case can be closed. (END)

### 2 - Verify the SN
[[Spark 40 Serial Number Check Tool]]

If the issue persists after Step 1, we need the Spark’s SN to verify the codec chip and offer the firmware updater accordingly:

> [INTERNAL INFORMATION - DO NO REVEAL TO CUSTOMERS]
> 
> Since 2023, there are 3 versions of Spark 40, with differences in the codec chip - namely the AKM, ADI, and GD chips. The transition from AKM to ADI has been implemented around late 2020 - early 2021. The transition to GD has been implemented around 2023 march. 
> 
> The functionality of all Spark versions are exactly the same. 

#### GD version
> SN# Range: The 6th number of Serial Number is D, E, P, Z
> i.e. S040CDxxxxxx, S040CExxxxxx

GD is the latest Spark version and has the latest firmware already when manufactured. Users with GD version Spark amp do not need to update the firmware.

Macro: <u># Spark Amp::Firmware Update Log (GD)</u>
 

#### AKM version
> SN# Range: The 6th number of Serial Number is 1, 2, 3, 4, 5, 6, 7, 8, A
> i.e. S040C1xxxxxx, S040CAxxxxxx
> 
> **Special Cases:** 
> -   S040CB1M, S040CB11, S040CB12, S040CB18, S040CB19 are all AKM (Use AKM macros instead)
> -   S040C619 (S040C6190001~S040C6190560) are all ADI (Use ADI macros instead)

Reply with macros: <u># Spark Amp::Firmware Update Log (AKM - MAC) v1.7.5</u> / <u># Spark Amp::Firmware Update Log (AKM - WIN) v1.7.5</u> (depends on the system used). 

The macros include new updater tools that's designed specifically for the AKM version and provide step-by-step instruction. 


#### ADI version
> SN# Range: The 6th number of the Serial Number is 9, 0, B, C
> i.e. S040C9xxxxxx, S040CCxxxxxx
> 
> **Special Cases:** 
> -   S040CB1M, S040CB11, S040CB12, S040CB18, S040CB19 are all AKM (Use AKM macros instead)
> -   S040C619 (S040C6190001~S040C6190560) are all ADI (Use ADI macros instead)

Reply with macros: <u># Spark Amp::Firmware Update Log (ADI - MAC) v1.7.5</u> / <u># Spark Amp::Firmware Update Log (ADI - WIN) v1.7.5</u> (depends on the system used). 

The macros include new updater tools that's designed specifically for the ADI version and provide step-by-step instruction. 


If Step 2 resolves the issue, the case can be closed. (END)

If the issue persists after Step 2, ask the customer to provide the log file (generated during Step 2) for further verification. 

### 3 - Examine the log file
Check the log file to verify if the update was successful. 

If at the very end of the log shows ‘Updating 100%’ and ‘Firmware Upgraded’ messages, it means the update was successful.  

![](https://lh6.googleusercontent.com/nMbEzBdyRIzV69Yy4a8kPSZBC1A3vZQV-etdWv7T7Gt97eMyIbE4PhACTkupkznsFyiU3_4Xw0OBt8GCADweBp_brwUFi0bfLgn_KucpqlFizUZbxm3rk2j9NVg6pt3BN7O9ADlCcPOkMjNSUH0NNw)
(Log successful info)

![](https://lh5.googleusercontent.com/izRS2F1nmwE4Mkb3kgFcuCrozyDS84gowQkjTHvT0MC3Pn246LK6Te6gFlniU7frZRd8MD2IJTs9jEIqWyQbLgI4DQ36QLCZc9S5lRO3BpX3_35l_ORIl88t6o4nE_4H-PiMA8LCTA8_R6q9zOJNcQ)
(Log successful result)

#### Update successful but no sound
**If the update showed to be successful but the Spark 40 amp has no sound after update, offer the other version of the log tool (offer ADI log tool for AKM machines, and vice versa).** This should resolve the no sound output issue (after firmware update). If the issue is indeed successfully resolved by the other log tool, please highlight the case alongside the Spark amp’s SN to <u>Dans Huang</u> via Slack.

#### Update unsuccessful
If the update wasn’t successful, use the information below to suggest corresponding solutions:

##### No device found
System cannot find the device, perform USB connection troubleshooting

1.  Switch USB port and cable
2.  Unplug all other USB devices
3.  Avoid using a USB hub
4.  Switch to another computer

![](https://lh5.googleusercontent.com/LkRF9cR5pdoICl3WmHNEYu0Hb6TaTTuBBODW6Se0R1PBse3K46Xf74rSUBiZJhuUnMpmS6pHTjwcwhPROJUtSctqlVxawt39EZvmk5189vRvKQ4fRuYdf41xorpKf1fdJ_Y8a_8xgxgOUXvQhABUqg)
(Log no device)

##### Log Error
Firmware upgrade failed for a specific reason

1.  ‘Sector len’ & ‘checksum’ all show 0: 
   Spark cannot start up normally. Change to another USB port and try updating again.
2.  Error code 13/14: 
   The computer cannot detect or communicate with the computer once entered the updating mode. Try unplugging and re-plugging in the USB device in this situation.  
3.  Error code 15:
   The updater’s directory contains non-English. The updater needs to be placed in an English-only directory, such as C:\. 
4.  Error code 16: 
   Update got aborted in the process. Try again after switching the USB port.

![](https://lh6.googleusercontent.com/zTg_1RZeuGNfntoYBPmmVZcJYdXFjDbyeu02b4DOcBGEsbbomdxJ5qP0-9qUPzowJw3NscW-Ti6mYGzELNvRiNEPWctCPJwlY4g_ErbHmi01WGUEZhlBM_kLcC-gYbLsKQszTgJB8NjSXnaTOz9RHg)
(Log error)