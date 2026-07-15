---
layout: page
title: Water Polo Board
---

<p style="text-align: center;"><img src="/assets/wpboard.png" alt="Water Polo Board icon" style="width: 160px; max-width: 45%; height: auto; border-radius: 22%;"></p>

Water Polo Board is a small wireless receiver you bring to the pool. It feeds live timing and score to the [Water Polo Camera](/wpcam) and [Water Polo Referee Companion](/wprefassist) apps over Bluetooth. It only listens; it never transmits to or interferes with the scoreboard equipment.

## How it works

The pool's scoreboard already broadcasts its timing wirelessly. The board quietly listens to that broadcast and passes it along to your phone over Bluetooth. That is the whole job: a receiver, one way, always listening and never talking back.

## Getting one is easy

You do not have to wait for us to sell hardware. The board runs on an affordable, off-the-shelf developer board about the size of a stick of gum. Pick one, load our free firmware onto it once, and you are set:

- <a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener">M5Stack NanoC6</a>: the smallest of the three, and it comes in a tidy little box.
- <a href="https://www.amazon.com/dp/B0D2NKVB34?tag=lgias-20" target="_blank" rel="noopener">XIAO ESP32C6</a>: small and beginner-friendly.
- <a href="https://www.amazon.com/dp/B0DCGB5QSR?tag=lgias-20" target="_blank" rel="noopener">ESP32-C6 dev board, 2-pack</a>: a dependable workhorse, and you get a spare.

<p style="text-align: center; margin: 1.5rem 0;">
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 18px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: middle;"><img src="/assets/nanoc6.webp" alt="M5Stack NanoC6" height="120" style="display: block; height: 120px; width: auto; border-radius: 12px;"></span>
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 18px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: middle;"><img src="/assets/xiao-c6.jpg" alt="Seeed XIAO ESP32C6" height="120" style="display: block; height: 120px; width: auto; border-radius: 12px;"></span>
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 18px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: middle;"><img src="/assets/devkitm.png" alt="ESP32-C6-DevKitM-1 developer board" height="120" style="display: block; height: 120px; width: auto; border-radius: 12px;"></span>
</p>

<small>As an Amazon Associate, LGIAS earns from qualifying purchases.</small>

After that it could not be lower maintenance: keep it in its antistatic bag, power it from any USB battery pack (you can even plug it into your phone), and it starts listening. The one-time firmware load takes a couple of minutes and is covered in our setup guide. The firmware is free to load yourself, so building your own is a first-class path, not a workaround.

## A ready-made version is coming

We are also building our own turnkey board so you can skip the DIY step entirely. It is not ready yet. Below are our board design and an early working prototype.

<p style="text-align: center; margin: 1.5rem 0;">
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 22px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: top;"><img src="/assets/wpboard-c-cad.png" alt="Board layout for our own Water Polo Board, revision 2" width="200" style="display: block; border-radius: 16px;"></span>
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 22px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: top;"><img src="/assets/wpboard-c-prototype.jpg" alt="Working prototype of our own Water Polo Board, coming soon" width="200" style="display: block; border-radius: 16px;"></span>
</p>

---

<small>* Compatible systems include wireless water polo timing from Colorado Time Systems. LGIAS is not affiliated with, endorsed by, or sponsored by Colorado Time Systems, which is a trademark of its respective owner.</small>
