# USB Wired Setup (Pro)

Wired USB mode is a SquirrelReceiver Pro feature.

It receives the DJI Goggles 3 live view over USB instead of Wi-Fi. It is usually cleaner than Wi-Fi, has lower latency, and charges the goggles while connected.

Expected latency is usually around **100-150 ms**. The best cases can be around **75 ms**.

> **Important:** Liveview sharing still needs to be enabled in the goggles. Wired mode does not replace that goggles setting.

## Before the first wired use

If you are using a goggles/PC combination for the first time with SquirrelReceiver Pro, Windows may need a one-time adapter setup.

Do that first: [First-Time USB Adapter Setup (Pro)](usb-wired-first-time-adapter-setup-pro.md)

After the adapter is set once, normal wired use is just connecting the goggles and starting SquirrelReceiver Pro.

## Cable setup

The best setup is a USB-C port on the PC with a USB-C to USB-C cable directly to the goggles.

Normal USB-A to USB-C cables can also work, but they usually charge the goggles more slowly.

OTG adapters can work, but put the OTG adapter on the **PC side**, not on the goggles side.

## Connect the goggles

1. Connect DJI Goggles 3 to the PC by USB.
2. Enable **Liveview sharing** in the goggles.
3. Start SquirrelReceiver Pro.
4. Wait a few seconds for the wired video path to start.

If the live view does not start and this is the first time using this PC/goggles combination, follow [First-Time USB Adapter Setup (Pro)](usb-wired-first-time-adapter-setup-pro.md).

## If USB-C connects the wrong way

Sometimes USB-C negotiation picks the wrong role. The goggles may think they are the USB host, while the PC treats the goggles like a charger.

If SquirrelReceiver does not see the goggles:

1. Unplug the cable.
2. Replug it.
3. Flip the USB-C plug around.
4. Try another USB-C port if the PC has one.
5. Repeat a few times if needed.

If that still does not work, use the goggles menu:

1. In the goggles, open **Settings**.
2. Go to **About**.
3. Select **OTG Wired Connection to Computer**.
4. Wait until the goggles show that they are connected.
5. Exit the screen and return to live view.

This can leave a small OTG wired mode label in the bottom right of the goggles view. It does not hurt the connection, but it can be annoying. You can usually turn it off from **Status** in the goggles menu. If the connection drops after turning it off, enable the wired mode screen again.

The behavior can be a little random between cables, USB ports, and PCs. Try the normal plug/replug path and the goggles OTG menu path if one of them does not work cleanly.

## Advantages of wired mode

The wired path sends the live view over USB instead of over the goggles' Wi-Fi network.

That has three practical benefits:

- Much fewer video artifacts from packet loss
- Lower latency, usually around 100-150 ms and best cases around 75 ms
- The goggles charge while connected
