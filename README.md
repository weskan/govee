# Govee

[![Add To Installation](https://marketplace.signalrgb.com/resources/add-extension-256.png 'Add to My SignalRGB Installation')](signalrgb://addon/install?url=https://gitlab.com/signalrgb/Govee)

## Getting started
This is a simple SignalRGB Addon to add support for Govee Wifi Devices to SignalRGB.

## Known Issues
- Devices that do not support Lan Control do not work.
- Scanning for devices may take a very long time.
- Devices that do not support Razer Chroma will show up as a single zone.

## Installation
Click the button above and allow signalrgb to install this extension when prompted.

## Support
Feel free to open issues here, or join the SignalRGB Testing Server and post an issue there https://discord.com/invite/J5dwtcNhqC.

## Local H6048 changes
- Added a custom H6048 (Govee Gaming Light Bars Pro) profile as two subdevices.
- Mapped each bar as a 63-LED horizontal strip for the most stable SignalRGB behavior.
- Fixed subdevice RGB packing so the second bar no longer overwrites the first bar in the output buffer.
- This is a practical SignalRGB mapping, not a guaranteed exact physical three-sided LED layout.
