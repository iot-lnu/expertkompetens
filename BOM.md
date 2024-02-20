
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

## Recommended hardware - MicroPython boards

### ESP32-based boards

### Heltec devices.

We have succesfully used the Heltec in previous courses. They are good as they provide a cheap way of combining both LoRa, WiFi and an ESP32. Remember to buy a 868MHz version (for the EU market).

[Heltec WiFi LoRa 32](https://heltec.org/project/wifi-lora-32-v3/)

Can be found on [Amazon](https://www.amazon.se/Diymore-dubbelk%C3%A4rnig-Bluetooth-utvecklingskort-863MHZ-928MHz/dp/B0BJF6G67Z/ref=sr_1_2?crid=124M5YJK6B22A&dib=eyJ2IjoiMSJ9.wBzd0hr5_DICGTGSjjBHUMnH2pthOcgJYdoNr1gDojF80915Pd3OIVO6OUqQvcfhkXNrD3pQMbhtvJaKlFsoFJ28Zq-xdIktL3PGxLec-72xJSnOQLXbG-ixLE1wqsAEm6zRcA9ZU-uF3UkeqL6yYraPqfCj3RqG61EuP0AkCJSyDNzuScU0CuMK9IXKn979MuZVwufE0Zw5C0ZBwie6U0_I1Jf6XcOWS5dnd97FdKklJDE5RbOg9GBG_fVDKgdTzmIn21YdmJpGcGqSQ3yzz-47lQkNrNd_XagokeCGAsU.E4NrX8IzsAh1BI7OO5YBnd4vg1OhHWkF09ma2gkEkt4&dib_tag=se&keywords=heltec+lora+v3&qid=1708424591&sprefix=heltec%2Blora%2Caps%2C91&sr=8-2) if you just search for it.


You can also buy any ESP32 device, and then just add a LoRaWAN module.

https://www.electrokit.com/?s=esp32&post_type=product&lang=sv

### Raspberry Pico Wireless

The RPi Pico WH (Wireless with Headers) is a great little device. Everyone should have one.

You will find it for a small sum at [Electrokit](https://www.electrokit.com/produkt/raspberry-pi-pico-wh/). Just remember to buy the Wireless version (W) and add Headers if you don't want to solder them yourself. 


### Adding LoRaWAN

We have succesfully used the [M5 Stack LoRaWAN module](https://shop.m5stack.com/products/lorawan-unit-868mhz-asr6501-with-antenna?variant=39729095442604) which also can be found on [elfa.se](https://www.elfa.se/en/asr6501-868mhz-lorawan-communications-unit-with-antenna-m5stack-u117/p/30221929?ext_cid=shgooaqsesv-Shopping-PerformanceMax-CSS&cq_src=google_ads&cq_cmp=20378176311&cq_con=&cq_term=&cq_med=pla&cq_plac=&cq_net=x&cq_pos=&cq_plt=gp&gad_source=1&gclid=CjwKCAiAibeuBhAAEiwAiXBoJEq6xuFNk34LZ-2i71u0MnRe2rdGEu2BOokFcg4HnlMjPn_-zIs99hoC6WcQAvD_BwE&gclsrc=aw.ds) 


## Adding extras .... 

* [Batterihållare AAA](https://www.electrokit.com/produkt/batterihallare-3xaaa-med-strombrytare-och-jst-kontakt/)

We also recommend buying a **sensor-kit**, as the bundles above are just the bare basics:

* [Electrokit, sensor-kit 26 moduler](https://www.electrokit.com/produkt/sensor-kit-26-moduler/)

or from:

* [amazon.de](https://www.amazon.de/Elegoo-aufger%C3%BCsteter-Sensormodul-Bausatz-Anleitung/dp/B01M30ZWQR/ref=sr_1_5?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=sensor+kit+arduino&qid=1583957059&sr=8-5)
* [Kjell.com](https://www.kjell.com/se/produkter/el-verktyg/arduino/moduler/playknowlogy-stora-modul-paketet-for-arduino-p87291)
