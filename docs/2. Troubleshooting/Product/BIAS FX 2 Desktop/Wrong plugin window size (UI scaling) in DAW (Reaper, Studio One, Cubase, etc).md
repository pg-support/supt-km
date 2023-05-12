# Wrong plugin window size (UI scaling) in DAW (Reaper, Studio One, Cubase, etc)
> On Windows computers, in certain DAWs such as Reaper/Studio One/Cubase, BIAS FX 2 plugin might show the wrong window size (too big/too small), part of the plugin window is black/white, or cropped UI.


## Studio One

![[Pasted image 20230221140844.png]]

![[Pasted image 20230221141417.png]]


1. Disable High DPI mode in Studio One
![[Pasted image 20230221142248.png]]
  
2. Go to Windows display/scaling setting and try to set it to 100% as well.

## Reaper
![[Pasted image 20230221142512.png]]

1. Close REAPER.
2. Right-click on the REAPER icon and select Properties.
3. In the Compatibility section, please enable “Override high DPI scaling behavior.” and select scaling performed by: “System”.
4. Launch REAPER and insert BIAS FX 2 again.


Resources:
[Cubase 11: Using DPI-unaware plug-ins on Windows – Steinberg Support](https://helpcenter.steinberg.de/hc/en-us/articles/360017509919-Cubase-11-Using-DPI-unaware-plug-ins-on-Windows)
[High-DPI monitor support – Ableton](https://help.ableton.com/hc/en-us/articles/209775985-High-DPI-monitor-support)
[High DPI awarenes for plugins - Cockos Incorporated Forums](https://forum.cockos.com/showthread.php?t=215766)
[Disable DPI Awareness in a Plugin - Audio Plugins - JUCE](https://forum.juce.com/t/disable-dpi-awareness-in-a-plugin/50140)