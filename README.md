# SquirrelReceiver

SquirrelReceiver is a desktop application for receiving and recording digital FPV video streams wirelessly and directly over WiFi from DJI Goggles on a Windows PC.

## Compatibility
* **Goggles:** DJI Goggles 2, DJI Goggles 3, DJI Goggles N3.
* **OS:** Windows 10 or 11 (64-bit).

## Setup and Activation

To use SquirrelReceiver, the PC must join the WiFi network hosted by the Goggles. Because the default credentials of this network are typically unknown, you must use the SquirrelCast Android app to configure them.

### 1. Goggles WiFi Configuration
1. Connect your Android phone to the DJI Goggles via USB OTG.
2. Open SquirrelCast and navigate to the **Utilities** tab.
3. In the **Goggles WiFi Settings** card, you can view the current SSID/Password or enter a new SSID and Password.
4. Tap **Set** to push your desired configuration to the Goggles.
5. On your Goggles, swipe down to access the top bar menu and enable **Share Liveview to Mobile Device via Wi-Fi** to broadcast the signal.

![Share Liveview to Mobile Device via Wi-Fi](liveview.png)

6. On your Windows PC, scan for WiFi networks and connect to the SSID you configured in Step 3 using your set password.
### 2. Software Activation
SquirrelReceiver requires a one-time hardware activation via the SquirrelCast Android app.
1. Launch SquirrelReceiver on your Windows PC.
2. Open the **Settings** menu to display the unique **Unlock QR Code**.
3. In SquirrelCast on your phone, navigate to the **Utilities** tab and tap **Scan Unlock QR**.
4. Scan the QR code displayed on your PC screen.
5. A License Key will be generated in the Android app.
6. Enter this key into the activation field in the Windows app.

### 3. Usage
1. Once your PC is connected to the Goggles' WiFi, SquirrelReceiver will automatically detect and display the video stream.
2. Use the **Record** button to save footage directly to the `Documents/SquirrelReceiver Recordings` folder.

## Troubleshooting

### Known issues
* The video can be glitchy once the AU is armed. I think it's related to package loss and a higher frame rate after arming. In version 1.1.0 SquirrelReceiver actively rerequests lost packages. This helps a bit, but some glitches persist, so there are more improvements needed.

### Connection Issues
* **WiFi Connection:** Ensure your PC hasn't automatically switched back to your home internet WiFi. It must stay connected to the Goggles' network.
* **Live Sharing Toggle:** If the video does not appear, verify that **Live Sharing** is still toggled ON in the Goggles' shortcut menu.
* **Firewall:** Ensure Windows Firewall is not blocking incoming UDP traffic for SquirrelReceiver.

* This is still a work in progress! Not all goggles and aircraft have been tested. Some may not work or require changes to the code. I would appreciate any feedback on what works or doesn't work.



##### Credits
- Thanks to Joonas for the help when developing this!


## Support the Project 💖
If you find this project useful, consider donating to support development!

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/donate/?hosted_button_id=BSA49E6J5DLM4)
