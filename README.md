# AE-Telex
Monome Teletype for the AE modular ecosystem

![IMG_3227](https://github.com/fauxcyrillic/AE-Telex/assets/127664178/527f82d5-5370-488b-b85e-9f9e13fd010e)

Work in progress, first version seems to tentatively work pretty well.
Not too many major changes required, as most of the Teletype innards run off a regulated 5v / 3.3v anyway. Changed the op-amp scaling as appropriate for a 0-5v world. Still, recreating the whole schematic from scratch was quite a task!

Loads of testing required before this is a confirmed 'thing', but feel free to take, inspect, and improve as you wish.

# Observations so far

Works ok with my RK61 keyboard as long as I *connect the Telex end of the usb cable first*. Turned the backlight off (although it seems fine with it on)

Had a couple (2) of 'crashes' (screen went off, scripts still running, had to power-cycle rack), at least one of which might be related to me messing with the keyboard connection during use as above

On the other hand, I've also had a number of long sessions with no issues at all; will continue to monitor to judge frequency

Reading the IN jack with nothing connected reads a value in the region of 50-60 even after calibration. Not sure if this is normal, and there's no reason to read it without a connection anyway. When patched the GND it reads 0 correctly

Not sure of the correct procedure for loading scenes with the onboard button so can't say if its working as expected. Are you supposed to hold it down when scrolling?

TO DO / IN PROGRESS: tighten up some panel tolerances (around sockets and USB jack)

TO DO: adjust code to max at 5v? Will test to see if necessary

TO DO: confirm best way to connect OLED

TO DO: Test with a bigger cap on power (330 or 470uF)

TO DO: check neccessity of cap before screen - bigger? smaller? Not needed at all?
