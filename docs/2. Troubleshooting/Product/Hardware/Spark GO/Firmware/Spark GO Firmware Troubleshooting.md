# Spark GO Firmware Troubleshooting
## Firmware update error

### Stuck at 2% / Error Code: -2 
- Ask the user to try again. Make sure to connect Spark GO to the computer and launch the updater, THEN power on Spark GO.


- If issue persists, please offer log tool with Zendesk macro *Spark GO::Firmware Update Log* and see if it works.

### Error Code:  13/14
- After entering update mode, the computer doesn't recognize the device or fails to communicate with it. Try unplugging and reconnecting the USB, then run the update again.

- The error code indicates Python installation can not be completed. Please ask the user to try and again with the correct updating process, as instructed on the Help Center.
  
- If issue persists, please offer log tool with Zendesk macro *Spark GO::Firmware Update Log* and see if it works.

### Error code: 15
- The path contains non-English characters. Move the updater or log tool to a path with only English characters, such as C:.

### Error code: 16
- The update failed midway. Try switching the USB port and run the update again.


### Firmware Update Fail

- Ask the user to try again. If issue persists, please offer log tool with Zendesk macro *Spark GO::Firmware Update Log* and see if it works.
  
- Please highlight the log to Dans for further investigation.

---

## Firmware update broke Spark GO

### Firmware updated, amp power on but no sound

- Try factory reset
  
- If issue persists, please offer log tool with Zendesk macro *Spark GO::Firmware Update Log* and see if it works.
  
- If issue persists, please highlight to Dans and WeiTing, and collect the machine back to Taipei office for further investigation.

### Firmware updated, Bluetooth no longer connects

~~- First, verify if the connection issue has to do with the **known issue** where **devices running refresh rate higher than 60hz will cause Spark app to disconnect**.~~  
  
- If the issue only occurs after firmware update, ask the user to forget previous Bluetooth connection on their phone, and try connecting again.
  
- If issue persists, please offer log tool with Zendesk macro *Spark GO::Firmware Update Log* and see if it works.

- Please highlight the log to Dans for further investigation.

### Firmware bricked the amp, cannot power on

- If the amp is totally bricked and cannot power on anymore, please proceed with DOA/RMA. 
  
- Highlight to Dans and WeiTing, and collect the machine back to Taipei office for further investigation.

