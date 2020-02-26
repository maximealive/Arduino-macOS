# Arduino IDE - macOS
Use Arduino IDE on your Mac with avoiding  to see /dev/cu.Bluetooth-Incoming-Port as unique choice:

1. Download and install driver
2. Plug-in your device(I used NodeMCU)
3. Check on terminal `ls /dev/cu.*` -> the output should be '/dev/cu.wchusbserialfa130'

## Materials
- NodeMCU
- Arduino IDE 1.8.12
- CP210x USB to UART Bridge VCP Drivers (v5.2.4)

## References/File
https://pbxbook.com/other/mac-tty.html
https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers
https://www.instructables.com/id/Get-Started-with-ESP8266-Using-AT-Commands-NodeMCU/
