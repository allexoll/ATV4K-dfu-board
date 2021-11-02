# ATV4K-dfu-board

This repository contains a schematic for how to make the AppleTV 4K enter DFU mode on reboot.

It is based on what I _think_ [@littlesteve](https://twitter.com/littlesteve) did for his [Apple TV 4K Breakout Board](https://gizmite.com/shop/apple-tv-4k-hacks/apple-tv-standard-breakout-cable/).

Press the button on boot to assert force_dfu the USB needs to be connected otherwise VBUS (5V) wont be present for the voltage divider.

Pin numbering is refering to https://www.theiphonewiki.com/wiki/J105aAP