# StadiaFW
Another Google Stadia Bluetooth and Wi-Fi firmware dump.

Google made a positive move during Stadia's unfortunate shutdown by releasing a low-energy Bluetooth firmware update for its controllers. <br>
However, there's a catch: the firmware update tool will be discontinued after December 31, 2023.

It's crucial to preserve these firmware files for future use. <br>
This repository includes the Bluetooth (`bruce`) and flash loader (`flashloader`) binary files. <br>
During my exploration, I was unable to secure the Wi-Fi (`gotham`) DVT and Prod binaries. <br>
Nonetheless, I have located OTA links for the `gotham` binaries.

### Source of Files
- Most bins (except `gotham`) were sourced from:  
  https://stadia.google.com/controller/app_combined.js

- `Gotham` OTA bins were obtained from the following URLs:
  - [Gotham Bin A](https://edgedl.me.gvt1.com/edgedl/googletv-eureka/stable-channel/ota.282115.stable-channel.gotham-pvt-a.214f6fe20f7b993046c77a9245c5805b056882dc.bin)
  - [Gotham Bin B](http://edgedl.me.gvt1.com/edgedl/googletv-eureka/stable-channel/ota.316382.stable-channel.gotham-pvt-b.da986392604309ea67eab5fa84f747e955f2875c.bin)  

#### HID Descriptors: [**@DJm00n/ControllersInfo**](https://github.com/DJm00n/ControllersInfo/tree/master/stadiacontroller)