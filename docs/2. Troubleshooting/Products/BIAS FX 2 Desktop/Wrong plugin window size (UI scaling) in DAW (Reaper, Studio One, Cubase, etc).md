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