### Why Do I Need to Install Python 2 While Updating the Firmware for Spark Amp?

The reason why we need to install Python 2 is that the way to communicate with the Bluetooth module in Spark Amp is with some Python 2 scripts. The vendor of the Bluetooth module said that it’s difficult to upgrade the scripts to Python 3. Therefore Python 2 is necessary to update the firmware of the Bluetooth module. We use the official installer package to install Python 2.7.18. In fact, you can install it yourself from https://www.python.org/downloads/release/python-2718/.


The default installed executable path is `/usr/local/bin/python`. The installed Python is for updating the firmware of Bluetooth module only. You can feel free to uninstall it after the update process is completed.To completely uninstall the installed Python 2.7, please execute the attached shell script. It will remove the files in “/Applications/Python 2.7”, “/Library/Frameworks/Python.framework”, and “/usr/local/bin/py*“. In our case, the other Python 3 framework should remain functional no matter the Python 2.7 is installed or not.