Basically, any MIDI devices that can output MIDI CC and PC messages will work with BIAS FX 2 Mobile.

_*Please note: MIDI control support is only available in the **Pro** or **Elite** version of BIAS FX 2 Mobile._ 

**MIDI CC (Control Change)** allows you to control most of the knobs on a pedal/amp and various features such as the Tuner and Metronome in BIAS FX 2 Mobile.

**MIDI PC (Program Change)** allows you to switch between presets in BIAS FX 2 Mobile.

To set up the MIDI controller with BIAS FX 2 Mobile, please install the MIDI monitor tool:

[MIDI Scope (App Store)](https://apps.apple.com/us/app/midi-scope/id1185667452?platform=ipad)

_*This tool is a third-party MIDI monitor app. It displays the MIDI devices connected to your iOS device and monitors the signals received, which speeds up the entire process._

1. Open MIDI Scope and select your MIDI controller in the app.
![[Pasted image 20240422175902.png]]

_*If your MIDI controller is not listed, it indicates a connection issue._

2. Go to the "Scope" tab and click "Connect".
![[Pasted image 20240422175911.png]]

3. Send a MIDI signal from your MIDI controller and ensure it's transmitting the CC/PC messages on the MIDI channel of your choice.

***Note that BIAS FX 2 Mobile interprets two messages with one command as two separate signals.**

- If you'd like to use the MIDI controller to toggle on/off a pedal, make sure the MIDI controller is sending only one **CC** message at a time.  
  

- If you'd like to use the MIDI controller to control the parameter on a pedal, make sure the MIDI controller is sending a linear value **CC** message with the same MIDI message at a time.  
  

- **MIDI PC** allows you to switch between presets in BIAS FX 2 Mobile, please check the MIDI PC Chart below.
 
![[Pasted image 20240422175944.png]]

4. Now we have confirmed that the MIDI controller is working properly with your iOS device. Let's launch BIAS FX 2 Mobile and get started with the in-app MIDI setup.

5. Go to Settings -> MIDI Settings 
![[Pasted image 20240422180001.png]]

6. Enable MIDI Control and select the preferred MIDI Channel.
![[Pasted image 20240422180013.png]]

7. Go back to the signal chain, and long-press the pedal/amp you'd like to control with a MIDI message.

Example 1: Toggle on/off a pedal

**Make sure the MIDI controller is sending only one message at a time.**

If you want to activate the chorus pedal using MIDI message CC#1, press and hold the pedal to open the "MIDI ASSIGNMENT" window. Then, choose CC#1 for Power Toggle.

_*You can also tap on "LEARN" and send the MIDI message from your controller to the iOS device._
![[Pasted image 20240422180023.png]]

Example 2: Changing the parameter on a pedal

**Make sure the MIDI controller is sending a linear value with the same MIDI message at a time.**

Let's say you'd like to assign the wah pedal with CC#2, press-and-hold the wah pedal to open the "MIDI ASSIGNMENT" window. Then, choose CC#2 for "Wah".

_*You can also tap on "LEARN" and send the MIDI message from your controller to the iOS device._
![[Pasted image 20240422180035.png]]

### MIDI PC Chart

To use the MIDI Program Change message with BIAS FX 2 Mobile, please refer to the chart below:

**Please be aware only the chosen bank can be controlled by Program Change messages**. **We would recommend moving the presets, which you would like to switch via PC message, into the same bank.**

|      |           |                                             |
| ---- | --------- | ------------------------------------------- |
| Sort | PC Number | Channel                                     |
| 1A   | 0         | Follow the MIDI channel in the MIDI setting |
| 1B   | 1         | Follow the MIDI channel in the MIDI setting |
| 1C   | 2         | Follow the MIDI channel in the MIDI setting |
| 1D   | 3         | Follow the MIDI channel in the MIDI setting |
| 2A   | 4         | Follow the MIDI channel in the MIDI setting |
| 2B   | 5         | Follow the MIDI channel in the MIDI setting |
| 2C   | 6         | Follow the MIDI channel in the MIDI setting |
| 2D   | 7         | Follow the MIDI channel in the MIDI setting |
| 3A   | 8         | Follow the MIDI channel in the MIDI setting |
| 3B   | 9         | Follow the MIDI channel in the MIDI setting |
| 3C   | 10        | Follow the MIDI channel in the MIDI setting |
| 3D   | 11        | Follow the MIDI channel in the MIDI setting |
| 4A   | 12        | Follow the MIDI channel in the MIDI setting |
| 4B   | 13        | Follow the MIDI channel in the MIDI setting |
| 4C   | 14        | Follow the MIDI channel in the MIDI setting |
| 4D   | 15        | Follow the MIDI channel in the MIDI setting |
| 5A   | 16        | Follow the MIDI channel in the MIDI setting |
| 5B   | 17        | Follow the MIDI channel in the MIDI setting |
| 5C   | 18        | Follow the MIDI channel in the MIDI setting |
| 5D   | 19        | Follow the MIDI channel in the MIDI setting |
| 6A   | 20        | Follow the MIDI channel in the MIDI setting |
| 6B   | 21        | Follow the MIDI channel in the MIDI setting |
| 6C   | 22        | Follow the MIDI channel in the MIDI setting |
| 6D   | 23        | Follow the MIDI channel in the MIDI setting |
| 7A   | 24        | Follow the MIDI channel in the MIDI setting |
| 7B   | 25        | Follow the MIDI channel in the MIDI setting |
| 7C   | 26        | Follow the MIDI channel in the MIDI setting |
| 7D   | 27        | Follow the MIDI channel in the MIDI setting |
| 8A   | 28        | Follow the MIDI channel in the MIDI setting |
| 8B   | 29        | Follow the MIDI channel in the MIDI setting |
| 8C   | 30        | Follow the MIDI channel in the MIDI setting |
| 8D   | 31        | Follow the MIDI channel in the MIDI setting |
