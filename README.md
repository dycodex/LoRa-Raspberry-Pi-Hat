LoRa Raspberry Pi Hat
=====================

LoRa Raspberry Pi Hat is an extension for Raspberry Pi that lets you send data over long distances with an extremely low data rate. This board is compatible with Raspberry Pi 2 Model B and Raspberry Pi 3 which is perfect for you--makers--who wants to experiment with LoRa and LoRaWAN.

Detail on [Makestro's Shop](https://shop.makestro.com).

![LoRa Raspberry Pi Hat](https://shop.makestro.com/wp-content/uploads/sites/2/2016/08/loraraspihat0.jpg)

![LoRa Raspberry Pi Hat top view](https://shop.makestro.com/wp-content/uploads/sites/2/2016/08/loraraspihat1.jpg)

![LoRa Raspberry Pi Hat with antenna](https://github.com/dycodex/LoRa-Raspberry-Pi-Hat/raw/master/assets/pihat11.jpg)

![LoRa Raspberry Pi Hat with antenna](https://github.com/dycodex/LoRa-Raspberry-Pi-Hat/raw/master/assets/pihat12.jpg)

## Features

* Frequency band of 868 MHz/433 MHz (factory pre-configured).

* Low power consumption.

* External antenna via I-Pex connector.

* On-board 8-channel analog-to-digital converted (ADC) via I2C.

* Compatible with Raspberry Pi 2 Model B/Raspberry Pi 3.

* LoRa™ Modem.

* FSK, GFSK, MSK, GMSK, LoRa™and OOK modulation.

## Pinout

![LoRa Raspberry Pi pinout](https://shop.makestro.com/wp-content/uploads/2016/08/lora_pinout-01_1024.jpg)

## Getting Started

Before you use the board, you'll have to enable SPI from raspi-config first. See [this link](https://learn.sparkfun.com/tutorials/raspberry-pi-spi-and-i2c-tutorial) for the tutorial.

Then, install the bcm2835 library on your Raspberry Pi. See [this link](http://www.airspayce.com/mikem/bcm2835/) for tutorial and library source code.

bcm2835 is required for code examples that we're about to show you.

Note that when you're using LoRaWAN, you need to plug the jumper to the GPIO8 and NSS header.


### Code examples

* [Simple LoRa Gateway](https://github.com/dycodex/Simple-LoRa-Gateway)
* [Single Channel Packet Forwarder (LoRaWAN)](https://github.com/andriyadi/single_chan_pkt_fwd).
* [RadioHead by hallard](https://github.com/hallard/RadioHead). You can check for the code at the `examples/raspi/rf95` directory.

### Use Cases Example & Tutorials

* [PatientCare](https://www.hackster.io/andri/patientcare-8ca30b)
* [Publishing Data from Node to Bakckend via LoRaWAN](https://learn.makestro.com/publishing-data-from-node-to-backend-via-lorawan/)

