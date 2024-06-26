# Quick Start Guide

## Watch Training Videos
[MacOS For Beginners](https://support.apple.com/guide/mac-help/get-started-with-your-mac-mchl3a2c2cb0/mac)

[Lighting Deployment](https://vimeo.com/user134801363/review/929875058/0a1da2fc42)

[Lighting Manager](https://vimeo.com/user134801363/review/861382651/3ae32264c8)

[Savant Community Documentation Portal (must sign in)](https://beta-community.savant.com/knowledge/Lighting-Documentation-Lighting-Portal)

## SAM 



## Blueprint Loading of the Template
* Select the Blueprint icon (top right square) to open Blueprint
* Click File->"Open Template" then Navigate to /Users/shared/Builder/Builder Template Example"
* ![](OpenTemplate.png)
* Click File->"Save As..." and save the file to a unique name, to a Folder of your choice (Documents/MyBlueprintFiles)

## Onboarding
* Open the SP&L and get the devices onto Wi-Fi.  They will be discovered in the app via BLE.  You must onboard one of the wireless dimmers, switches or keypads.  After that, you can use the RAD protocol to have the devices self-propagate the credentials to all of the devices in the home:


## Wi-Fi Discovery
* Press the slide out icon at the top right: ![](FirstLightingManager.png)
* Then click Discover
* ![](Discovery.png)
* Click Identify to flash the LEDs on the keypads.  Click button below icon in discovery column to add it to the select zone (select it first in the middle column).  Use Quick Bind or Quick Add here to onboard via button press from the keypad.
* ![](DragToZone.png)
* Finish adding all of the keypads into the rooms making sure you:
1. Make the Layout and Location correct
2. Select Always On if this keypads load will be controlling a load with Cync bulbs, strips and fixtures.
3. Give the Load name a unique name and if it is in a location other than the physical keypad, uncheck the "Tracked" checkbox. If it is not wired to a load then check the "Not Wired" checkbox.
4. Select the button and assign it to a previously created Scene, Lightbank or Load.
5. Click Sync.. at the bottom right then click Done.

## Save and Upload
* Hit Command-S to save this file.
* Now you want to upload the configuration to the host
* ![](UploadToMaster.png)

## Complete Guide

[Complete Wireless Lighting Deployment Guide](https://sav-documentation.s3.amazonaws.com/Product%20Deployment%20Guides/009-1807-00%20Wireless%20Lighting%20Deployment%20Guide.pdf){:target="_blank"}
