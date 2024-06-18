# Lighting
Pre-program the Savant lighting requires that you:

* Have a wireless network that is operational in the home.  Please ensure you know the network name (SSID) and the network password.
* All devices are installed and powered
* have Savant Power & Light app installed on your deivce

to Pre-Program the lighting you will

1. using the Savant Power & Light App connect 1 dimmer to the WiFi Network
1. using the RAD method have the 1st dimmer talk to the other dimmers in the house to get them connected to the network

## Savant Power & Light App
Download the Savant Power and Light app from the Apple App Store or Google Play Store

## RAD
Using these steps you can use RAD at any time to connect additional or new keypads to the network using a "Primary" keypad that is already on the network.

1. Set the dimmer that is on the WiFi into RAD Primary mode
    1. Locate the service switch and open it to remove power from the switch
    1. Press and hold top left most button and press and hold it whil closing the airgap and powering the switch on
    1. continue to hold the button for 10 seconds when the button will start to blink white
    1. the LEDs at the top of the keypad will nightrider from the left to the right in white to let you know it is in RAD Primary mode.
![](/img/radprimary.png)

1. set each dimmer that is not on the network yet into discovery mode.
    1. Press and hold the top left most button for 10 seconds when the button will start to blink red
    1. the LEDs at the top of the keypad will nightrider from the left to the right in red to let you know it is in RAD Subordinate mode.

1. Once complete you will need to Exit RAD mode on the keypads. This can be done 2 ways:
    1. Return to the first(Primary) keypad and press the reset button under the faceplate.  this will reset the keypad and exit RAD mode.  This will send a reset command to ALL RAD Subordinate keypads.
	1. Dimmers & Keypads will automatically exit RAD mode after 15 minutes of inactivity.  If you want to manually exit the mode use this.

the blinking lights will tell you when the WiFi has been learned.  Each device once they learn the WiFi network they will begin to broadcast the WiFi network to other devices in discovery mode.

* [RAD](/content/RAD.pdf)