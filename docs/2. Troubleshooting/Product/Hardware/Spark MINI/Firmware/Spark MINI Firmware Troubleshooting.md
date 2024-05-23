# Spark MINI Firmware Troubleshooting
> 
> If the issue is related to the computer failing to detect the Spark MINI, check [[Priority of Connection (Spark MINI)]].

## Firmware update error

### Stuck at 2% / Error Code: -2 
- Ask the user to try again. Make sure to connect Spark MINI to the computer and launch the updater, THEN power on Spark MINI.


> If customer encounter any issue during/after the firmware v1.11.2.75 update and fail to perform it successfully, please follow the following steps:

~~*Note: Since March 2023, there is a new version of Spark MINI with the newer GD codec chip. Since GD is the latest Spark MINI version, it should have the latest firmware already installed when manufactured. Users with GD version Spark MINI do not need to update the firmware.*~~

You can determine a Spark MINI's version by looking at the 7th digit of its SN: 

- `1` is the  old version; 

- `2` is the latest GD version.


### 1 - Verify the SN
If the firmware update still fails, ask the customer to provide a clear photo of the serial number of the Spark MINI.

If the 7th number (the letter after "G") of the SN is 1, e.g. S1011G**1**xxxxxxxx, please use the macro and provide the updater with logs:
<u># Spark MINI::Firmware Update Log (STM)</u>.

or 

If the 7th number (the letter after "G") of the SN is 2, e.g. S1011G**2**xxxxxxxx, please use the macro and provide the updater with logs:
<u># Spark MINI::Firmware Update Log (GD/MCU)</u>.


The macro includes new updater tools with logs for both Windows and Mac with step-by-step instruction. It also adds the tag "firmware_new" for us to monitor the trend of this issue.

The firmware version should read as "1.10.2.57" once update via the firmware updater successfully complete.

If the workarounds resolve the issue, the case can be closed. (END)

If the issue persists after the troubleshooting, ask the customer to provide the log file (generated with the updater tool) for further verification. 


### 2 - Examine the log file
If the update wasn’t successful, use the information below to examine the log file and suggest corresponding solutions:

1.  Error code -10: 
   The installation was canceled by the user.
2.  Error code -11: 
   Python installation timeout, please try again. The installation of Spark Firmware will be aborted.
3.  Error code -13/-14: 
   Python installation can not be completed, please try again. The installation of Spark Firmware will be aborted.
4.  Error code -15: 
   Spark Firmware installation timeout, please try again. Something went wrong during the update process, please disconnect the USB cable, then long press the power button for 10s to force shut down Spark MINI. Then reboot the Spark MINI and the updater to try again.

### 3 - Bluetooth Issue

If the customer updates the firmware with log successfully, but the Spark MINI have the Bluetooth connection issue.

Please use the macro and provide the BT firmware updater:

<u> # SparkMINI::BT Firmware Update</u>

If the workarounds resolve the issue, the case can be closed. (END)

---
### Internal Information

The firmware updater with log will not update the Bluetooth firmware on Spark MINI.
<u># Spark MINI::Firmware Update Log (STM)</u>.
<u># Spark MINI::Firmware Update Log (GD/MCU)</u>.

