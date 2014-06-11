bf_hotsplash
============

Brightfish Hotspot with NoDogSplash captive portal

For a splash-page open Wifi hotspot based on:

* TP-LINK TL-WDR 4300
* [OpenWrt](https://openwrt.org/ "OpenWrt")
* [NoDogSplash](http://kokoro.ucsd.edu/nodogsplash/)

## Installation

* start up TP-LINK router for first time - connect to
* download [openwrt-ar71xx-generic-tl-wdr4300-v1-squashfs-factory.bin](http://downloads.openwrt.org/attitude_adjustment/12.09/ar71xx/generic/openwrt-ar71xx-generic-tl-wdr4300-v1-squashfs-factory.bin)
* upgrade firmware to OpenWrt image
* reboot router
* enable SSH
* enable both wifi networks
* log in to SSH on [192.168.1.1:22](ssh://192.168.1.1:22)
* Install NoDogSplash with opkg:
    `opkg update`
    `opkg install nodogsplash`
* edit nodogsplash config
* edit splash page