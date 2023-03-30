# Principles for Troubleshooting
Troubleshooting is NOT just about resolving the issue on hand in order to close the ticket.

Troubleshooting also involves processes of collecting the necessary information and highlighting the info to our product team, in order to further improve our products.

We should always aim to fix a product issue at the root, instead of fixing the issue for the one customer by offering some temporary workarounds.

Below are some guidelines for troubleshooting:

### Correctly understanding the question / issue

-   Read the email closely.
    
-   If the user has multiple issues, address them one-by-one.
    
-   If the user seems to misunderstand some part of the product, address them accordingly.
    
-   If the user didn’t communicate the issues clearly, ask them to elaborate, or rephrase their questions and ask them to confirm if your understanding is correct.
    

### Narrow it down

-   To narrow down an issue, is to identify precisely when/where/how the issue happens, and when/where/how it does not.
    
-   As long as there’s more than one possible way to interpret the user’s question/scenario, ask the user to clarify or ask probing questions to further clarify the situation.
    
-   If there’s a series of factors that might lead to the problem, identify where the issue lies by swapping out each factor one at a time.


Some examples to showcase the thinking process:
    

#### “My Spark amp has no sound”
    

-   Spark has multiple outputs, i.e. speakers and headphones.
    
-   Spark also has multiple inputs, i.e. guitar input, Bluetooth audio, Aux In, USB audio.
    
-   The agent should try to identify if there’s no sound for all outputs, or only certain ones.
    
-   The agent should also try to identify if both the guitar sound and audio playback are not working, or only one of them?
    
-   The agent can even further identify if only a specific channel of audio input is not working (Bluetooth, Aux In, USB) or all of them are not working.
    

#### “I’m using RIFF with BIAS FX 2, but there’s no sound”
    

-   The guitar goes from the guitar -> guitar cable -> RIFF (audio interface) -> USB cable -> Computer -> BIAS FX 2 application -> USB cable -> RIFF -> output devices (speakers/headphones).
    

The agent should try to identify at which point in the signal chain the signal got blocked.

-   Is RIFF receiving input signals? If not, then the problem is within the guitar and guitar cable.
    
-   Is the computer receiving input signals from RIFF, i.e. detecting RIFF as an audio device for its system audio? If not, then the problem is within the USB connection (USB cable, USB port, USB hub, etc).
    
-   Is BIAS FX 2 receiving the input signal from RIFF? If not, check if BIAS FX 2’s audio setting is set up correctly and can see RIFF as the audio device.
    
-   Is BIAS FX 2 receiving the input but not producing any output? If so, then check if the audio is blocked somewhere within the program by switching to other presets.
    
-   Is BIAS FX 2 showing output signal but no sound is heard? If so, make sure the output is turned up on RIFF, and check if the speakers and headphones are connected to RIFF correctly and are fully functioning.
    

### Offer solution

-   If it’s a known issue/problem that we already have solutions/talking points for, offer them to the user.
    
-   If it’s not a known problem or that we do not yet have a solution/talking point for the problem, collect the necessary information and highlight the case internally.
    

### Highlight the case when further assistance is needed

-   Ask the user to provide necessary information about the issue (when/where/how does it happen), if not already.
    
-   As of now, highlight all the necessary information to Dans to receive further feedback.
    
-   If any other information is helpful for our team to work on the issue, Dans will then ask the agent to follow up with the user to inquire about them.
    
-   If there’s any temporary workaround to the issue, the agent can then offer it to the user.
    

### Helpful Information (to ask for)

#### Hardware
##### Photo(s) required:
-   Cosmetic damage
    
-   Physical damage
    
-   Shipping-induced damage
    
-   Received wrong item(s)
    
-   Missing certain item(s)
    

##### Helpful with videos:
-   Noise via main-out
    
-   No guitar input
    
-   Popping noise while turning on/off (Spark MINI) (No need for video on Spark 40)
    
-   No sound from any output
    
-   Low volume from any Output
    
-   Noise via Bluetooth
    
-   Speaker Noise
    
-   Abnormal knob/button/switch/LED behavior
    
-   Bluetooth Audio Cutout
    

##### No need with videos:
-   Power issue (Can’t power up / Defective power brick)
    
-   Noise from headphone
    
-   Damage induced by firmware update
    
-   Battery
    

#### Software

-   Device model (iPhone, iPad, Android, etc)
    
-   OS version (iOS, Android, macOS, Windows, etc)
    
-   App version
    
-   Reproducing steps (the more precise the better)
    
-   Screen-recording/Screenshots of the issue
    

##### Template for asking the user to film a troubleshooting video:

We'd need further information to narrow down the issue. Please help us verify the issue:

A). Please film a short video showing your software/hardware setup, along with the issue you're having.

B). Go to WeTransfer (https://wetransfer.com/), hit 'Add Your File' and upload the file.

C). Hit the '...' icon on the bottom left, click on 'Send as link', copy and paste the link back to the email you're reading right now, then hit reply.