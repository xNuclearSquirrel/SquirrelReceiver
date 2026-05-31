# SquirrelReceiver

SquirrelReceiver is a Windows app for receiving live video from **DJI Goggles 3** on a PC.

It can receive the goggles' built-in Wi-Fi live view, and the Pro version also supports a wired USB mode with lower latency, fewer artifacts, and charging for the goggles while you fly or test.

<p float="left">
  <img src="liveview.png" alt="Enable Liveview sharing in DJI Goggles 3" height="240" />
  <img src="manuals/images/squirrelreceiver.png" alt="SquirrelReceiver receiving video on Windows" height="240" />
</p>

## Lite and Pro

There will be two versions:

| Feature | SquirrelReceiver Lite | SquirrelReceiver Pro |
| --- | --- | --- |
| Wi-Fi live view from DJI Goggles 3 | Yes | Yes |
| Wired USB live view | No | Yes |
| Charges the goggles while receiving video | No | Yes, in wired mode |
| Expected wired latency | Not available | Usually around 100-150 ms, best cases around 75 ms |
| Recording | Yes | Yes |
| Lens correction and LUTs | No | Yes |
| Detached video window | No | Yes |
| Custom waiting screen logo | No | Yes |
| Unlock path | SquirrelCast Android app | Microsoft Store purchase |
| Price | Free receiver download if you already own SquirrelCast | Planned Microsoft Store price: USD $20 |

SquirrelReceiver Lite is meant for the Wi-Fi workflow. Unlocking it uses the SquirrelCast Android app, which is a separate paid app, about USD $7 depending on region.

SquirrelReceiver Pro is the recommended version if you want the best live view path. The wired mode avoids most Wi-Fi packet loss problems and keeps the goggles charging while connected.

> **Note:** Store pricing and regional availability can differ. The final Store link will be added here before release.

## Compatibility

- **Goggles:** DJI Goggles 3
- **OS:** Windows 10 or Windows 11, 64-bit
- **Wi-Fi mode:** Available in Lite and Pro
- **Wired USB mode:** Pro only
- **SquirrelCast:** Needed to configure goggles Wi-Fi and to unlock Lite

SquirrelReceiver is not an RTSP or WebRTC receiver. It receives the direct live view stream from DJI Goggles 3.

## Quick Start

### If you use Lite

1. Install SquirrelReceiver Lite.
2. Unlock it through the SquirrelCast Android app.
3. Configure the goggles' Wi-Fi in SquirrelCast.
4. Enable **Liveview sharing** in the goggles.
5. Connect the Windows PC to the goggles' Wi-Fi network.

Read: [Installing SquirrelReceiver Lite](manuals/installing-squirrelreceiver-lite.md) and [Wi-Fi Liveview Setup](manuals/wifi-liveview-setup.md)

### If you use Pro

1. Buy and install SquirrelReceiver Pro from the Microsoft Store.
2. For the best video path, connect the goggles by USB-C.
3. Enable **Liveview sharing** in the goggles.
4. If Windows does not already have the right adapter settings, follow the wired setup guide.

Read: [Buying and Installing SquirrelReceiver Pro (Pro)](manuals/buying-and-installing-squirrelreceiver-pro.md) and [USB Wired Setup (Pro)](manuals/usb-wired-setup-pro.md)

> **Important:** Liveview sharing must be enabled in the goggles for both Wi-Fi and wired mode. This is easy to miss.

## Manuals

- [Installing SquirrelReceiver Lite](manuals/installing-squirrelreceiver-lite.md)
- [Buying and Installing SquirrelReceiver Pro (Pro)](manuals/buying-and-installing-squirrelreceiver-pro.md)
- [Wi-Fi Liveview Setup](manuals/wifi-liveview-setup.md)
- [USB Wired Setup (Pro)](manuals/usb-wired-setup-pro.md)
- [Using Live View](manuals/using-live-view.md)
- [Recording Video](manuals/recording-video.md)
- [Lens Correction and LUTs (Pro)](manuals/lens-correction-and-luts-pro.md)
- [Detached Video Window (Pro)](manuals/detached-video-window-pro.md)
- [Custom Waiting Screen Logo (Pro)](manuals/custom-waiting-logo-pro.md)
- [Troubleshooting](manuals/troubleshooting.md)

## Support

For questions, feedback, or compatibility reports, join the Discord:

[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?logo=discord&logoColor=white)](https://discord.gg/rv37TDFwcX)

Privacy policy: link will be added here before release.

## Credits

Thanks to Joonas for the help when developing this, and thanks to everyone who tested early builds and reported what worked and what did not.

## Support the Project

If you find this project useful, consider donating to support development.

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/donate/?hosted_button_id=BSA49E6J5DLM4)
