# Arduino IDE - macOS
<p align="center">
  <img src="https://user-images.githubusercontent.com/12975980/76165393-0f011680-6157-11ea-81f0-59a0505bde30.png">
</p>


Use Arduino IDE on your Mac avoiding  to see _"/dev/cu.Bluetooth-Incoming-Port"_ as unique choice:
1. Download and install driver
2. Plug-in your device
3. Check on terminal: `ls /dev/cu.*` the output should be _"/dev/cu.wchusbserialfa130"_ or something like this

## Materials/Specifications
- macOS High Sierra 10.13.6
- NodeMCU 0.9 (ESP-12 Module)
- Arduino IDE 1.8.12
- CP210x USB to UART Bridge VCP Drivers (v5.2.4)

## References/File
https://pbxbook.com/other/mac-tty.html

https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

https://www.instructables.com/id/Get-Started-with-ESP8266-Using-AT-Commands-NodeMCU/
