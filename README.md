![Header](Images/cmheader.png)
<br>



  <b>This repo will hold the flasher-tool to upload/flash a custom verion of <a href=hhttps://github.com/justcallmekoko/ESP32Marauder/wiki/about>Wifi Marauder</a> along with 3D files to print different cases for the CYD AKA Cheap Yellow Display. This build features a few great fixes and customzations.</b> 
  
  
  <br>
  <br>
  
<div align="center">
  
  ## ⬆ Update Highlights 04/26/24 — Marauder v0.13.10 ⬆

</div>

- **RGB LED enabled for builds w/o GPS thanks to [**lsdlsd88**](https://github.com/lsdlsd88)**

- **Detect Pwnagotchi [enabled](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display/blob/master/screenshots/pwn2.jpg) in the WiFi Sniffers submenu. (currently for builds without GPS. Fix hopefully soon)**
    
- **SwiftPair Spam now 100% functional** — Samsung, Google, and BLE spam crashing should now be nonexistent.

- **<a href=https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff>Evil Portal storage adjustment</a>** — Moves all portals into a folder instead of root of sd card.

- **For info on adding an external antenna, click [here](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display/blob/master/AntennaMod.md).**


<hr>

## Device Compatibility

Successfully tested on both of these devices:
- [CYD variant 1](https://amazon.com/dp/B0BVFXR313)
- [CYD variant 2](https://amazon.com/dp/B0CLR7MQ91)

No hardware modifications required thanks to integration with **@ggaljoen's** [TFT_eSPI](https://github.com/ggaljoen/TFT_eSPI) fork.

<hr>

## To install this fork of marauder
 - **Simple Install:** <b>You can choose to use the CM-Box flasher tool to flash the latest version of CM-Box (Custom Marauder box) to your CYD.
 Please consult the images below to verify which version of the CYD you have if you are unaware. These images are also on the flasher tool page.</b>
 
  - **Hands-On Install:** <b>Or you can choose to build from source (<a href=https://github.com/ATOMNFT/CYD-ESP32Marauder>CYD-ESP32Marauder</a>) for a more hands on experince. Both options result in the same installation the second option gives you the ability to modify the files further if your comfy with that.</b> 

 <br>
 
   ![ESP32-FLASHER](https://github.com/ATOMNFT/CM-Box/blob/main/Images/esp-flash-icn.png "Simple Install")  **Simple Install:** <a href=https://atomnft.github.io/CM-Box/flash0.html>CM-Box flasher tool</a> 
   <br>
   <br>
   <br>
   ![IDE-Build](https://github.com/ATOMNFT/CM-Box/blob/main/Images/ide-icn.png "Hands-On Install")  **Hands-On Install:** <a href=https://github.com/ATOMNFT/CYD-ESP32Marauder>CYD-ESP32Marauder</a>
  
 <hr>

## Parts List
1. CYD aka Cheap Yellow Display. (Can be found <a href=https://shorturl.at/GJKY4>HERE</a>)
2. 1 rocker switch (Can be found <a href=https://shorturl.at/oABL4>HERE</a>) 19mm x 13mm
3. 1 Voltmeter (Can be found <a href=https://shorturl.at/djHY5>HERE</a>)
4. 1 Lipo battery (Can be found <a href=https://rb.gy/8q9c45>HERE</a>)
5. x4 M3x20mm hex head screws. (Can be found <a href=https://rb.gy/lb1ewo>HERE</a>)

- **GPS Functionality**: 🛰 GPS is enabled and fully operational through the 4-pin connector located near the MicroUSB port of the CYD module. [Check here](https://github.com/justcallmekoko/ESP32Marauder/wiki/gps-modification) for details on supported GPS hardware.

<hr>
  
## Directions to build the CM-Box
 1. Download and print the stl files located in <a href=https://github.com/ATOMNFT/CM-Box/tree/main/STL%20Files>3D files</a> folder. All files are ready to print.
 2. Consult parts list above^
 3. Process coming soon. (Pics are being taken of a new build for ref.)
  
 <hr>
  
## Pics of build
  <b>Head over to the <a href=https://github.com/ATOMNFT/CM-Box/tree/main/STL%20Files>3D files</a> section to download the stl files need to print the CM-Box. The files are only for the 1 micro usb version at this time.</b>
  
  ![Front](Images/CMB1.jpg) ![Stand](Images/CMB2.jpg) ![Stand](Images/CMB3.jpg) ![Stand](Images/CMB4.jpg)
  <br>
  <hr>
  
## Shoutouts! 📢
  <b>A huge thank you goes to two wonderful people. Whom without I would have not made it as far as I  did learning.</b> <br>
  <b>Thanks to <a href=https://github.com/Fr4nkFletcher>Fr4nkFletcher</a> for all your guidance and late night replies.</b>
  <b>And thank you to <a href=https://github.com/smoochiee>smoochiee</a> for helping with the bootscreen and the badass tuts for building our own Marauder.</b><br>
  <b>A big thank you as well goes to the creators and supporters of the [ESP32 Cheap Yellow Display](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display) project and the community Discord, especially **@cod5fgzj**, [**ggaljoen**](https://github.com/ggaljoen). 
  <br> 
  And of course <a href=https://github.com/justcallmekoko>JustCallMeKoko</a>for the foundational work on ESP32 Marauder.</b>
  
  
  <br>
  <br>
  
  
  

 