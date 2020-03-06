# Arduino IDE - macOS
<p align="center">
  
<img src="https://user-images.githubusercontent.com/12975980/76038350-adb82800-5f49-11ea-874a-eb749f484662.png">


</p>


Use Arduino IDE on your Mac avoiding  to see _/dev/cu.Bluetooth-Incoming-Port_ as unique choice:
1. Download and install driver
2. Plug-in your device(I used NodeMCU)
3. Check on terminal: `ls /dev/cu.*` the output should be _/dev/cu.wchusbserialfa130_ or something like this

## Materials/Specifications
- macOS High Sierra 10.13.6
- NodeMCU 0.9 (ESP-12 Module)
- Arduino IDE 1.8.12
- CP210x USB to UART Bridge VCP Drivers (v5.2.4)

## References/File
https://pbxbook.com/other/mac-tty.html

https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

https://www.instructables.com/id/Get-Started-with-ESP8266-Using-AT-Commands-NodeMCU/
