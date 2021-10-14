## Overview
Warp Revision C adds support for a replaceable battery on a JST-PH connector, battery charging via USB, and a new Bluetooth LE module.

![JPEG image-622FEEC11206-1](https://user-images.githubusercontent.com/86417/137297952-f049b295-af8a-4928-ba61-302ee4fa7dd8.jpeg)


## Switch Settings
- Switch S1: Position 1: OFF; Position 2: OFF
- Switch S2: Position 1, OFF; Position 2: ON

## Battery
JST-PH connector. Polarity: When looking at the top surface of the Warp Revision C board (surface with logo and serial number), the red (positive) conductor will be on the left and the black (negative) conductor will be on the right:

![JPEG image-622FEEC11206-1 copy](https://user-images.githubusercontent.com/86417/137298478-f8602ade-aa2a-4593-acb4-779662c9fb7c.jpeg)


## Connecting via Bluetooth LE
You can connect to Warp using the BGX Commander app on [iOS](https://apps.apple.com/us/app/bgxcommander/id1350920514) and [Android](https://play.google.com/store/apps/details?id=com.silabs.bgxcommander&hl=en_GB&gl=US) (and using similar facilities on Linux, Windows, and macOS):

![IMG_2E5A884E4DB7-1](https://user-images.githubusercontent.com/86417/137298960-21c838d0-3f32-42a1-8cf9-06355bbdd39c.jpeg)

Once connected, select your Warp from the list of devices and you get a terminal into the Warp prompt (or if your firmware is compiled to enable `WARP_BUILD_BOOT_TO_CSVSTREAM`, you get the CSV stream):

![IMG_0313](https://user-images.githubusercontent.com/86417/137297431-26b0c48a-131a-49e0-b8c4-42d4a6dbc8f6.PNG)
