# USB Airplay for A1639 Apple HomePods

First-generation Apple HomePods can be connected via USB to a Mac and function as a local "USB" Airplay 2 Speaker. This is still Airplay, with all it's pros / cons, just over USB. The HomePod / Mac appear to be creating a virtual network adapter over the USB connection. 

Observations / limitations so far:
* Only seems to work on Macs
* Only seems to work if the HomePod is already set-up. Does not work on a HomePod in Setup Mode
* Does not seem to work if the HomePod is configured as a "Default Output" for an Apple TV
* Needs at least least HomePod Version 14.0? 13.X did not work, so I assume older versions also won't work
* Can play to multiple HomePods via USB using "Airfoil" by Rogue Amoeba (plus other Airplay 2 speakers.) 
* Connecting a stereo-paired HomePod via USB will only play audio to the USB HomePod
* USB Ethernet adapters, even powered ones, by themselves do not appear to work with the HomePod.
* You can turn off all of your wireless radios and it will still work since this is all over the USB cable. 
* Your HomePod's WiFi can be completely dead and this will still work, if your HomePod is already configured.

To use, you need to make or buy a USB adapter for your pod. Whatever you end up doing to get USB access to your HomePod will most likely stick out the bottom, so you need to raise the base of the pod to prevent damage to the adapter or debug port when placing it upright on a table. I have 3d printable adapters and stands you can make or buy here: https://github.com/UnbendableStraw/homepwn-simple/

Video Demos:
* https://twitter.com/UnbendableStraw/status/1836576917077790951
* https://twitter.com/UnbendableStraw/status/1836848399997620624
* https://youtube.com/live/Je3FnzLNufg

Unknowns:
* Can we get a Mac bridge the connection to the rest of your network?
* Can we get it working on Windows / Linux? 
* Can we get _any_ ethernet adapter to work with this?
* Will updates break / remove this in the future?
