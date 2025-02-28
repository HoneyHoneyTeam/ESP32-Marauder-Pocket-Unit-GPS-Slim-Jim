# ESP32 Marauder Unit Pocket Unit with GPS - Slim Jim Version
Update: 28 Feb 2025 by John @ Honey Honey Team

![Alt text](Assets/images/SlimJimseries.jpg)
![Alt text](Assets/images/SlimJim-Coral4.jpg)
![Alt text](Assets/images/SlimJim-Coral3.jpg)
![Alt text](Assets/images/SlimJim-Coral2.jpg)
![Alt text](Assets/images/Alright.3d.case.2.jpg)
![Alt text](Assets/images/Alright.3dcase.1.jpg)
![Alt text](Assets/images/Alright.3dcase-6.jpg)

<br/>


## What is ESP32 Marauder Pocket Unit with GPS – Slim Jim Version ? 

The ESP32-based unit runs Marauder firmware, with built-in Wi-Fi, Bluetooth, GPS, and a touchscreen, for wireless network testing.  

## What is difference between The Slim Jim version and the V2 version?

The main purpose of creating Slim Jim is keep the 2.8inch touch screen also reduce the size of the unit. In order to do that, 800mah battery has been used internally. More info please check the comparision table in the listing photos.  

<br/>

## Specification of the ESP32 Marauder Slim Jim

• It support latest Marauder firmware (1.2.1 currently), ESP32 WiFi and Bluetooth capabilities. 
• 2.8 inch touchscreen. 
• Adding a GPS module while maintaining the compact size of the unit. 
• Dual antenna SMA connectors for WIFI and GPS 
• Dual 18650 batteries and USB C charging for long operational life. 
• Micro SD card slot for file sharing, backup, and firmware updates.  
• 6 GPIO interface for bricking device recovery 
• Premium 3D printed full enclosure (Optional).  
• Package content: 1 * unit, 2 * antenna, 1 * Micro SD card, 1 * USB-C cable and optional 3d enclosure.  


<br/>

## What is the difference between our boards for Flipper Zero. 

<br/>

![Alt text](https://github.com/HoneyHoneyTeam/3in1-WiFi-MultiBoard/blob/main/Assets/images/3boardsInComparison.png)

<br/>

  
## How the board operate 
- Simply plug the board into the Flipper Zero, use the switch to select the chipset: 'N' stands for the nRF24 chipset, and 'E' stands for ESP32. Then, choose one of the corresponding apps on the Flipper, and you're good to go.
- The nRF24 and CC1101 chipsets do not require additional firmware to function. Most Flipper Zero firmware, including Momentum, Unleashed, and others, support them natively.
- The ESP32 requires Marauder firmware to function, and it comes pre-loaded with the firmware on the ESP32 chipset.

<br/>

## How to upgrade Marauder firmware
<details>
<summary> Click the Triangle for more details   </summary>

<br/>

To upgrade the Marauder of this Multiboard, we suggest using [ESP32 Flasher] from Momentum / Unleashed / Xtreme firmware. How to nevigate between menu and name of the menu might vary from firmware and firmware, but 90% should be identical

1. The testing environment is Xtreme Firmware 0053 Version.

2. While holding the < Boot1 / B > button on the board, click the < EN1 / E> button, then release the < Boot1 / B> button, then release the < EN1 / E> button. The board should be in bootloader mode now
   
3. Navigating Flipper Zero menu as following: < Apps > => < GPIO > => < [ESP] ESP Flasher > => < Quick Flash > => < Other ESP32-S2 > = < Marauder >
   
4. Flipper should start flashing the board with Marauder firmware from this point.

5. The screen should instruct you to reset the board if it did not auto-reset. Once reset, the process is complete.

FYI. 

- If this is your first time to try this function, it might take a few times to get it right, I would do the “press and release” action first before launching the ESP32 Flasher. 
- If you would like to flash a particular version of the Marauder, the Marauder bin file need to drop into the ESP32 folder of the Flipper Zero micro SD card
- There are multiple ways to upgrade Marauder, but in our opinion, this method is the least complicated as of writing this manual.

</details>

<br/>

## Our official shop if you would like to support us.  
1. [Our official site](https://honeyhoneylab.com/)
2. [Tindie](https://www.tindie.com/stores/honeyhoneytrading/)
3. [eBay](https://www.ebay.com.au/itm/197059205271)
4. ~~[ETSY Shop](https://www.etsy.com/au/shop/HoneyHoneyTrading)~~

<br/>

## Warrenty and Tech Support

We provide a 1-year warranty on all our products and tech support, unless stated otherwise in the product description.

FYI, our [Etsy](https://www.etsy.com/au/shop/HoneyHoneyTrading) shop is no longer in operation. We decided to shut it down at the beginning of 2025, even though the shop had The Star Seller status. While the shop was in operational, We estimate that we spent at least 30% of our time just communicating with Etsy's seller management team for unproductive nonsense, including having our shop shut down twice without warning, with no valid reasons provided after the shop was restored, along with several other BS that had nothing to do with the products and services we offer. 

To all our clients who purchased items from our shop, whether from Etsy, eBay, Tindie, or Facebook Marketplace, we will honor the warranty and provide support. Please feel free to email us at Support@honeyhoneylab.com. or [Whatsapp](https://wa.me/61452559581) 

<br/>

## Credibility
- Credit of the [web flasher](https://esp.huhn.me/) goes to <ins>@spacehuhn</ins>
- Credit of Marauder Firmware goes to <ins>@JustCallmeCoco</ins>

<br/>

## FAQ 

**How do we test the board functionality pre-shipment?**

<details>
<summary> Click the Triangle for more details   </summary>

<br/>

**For Marauder / ESP32: **
- Turn the switch onboard to the right side (ESP32 / E).
- Open an Flipper App Call < [ESP32] Marauder > => < Scan = > AP >. Flipper should start showing the different WIFI AP info in your surroundings.
- Sometimes the APP might freeze at < press back to send stopscan > momentarily. I usually wait for a few seconds or re-launch the app altogether. 


**For NRF24**
- Turn the switch on board to left side (NRF24 / N)
- Open an Flipper App Call < [NRF24]Sniffer > , then click the middle bottom / enter bottom of Flipper Zero, the onscreen info of Sniffing should turn < No > to < Yes >. Also Address should start changing at this point, if there is working wireless mouses / keyboards nearby. 

</details>

<br/>

### Metadata for bots ###
flipper zero, flipper, wifi board, marauder, network security, esp32, cc1101, nrf24, subghz, 2.4ghz, wifi, 
