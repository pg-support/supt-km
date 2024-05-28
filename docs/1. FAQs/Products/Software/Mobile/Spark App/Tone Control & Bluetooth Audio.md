# Tone Control & Bluetooth Audio

Tone Control & Bluetooth Audio can be connected to more than one device; however, it depends on the OS.

### **iOS + Android:**
iOS Spark app connects to Tone Control + Android connects to Bluetooth Audio -> Successful.

Android connects to Tone Control + iPad connects to Bluetooth Audio -> Failed.

iPad SPK app先連上SPK GO (BLE), S23+ Android 再連BLE Audio -> 成功
Android S23+ SPK app先連上SPK GO (BLE), iPad再連BLE Audio -> 失敗


### **Android + Android:**
Android connects to Tone Control + Android connect to Bluetooth Audio -> Failed.

Android Note 8  SPK app先連上SPK GO (BLE), S23+ Android在連BLE Audio -> 失敗
Android S23+ 8  SPK app先連上SPK GO (BLE), Note 8 Android在連BLE Audio -> 失敗


### **iOS + iOS:**
iOS connects to Tone Control + Android connect to Bluetooth Audio -> Failed.

iPad SPK app先連上SPK GO (BLE), iPhone 再連BLE Audio -> 成功
iPhone SPK app先連上SPK GO (BLE), iPad 再連BLE Audio -> 成功


### **iOS + macOS:**
iOS connect to Tone Control + macOS connects to Bluetooth Audio -> Successful.

iPad SPK app先連上SPK GO (BLE), iMac再連BLE Audio -> 成功