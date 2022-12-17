This is a repo with ideas etc related to the WLED project:

https://github.com/Aircoookie/WLED

This is project I ran across lately with an Adafruit project that shows installing WLED on a QTPi: https://learn.adafruit.com/neopixel-remote-ir-control-with-wled/overview

I was able to get this working with a little effort.  The two biggest hurdles were the wire colors not matching the small photos.  And the description of what WLED settings to use were in text.  It would have helped to see screen shots.

I was also hesitent because I wanted to understand the bigger concepts of WLED before I blindly started installing software.

I did need to install new driver, then connected to "wserial*" instead of "serail*".  That should make sense when you see it.

Then used this page to install the release version: https://install.wled.me/

## My HW
- WS2812 5V 150 count - https://www.amazon.com/gp/product/B07BH37JGC/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1
- Adafruit QT Py ESP32 Pico - WiFi Dev Board with STEMMA QT - https://www.adafruit.com/product/5395
- Adafruit NeoPixel Driver BFF Add-On for QT Py and Xiao - https://www.adafruit.com/product/5645
- IR (Infrared) Receiver Sensor - https://www.adafruit.com/product/157
- (found) 24 key RGB like - https://www.amazon.com/QIACHIP-Controller-24-Key-Wireless-Control/dp/B07TVBWLSV/ref=sr_1_17?crid=1Q5Q1DK5TRXXS&keywords=controller+with+24+key+remote+for+12v+rgb+led+strip+light&qid=1671291413&s=hi&sprefix=24+key+rgb+LED%2Ctools%2C170&sr=1-17



## WLED Concepts

TBD

## Rough Ideas and Questions

- 192.168.1.6

- [ ] how to get back to Access Point only?
- [ ] config test, cyle pins?
- [ ] any use for zephyros or freertos, temp issue
- [ ] what was thought with wsm branch?  effects? (fx?)
- [ ] add css
- [ ] add my wrap concept
    - [ ] pole
    - [ ] box
    - [ ] board
    - [ ] calc for scoreboard
    - [ ] calc for billboard/words/ scrolling
- [ ] site as a pwa?
    - [ ] any thing special about wled- [ ]app
        - [ ] how communicate
        - [ ] how it works
        - [ ] try on android






## REFERENCES

- https://learn.adafruit.com/neopixel-remote-ir-control-with-wled/overview
- https://github.com/Aircoookie/WLED
- Adafruit QT Py ESP32 Pico: Pinouts - https://learn.adafruit.com/assets/112309
- Driver for Mac - https://learn.adafruit.com/how-to-install-drivers-for-wch-usb-to-serial-chips-ch9102f-ch9102/mac-driver-installation
- https://install.wled.me/
- https://kno.wled.ge/
- https://kno.wled.ge/advanced/compiling-wled/
- https://components101.com/diodes/tsop38238-ir-receiver
- https://docs.platformio.org/en/latest/integration/ide/vscode.html


