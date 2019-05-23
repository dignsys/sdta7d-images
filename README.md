# Tizen Images for SDTA7D

This project is for sharing Tizen images for SDTA7D.

## Version Information

* Kernel: Linux 4.20.xx
* U-Boot: 2019-01
* Tizen Platform: 5.0

## Target Board

* imx7d-Pico

## Build System

* GBS

## Image Creation Method

* mic

### File Lists

1. Kick start file for creating boot image
   * tizen-unified_iot-boot-armv7l-sdta7d.ks
2. Tizen Boot Image
   * tizen-unified_iot-boot-armv7l-sdta7d.tar.gz
3. Kick start file for creating platform image
   * tizen-unified_iot-headless-2parts-armv7l-sdta7d.ks
4. Tizen Platform Image
   * tizen-unified_iot-headless-2parts-armv7l-sdta7d.tar.gz

### Modified packages

* bluetooth-firmware-bcm
* building-blocks
* peripheral-bus
* peripheral-io
* smartthing-plugin
* systemd
* wlandrv-plugin-tizen-ap6335