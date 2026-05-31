# Troubleshooting

Start with the simple checks. Most connection problems are caused by Liveview sharing being off, Windows being on the wrong Wi-Fi network, or USB-C negotiating the wrong role.

## No video in Wi-Fi mode

Check:

- DJI Goggles 3 are powered on.
- **Liveview sharing** is enabled in the goggles.
- The Windows PC is connected to the goggles' Wi-Fi network.
- Windows did not switch back to your home Wi-Fi.
- Windows Firewall allowed SquirrelReceiver on private networks.
- The goggles have an active video source, or Camera View Recording is enabled for testing.

See [Wi-Fi Liveview Setup](wifi-liveview-setup.md).

## No video in wired mode (Pro)

Check:

- You are using SquirrelReceiver Pro.
- Liveview sharing is enabled in the goggles.
- The goggles are connected by USB-C.
- The goggles are charging or otherwise visibly connected.
- Windows shows the goggles adapter.
- The adapter IP is set to `192.168.60.1` with subnet `255.255.255.0` or prefix `24`.

If the adapter does not appear, unplug and replug the cable, flip the USB-C plug, try another port, or use **Settings > About > OTG Wired Connection to Computer** in the goggles.

See [USB Wired Setup (Pro)](usb-wired-setup-pro.md).

## Liveview sharing is easy to miss

This setting must be enabled on the goggles for both Wi-Fi and wired mode.

<p align="center">
  <img src="images/share-liveview.png" alt="Enable Liveview sharing on DJI Goggles 3" width="65%" />
</p>

If it is off, SquirrelReceiver can be installed, licensed, connected, and still show no video.

## Bench testing without an air unit or drone

If no air unit or drone is connected, the goggles may not output a useful signal.

Try one of these:

- Connect an air unit or drone so the goggles receive real video.
- Enable **Camera View Recording** in the goggles and test again.

<img src="images/camera-view-recording.png" alt="Camera View Recording setting in DJI Goggles 3" width="35%" />

## Wi-Fi video glitches

Wi-Fi mode can show artifacts or stutter if packets are lost.

Things that can help:

- Keep the PC close to the goggles.
- Avoid crowded Wi-Fi environments.
- Make sure Windows stays connected to the goggles' Wi-Fi.
- Stop downloads or other heavy network traffic on the PC.

For the cleanest path, use wired mode in SquirrelReceiver Pro.

## Wired mode charges slowly

USB-A to USB-C cables can work, but often charge slowly.

For the best result, use a USB-C port on the PC and a USB-C to USB-C cable. If that connects in the wrong role, follow the cable negotiation steps in [USB Wired Setup (Pro)](usb-wired-setup-pro.md).

## Lite unlock problems

Check:

- SquirrelCast is installed on the Android phone.
- You are scanning the QR code shown by SquirrelReceiver Lite.
- The generated key is entered exactly as shown.
- You are unlocking the same Windows PC that generated the QR code.

Lite activation is hardware-tied. Hardware changes can require a new unlock.

## Pro license problems

Check:

- You are signed into the Microsoft Store with the account that bought Pro.
- SquirrelReceiver Pro was installed from the Store.
- Store updates are installed.
- Windows has been restarted if the license status seems stale.

Pro does not use the SquirrelCast QR unlock flow.

## Recording problems

Check:

- The app is unlocked/licensed.
- Live video is arriving.
- The recording folder exists.
- The disk has enough free space.
- Windows security settings are not blocking writes.

See [Recording Video](recording-video.md).
