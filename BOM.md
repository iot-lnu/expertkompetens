
# Bill of Material

**IMPORTANT**

Please give us suggestions or drop us questions in Discord. Thanks!

**IMPORTANT**

## Hardware

In order to be able to participate in the course you need to buy **hardware**. 

In the area of IoT there are a vast amount of hardware choices, everything from ST, ESP32, RP2040, Nordic and many more. What does matter is that you are able to get your idea and application up and running, and then later on when building your product choosing the right hardware. In this case it's actually good to start with a well supported platform that can also be programmed with many different high level languages. Also, the case of having wireless connectivity built in to the device is also important.

MicroPython is one of the new kids in the block in IoT, which we are recommending if you haven't an extensive experience in C++. The recommendations for this course is either an ESP32-based board or a Raspberry Pico RP2040 based board (with wireless). This will give some basic functionality in terms of communications, WiFi and BLE. But - in order to build applications on LoRaWAN or any other kind of LPWAN network you will need more radios. One option is to go modular, that is have your basic microcontroller and then build modular devices communicating over a bus. Or, directly go for a microcontroller that already fulfils all the basic radios and have a good software support.

For years Pycom have sold their LoPy4 and FiPy-devices. Essentially an ESP32 flashed with their own fork of MicroPython, and fitted with radios for LPWAN networkls LoRaWAN and SigFox for the LoPy4, and also cellular NB-IoT/LTE CATM1 for the FiPy. Unfortunately these devices are on end-of-life and are not sold anymore, if you can get your hands on one of these they are still a solid option for being able to explore a lot of different options in the prototyping phase.

The course is not based upon any particular language, but we will recommend MicroPython as it is making the development process faster and is better suited for people that haven't any experience in embedded programming. We have previous years chosen to work with Pycom's hardware, but as they are now changing their product line there is a need for checking other options as well. There is a possibility to flash MicroPython on mny other boards as well. 





* It's also recommended with a battery if you want to power your device away from the computer. The expansion board has a built in LiPo charger, but if you want to use non-rechargeable batteries buy a holder with a switch. **Important make sure the connector is JST-PA or JST-PH, 2 mm**

Wiki: [JST connectors](https://en.wikipedia.org/wiki/JST_connector)

  * [Batterihållare AAA](https://www.electrokit.com/produkt/batterihallare-3xaaa-med-strombrytare-och-jst-kontakt/)

  The expansion board has a built in LiPo-charger, so the best is to buy a LiPo-battery with JST-connection:
  * [LiPy battery JST](https://www.electrokit.com/produkt/batteri-lipo-3-7v-4400mah/)

We also recommend buying a **sensor-kit**, as the bundles above are just the bare basics:

* [Electrokit, sensor-kit 26 moduler](https://www.electrokit.com/produkt/sensor-kit-26-moduler/)

or from:

* [amazon.de](https://www.amazon.de/Elegoo-aufger%C3%BCsteter-Sensormodul-Bausatz-Anleitung/dp/B01M30ZWQR/ref=sr_1_5?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=sensor+kit+arduino&qid=1583957059&sr=8-5)
* [Kjell.com](https://www.kjell.com/se/produkter/el-verktyg/arduino/moduler/playknowlogy-stora-modul-paketet-for-arduino-p87291)

## Recommended hardware - MicroPython boards

### ESP32-based boards



### Heltec devices:




### Pycom devices:

- [LoPy4 (With headers)](https://pycom.io/product/lopy4/)
- [FiPy](https://pycom.io/product/fipy/) if you want to make use of LTE/NB-IoT*
* [Expansion board 3.0](https://pycom.io/product/expansion-board-3-0/)
* [LoRa/SigFox antenna](https://pycom.io/product/lora-868mhz-915mhz-sigfox-antenna-kit/)

* Micro USB cable (you probably already have some lying around). Make sure it's of high quality and can transfer data.

### You will also need sensors:

You can choose from a variety of sensors depending on what you want to develop in the course. If you are unsure, please pick just a start kit for Arduino (3.3V).

- Sensors of your choice. I recommend a starting kit from either [amazon.de](https://www.amazon.de/Elegoo-aufger%C3%BCsteter-Sensormodul-Bausatz-Anleitung/dp/B01M30ZWQR/ref=sr_1_5?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=sensor+kit+arduino&qid=1583957059&sr=8-5) for ~30 EUR, or from Swedish distributor [Kjell.com](https://www.kjell.com/se/produkter/el-verktyg/arduino/moduler/playknowlogy-stora-modul-paketet-for-arduino-p87291) or
[Electrokit](https://www.electrokit.com/produkt/sensor-kit-26-moduler/)

Wiring and breadboards:

- [Starting kit for Arduino Kjell.com](https://www.kjell.com/se/produkter/el-verktyg/arduino/arduino-kit/luxorparts-basic-start-kit-for-arduino-p90632) or [breadboard(s) from Amazon](https://www.amazon.de/Elegoo-Breadboard-Solderless-Distribution-Verbindungsbl%C3%B6cke/dp/B01MCRZFE5/ref=sr_1_3?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=3L86WOJGVV8CB&keywords=breadboard&qid=1583957299&sprefix=breadboard%2Caps%2C282&sr=8-3) and [Dupont cables](https://www.amazon.de/Female-Female-Male-Female-Male-Male-Steckbr%C3%BCcken-Drahtbr%C3%BCcken-bunt/dp/B01EV70C78/ref=sr_1_3?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=dupont+cable&qid=1584042669&sr=8-3).


# Pycom.io

You can buy these directly from Pycom.io, but it's recommended to buy from a Swedish distributor in first hand as the shipping might be both cheaper and faster.

* [LoPy4 (With headers)](https://pycom.io/product/lopy4/)
* [Expansion board 3.0](https://pycom.io/product/expansion-board-3-0/)
* [LoRa/SigFox antenna](https://pycom.io/product/lora-868mhz-915mhz-sigfox-antenna-kit/)

### Choice of LTE and NB-IoT

If you want cellular connection/LTE as well, the **FiPy4** is the way to go (in that case, replace **LoPy4 with FiPy**). It's a bit more expensive, but does the same thing as LoPy4 with added benefit of LTE/NB IoT as well.

- [FiPy](https://pycom.io/product/fipy/)
- [Expansion board 3.0](https://pycom.io/product/expansion-board-3-0/)
- [LTE antenna](https://pycom.io/product/lte-m-antenna-kit/),
- [LoRa/SigFox antenna](https://pycom.io/product/lora-868mhz-915mhz-sigfox-antenna-kit/),
