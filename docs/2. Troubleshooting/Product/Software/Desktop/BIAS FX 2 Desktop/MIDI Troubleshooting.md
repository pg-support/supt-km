# MIDI Troubleshooting

Most of the cases related to MIDI assignment is caused by the incorrect setup.

The agent can use the following macro to request a video from the customer, helping to narrow down the issue:

---
I'd need further information to narrow down the issue. Please help me verify the issue:

1). Please film a short video showing your software/hardware setup, along with the issue you're having.

2). Provides me with the screenshots of your audio settings in BIAS FX 2.

3). Please also leave the MIDI monitor open when you're sending MIDI messages to BIAS FX 2.

https://hautetechnique.com/midi/midiview/

4). Go to WeTransfer (https://wetransfer.com/), hit 'Add Your File', and upload the file.

5). Hit the '...' icon on the bottom left, click on 'Send as link', copy and paste the link back to the email you're reading right now, then hit reply.

[How to Upload Files via WeTransfer](https://youtu.be/gxHlKYDZX9s)

---

To narrow down the issue, please download MIDI View & Pocket MIDI first:

[MidiView](https://hautetechnique.com/midi/midiview/)
MidiView is a simple MIDI Monitor app to that shows bi-directional MIDI packages that flows through your machine.

1. Ensure that MIDI Control is enabled in the MIDI Settings, and the MIDI Input is selected in the Audio Settings within BIAS FX 2.
     ![[Pasted image 20240201150954.png]]
	
	![[Pasted image 20240201155330.png]]


2. Check the MIDI device.
	If the MIDI controller is connected to and detected by the computer, it will be listed on the middle of the app (green area).
	
	Also ensure the device's status on the left is "ENABLE".
	![[Pasted image 20240201144057.png]]


3. Check the MIDI Channel and the types of the MIDI messages from the MIDI Controller.
	The MIDI message should be sent from the MIDI controller to the corresponding channel in the MIDI Settings within BIAS FX 2.
	![[Pasted image 20240201150648.png]]
	
	
	BIAS FX 2 can only recognize PC and CC messages.
	
	FYI: [About MIDI-Part 3:MIDI Messages](https://www.midi.org/midi-articles/about-midi-part-3-midi-messages) 
	
	Check whether the customer use the correct types of MIDI messages.
	
	![[Pasted image 20240201145930.png]]
	![[Pasted image 20240201150446.png]]


[Pocket MIDI](https://www.morson.jp/pocketmidi-webpage/)
Virtual MIDI controller, Pocket MIDI allows you to send MINI messages within the computer.


