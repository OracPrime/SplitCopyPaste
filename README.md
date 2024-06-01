This is a set of scripts for Reaper DAW to enable copy and pasting of a set of splits from one track or lane to another.

I recommend attaching each script to a button: I give them text icons of "copy splits" and "paste splits".

If you have two tracks, lanes or takes in reaper where you wish to split the second into items in the same times as a first track then:

1) Select the split items on the first track. Execute copySplits.lua
2) Select the item you want to split at the same times
3) Excecute pasteSplits.lua

The splitting process is non-destructive, so you can stretch items to recover missing bits if required.  And of course Undo is supported
