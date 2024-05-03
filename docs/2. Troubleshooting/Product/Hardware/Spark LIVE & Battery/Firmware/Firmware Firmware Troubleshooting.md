# Firmware Firmware Troubleshooting

Symptom: Firmware Updater Bricked the Spark LIVE

> If the customer encounters the issue during/after the firmware ver. 2.1.4.92_rev258 and fail to perform it successfully, please follow the following steps:

### 1 - General troubleshooting

Reply with Macro: <u>#Spark LIVE::Firmware Update Log (MCU) ver. 2.1.4.92_rev258</u>

The macro includes the general workarounds and the information required (Spark LIVE SN) for our team to further investigate. 


---
[Spark LIVE - Alternative Firmware Updater](https://drive.google.com/drive/folders/1j1AUjeZSO3gjvM-bWx29efoa1jfWUxkR?usp=sharing)

1. Unzip the updater file and then launch it.

2. Disconnect the Spark LIVE from the computer by unplugging the USB cable.

3. Unplug the power cable from the Spark LIVE.

4. While holding down the pair button, plug in the power cable again. The Spark LIVE will enter firmware update mode, indicated by a solid white light.

5. Connect the Spark LIVE to the computer using the USB cable, and then click "Next" in the alternative updater.
   
   *The indicator light should be solid white before connecting to the computer. There is no need to hold down the power button and pair button simultaneously to enter the update mode.
   
6. If the update still fails, please locate the log file at “~/Documents/PositiveGrid/” and send it back to us. This will help our product team narrow down the issue.

### 2 - Collect the log file

If the customer still cannot update the firmware using the alternative firmware updater, please collect the log file and escalate the issue to WT.

The log file is saved under:

macOS
“~/Documents/PositiveGrid/”

Windows
"\\Documents\\PositiveGrid"