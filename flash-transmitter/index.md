---
layout: page
title: Flash the transmitter (dev)
---

Internal dev tool. This loads the 802.15.4 transmitter firmware onto a board over USB, so it can inject synthetic CTS frames for testing. It is not part of the product and is not linked from anywhere.

## What you need

- A board (ESP32-C6).
- A USB-C cable that transfers data, not a charge-only one.
- A computer running Chrome or Edge. This does not work in Safari, in Firefox, or on a phone.

## Flash it

<div style="margin: 1.5rem 0;">
<esp-web-install-button manifest="/flash-transmitter/manifest.json"></esp-web-install-button>
</div>
<script type="module" src="https://unpkg.com/esp-web-tools@10/dist/web/install-button.js"></script>

1. Plug the board into your computer.
2. Press the button above, and pick your board when the browser asks.
3. Let it run, then unplug the board when it finishes.
