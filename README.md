# Arduino IDE - macOS
Use Arduino IDE on your Mac avoiding  to see _/dev/cu.Bluetooth-Incoming-Port_ as unique choice:

1. Download and install driver
2. Plug-in your device(I used NodeMCU)
3. Check on terminal:

        `ls /dev/cu.*`
  
    the output should be _/dev/cu.wchusbserialfa130_

## Materials/Specifications
- macOS High Sierra 10.13.6
- NodeMCU 0.9 (ESP-12 Module)
- Arduino IDE 1.8.12
- CP210x USB to UART Bridge VCP Drivers (v5.2.4)

## References/File
https://pbxbook.com/other/mac-tty.html

https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

https://www.instructables.com/id/Get-Started-with-ESP8266-Using-AT-Commands-NodeMCU/
