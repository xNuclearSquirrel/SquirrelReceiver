# Buying and Installing SquirrelReceiver Pro

SquirrelReceiver Pro is the Microsoft Store version.

Pro includes Wi-Fi live view and the wired USB live view path. Wired mode is the main reason to choose Pro: it is cleaner than Wi-Fi, usually has lower latency, and charges the goggles while connected.

<!-- TODO: Add the Microsoft Store product link before publishing. -->

## Buy and install

1. Open the Microsoft Store page for SquirrelReceiver Pro.
2. Buy the app with your Microsoft account.
3. Install it from the Store.
4. Start SquirrelReceiver Pro from the Start menu.

Planned price: **USD $20**. Store pricing can differ by region.

## License status

Pro uses the Microsoft Store for licensing. It does not use the QR unlock flow from Lite.

If SquirrelReceiver Pro says it is not licensed:

1. Make sure you are signed into the Microsoft Store with the account that bought the app.
2. Open the Microsoft Store app and check for app updates.
3. Restart SquirrelReceiver.
4. Restart Windows if the Store license state still looks stale.

> **Note:** Microsoft Store licensing is handled by Windows and the Store. The app can show the license status, but the purchase itself is managed by Microsoft.

## First setup

For the best live view path, use wired mode:

1. Connect DJI Goggles 3 to the PC with USB-C.
2. Enable **Liveview sharing** in the goggles.
3. Open SquirrelReceiver Pro.
4. If video does not start, follow [USB Wired Setup (Pro)](usb-wired-setup-pro.md).

You can also use Pro over Wi-Fi. For that path, follow [Wi-Fi Liveview Setup](wifi-liveview-setup.md).

## Why wired mode is different

The wired path sends the live view over USB instead of over the goggles' Wi-Fi network.

That has three practical benefits:

- Much fewer video artifacts from packet loss
- Lower latency, usually around 100-150 ms and best cases around 75 ms
- The goggles charge while connected

Cable quality and USB negotiation still matter. If the goggles do not connect correctly, use the cabling notes in [USB Wired Setup (Pro)](usb-wired-setup-pro.md).
