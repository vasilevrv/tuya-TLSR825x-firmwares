For flash firmwares you can use:

1. https://github.com/pvvx/TlsrTools825x - Based on STM32
2. https://github.com/pvvx/TLSRPGM - Based on TB-04-KIT or TB-04 / 03F module
3. https://github.com/Suxsem/Telink-Zigbee-serial-flash-tool - Based on UART interface

At the moment we have the next firmwares:

- Single button (battery) - single_button.bin
- Motion sensor (battery) - motion_sensor.bin
- Dual-channel relay - dual_channel_relay.bin

These factory firmwares can be used as is, or the MAC address can be replaced. As desired. You can write the firmware either completely or only the necessary sectors.

Flash allocation described here:
https://github.com/Suxsem/Telink-Zigbee-serial-flash-tool/blob/main/docs/flash_allocation.PNG
