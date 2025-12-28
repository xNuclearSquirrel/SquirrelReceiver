# SquirrelReceiver

SquirrelReceiver is a desktop application for receiving and recording digital FPV video streams from DJI Goggles on a Windows PC directly over WiFi.

## Compatibility
* **Goggles:** DJI Goggles 2, DJI Goggles 3, DJI Goggles N3.
* **OS:** Windows 10 or 11 (64-bit).

## Setup and Activation

To use SquirrelReceiver, you must configure your Goggles and activate the software using the SquirrelCast Android app.

### 1. Goggles WiFi Configuration
The Goggles must be on the same network as your computer to transmit the stream.
1. Connect your Android phone to the DJI Goggles via USB OTG.
2. Open SquirrelCast and navigate to the **Utilities** tab.
3. In the **Goggles WiFi Settings** card, enter your local Wi-Fi SSID and Password.
4. Tap **Set** for both fields.
5. The Goggles will reboot and connect to your network.

### 2. Software Activation
SquirrelReceiver requires a one-time hardware activation via the SquirrelCast Android app.
1. Launch SquirrelReceiver on your Windows PC.
2. Open the **Settings** menu to display the unique **Unlock QR Code**.
3. In SquirrelCast on your phone, navigate to the **Utilities** tab and tap **Scan Unlock QR**.
4. Scan the QR code displayed on your PC screen.
5. A License Key will be generated in the Android app.
6. Enter this key into the activation field in the Windows app.

### 3. Usage
1. Ensure your PC is on the same Wi-Fi network configured in Step 1.
2. SquirrelReceiver will detect the stream automatically once the Goggles are powered on and connected to the network.
3. Footage is saved directly to the `Documents/SquirrelReceiver Recordings` folder when the **Record** button is used.

## Troubleshooting

### Connection Issues
* **Network Mismatch:** Verify that both the PC and the Goggles are connected to the same 2.4GHz or 5GHz band of your router.
* **Firewall:** Ensure Windows Firewall is not blocking incoming UDP traffic for SquirrelReceiver.
* **IP Changes:** If the Goggles receive a new IP address from your router, the stream may take a few moments to re-establish.

### Activation Issues
* **HMAC Key Entry:** Ensure the license key is entered exactly as shown in the Android app, including dashes. 
* **QR Visibility:** If the QR code fails to scan, ensure your PC monitor brightness is sufficient and there is no glare on the screen.
