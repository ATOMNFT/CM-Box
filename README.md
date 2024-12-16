![Header](Images/cmheader.png)
<br>

<div align="center" style="padding: 20px 0;">
  <img src="https://github.com/ATOMNFT/CM-Box/blob/main/Images/Repolike.svg" style="padding: 20px;">
</div>
  
  ---

  <b>This repo will hold the flasher-tool to upload/flash a custom verion of <a href=hhttps://github.com/justcallmekoko/ESP32Marauder/wiki/about>Wifi Marauder</a> along with 3D files to print different cases for the CYD AKA Cheap Yellow Display. This build features a few great fixes and customzations.</b> 
  
  <br>
  <br>
  

  
  ## ⬆ Update Highlights 11/23/24 ⬆ <br> Added New v1.1.0!
  
  | Feature/Update                             | Description/Notes                                                                                                                                                        |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| • Added logging to SD for Flipper/AirTag sniff | Thanks to Fr4nkFletcher                                                                                                                                               |
| • Added Pcap capture of flipper data       | WIP as the pcap is malformed                                                                                                                                            |
| • Added Flipper Zero Sniff                 |                                                                                                                                                                        |
| • Airtag Sniffing/Spoofing                 |                                                                                                                                                                        |
| • Working Pwnagotchi Detect on all models  |                                                                                                                                                                        |
| • Flipper BLE Spam                         |                                                                                                                                                                        |
| • Wardriving Menu added                    |                                                                                                                                                                        |
| • RGB LED enabled                          | Thanks to lsdlsd88                                                                                                                                                    |
| • Detect Pwnagotchi 100% functional        |                                                                                                                                                                        |
| • BLE/SwiftPair Spam now 100% functional   |                                                                                                                                                                        |
| • Evil Portal storage adjustment           | Moves all portals into a folder instead of root of SD card                                                                                                            |
| • External antenna information             | [Click here](https://github.com/Fr4nkFletcher/ESP32-Marauder-Cheap-Yellow-Display/blob/master/AntennaMod.md) for info on adding an external antenna.                  |


<hr>

> ## 📡 **GPS Functionality** 📡
> 
> - **GPS is enabled** on builds `13.10` & `1.0.0` (not labeled as "NoGPS" in the flasher tool).  
>   It is fully operational via the 4-pin connector located near the MicroUSB port on the CYD module.  
> 
> - For build `1.1.0`, GPS is fully functional with **no conflicts** affecting LED or Pwnagotchi detection.  
> 
> 🔗 [Check here](https://github.com/justcallmekoko/ESP32Marauder/wiki/gps-modification) for details on supported GPS hardware.

<hr>

> ## 🛠️ **Device Compatibility**
> 
> Successfully tested on:
> - [CYD variant 1](https://amazon.com/dp/B0BVFXR313)  
> - [CYD variant 2](https://amazon.com/dp/B0CLR7MQ91)  
> 
> **✨ No hardware modifications required!**  
> This is made possible thanks to seamless integration with **[@ggaljoen](https://github.com/ggaljoen)'s** [TFT_eSPI](https://github.com/ggaljoen/TFT_eSPI) fork.

<hr>

## To install this fork of marauder
 - **Simple Install:** <b>You can choose to use the CM-Box flasher tool to flash the latest version of CM-Box (Custom Marauder box) to your CYD.

 - **Hands-On Install:** <b>Or you can choose to build from source (<a href=https://github.com/ATOMNFT/CYD-ESP32Marauder>CYD-ESP32Marauder</a>) for a more hands on experince. Both options result in the same installation the second option gives you the ability to modify the files further if your comfy with that.</b> 

   <br>
 
   <a href="https://atomnft.github.io/CM-Box/flash0.html"><img src="https://github.com/ATOMNFT/CM-Box/blob/main/Images/esp-flash-icn.png" />CM-Box flasher tool</a>
   <br>
   <br>
   <a href="https://github.com/ATOMNFT/CYD-ESP32Marauder"><img src="https://github.com/ATOMNFT/CM-Box/blob/main/Images/ide-icn.png" />Arduino Sketch Files</a>
  
<hr>

> ## 🛠️ **Parts List**  
> 
> 1. **CYD aka Cheap Yellow Display**  
>    *(Can be found [HERE](https://shorturl.at/GJKY4))*  
> 2. **1 Rocker Switch** (19mm x 13mm)  
>    *(Can be found [HERE](https://shorturl.at/oABL4))*  
> 3. **1 Voltmeter**  
>    *(Can be found [HERE](https://shorturl.at/djHY5))*  
> 4. **1 Lipo Battery**  
>    *(Can be found [HERE](https://rb.gy/8q9c45))*  
> 5. **x4 M3x20mm Hex Head Screws**  
>    *(Can be found [HERE](https://rb.gy/lb1ewo))*  
> 
> ---
> 
> ## 🧰 **Directions to Build the CM-Box**  
> 
> 1️⃣ Download and print the STL files located in the [3D files folder](https://github.com/ATOMNFT/CM-Box/tree/main/STL%20Files). All files are ready to print.  
> 2️⃣ Consult the **Parts List** above.  
> 3️⃣ **Build Process Coming Soon**  
>     *(Pics are being taken of a new build for reference.)*  
> 
> ---
> 
> ## 💾 **SD Setup for CM-Box**  
> 
> If you flashed from the [Custom Marauder Flasher Tool for CYD](https://atomnft.github.io/CM-Box/flash0.html)  
> or built from [CYD-ESP32Marauder](https://github.com/ATOMNFT/CYD-ESP32Marauder), you need to:  
> - Create a folder on the root of your SD card titled `portals`.  
> - Store the [Evil Portal HTML files](https://github.com/ATOMNFT/CYD-ESP32Marauder/tree/master/Evil%20Portal%20Stuff), including the `index.html` file, in this folder.  
> 
> ---
> 
> ## 📸 **Pics of Build**  
> 
> Head over to the [3D files section](https://github.com/ATOMNFT/CM-Box/tree/main/STL%20Files) to download the STL files needed to print the CM-Box.  
> *(The files are only for the 1 Micro USB version at this time.)*  
> 
> ![Front](Images/CMB1.jpg) ![Stand](Images/CMB2.jpg)  
> ![Stand](Images/CMB3.jpg) ![Stand](Images/CMB4.jpg)  
> 
> ---
> 

## 🎉 **Shoutouts!** 📢  
 
 A huge thank you goes to two wonderful people who made learning and building this possible:  
 
 - **[Fr4nkFletcher](https://github.com/Fr4nkFletcher)** for all your guidance and late-night replies.  
 - **[Smoochiee](https://github.com/smoochiee)** for helping with the bootscreen and the badass tutorials for building Marauder.  
 
 Special thanks to the creators and supporters of the [ESP32 Cheap Yellow Display](https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display) project and the community Discord, especially **@cod5fgzj** and [**ggaljoen**](https://github.com/ggaljoen).  
 
 And of course, **[JustCallMeKoko](https://github.com/justcallmekoko)** for the foundational work on ESP32 Marauder.  

  
<br>
<br>
  