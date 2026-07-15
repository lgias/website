---
layout: page
title: Flash the Water Polo Board
---

Load the Water Polo Board firmware onto a compatible board right here in your browser. Nothing to install, it takes a couple of minutes, and you only do it once.

## What you need

- A compatible ESP32-C6 board (see the [Water Polo Board](/wpboard) page for options).
- A USB-C data cable (a charge-only cable will not work).
- A computer running Chrome or Edge. Flashing is not supported in Safari, in Firefox, or on phones.

## Flash it

<p style="margin: 1.5rem 0;">
<esp-web-install-button manifest="/flash/manifest.json"></esp-web-install-button>
</p>
<script type="module" src="https://unpkg.com/esp-web-tools@10/dist/web/install-button.js?module"></script>

1. Plug the board into your computer with the USB cable.
2. Click Connect above and choose the board's serial port.
3. Choose Install and wait for it to finish.
4. Unplug it. It is ready to pair with the app.

[Back to Water Polo Board](/wpboard)
