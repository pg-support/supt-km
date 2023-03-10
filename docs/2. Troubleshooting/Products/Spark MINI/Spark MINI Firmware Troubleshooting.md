# Spark MINI Firmware Troubleshooting
> If customer encounter any issue during/after the firmware v1.9.2.34 update and fail to perform it successfully, please follow the following steps:

### 0 - Run as administrator
If the customer encounters the error codes -1 or -2 on their Windows computers, please ask the customer to run the firmware updater as administrator (right click -> select ‘Run as administrator’).  

### 1 - General troubleshooting
If the firmware update still fails, reply with Macro: <u># Spark MINI::Firmware Update Log</u>.

The macro includes new updater tools with logs for both Windows and Mac with step-by-step instruction. It also adds the tag "firmware_new" for us to monitor the trend of this issue.

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
  