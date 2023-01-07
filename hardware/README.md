# GD32F405RGT6 Automotive Wireless Dev Board

Simple development board featuring an ARM M4 based MCU
and a handful of wireless communication modules. It is
intended for use in Automotive prototyping and hacking.

## Partial BOM

This is not meant to emcompas every part on the board.
It just lists some of the more notable parts. For the full
BOM, check the [jlcpcb](/jlcpcb) folder.

|part #|Description|source|
|-|-|-|
|gd32f405rgt6 |application|C99031  |
|ATGM336H-5N31|gps        |C90770  |
|Ra-01S       |lora       |C724871 |
|ESP32-C3-MINI-1U-N4|bt   |C2911374|
|TLV61046ADBVT|step-up    |C139398 |
|TS3USB30ERSWR|usb sw     |C73880  |
|LM317AG-TN3-R|ldo        |C75510  |
|SIT1044TK/3  |CAN        |C2972660|

## Power Consumption

This is by no means a complete list of all power required,
it is just a reference for a educated guess, useful for
deciding a power supply.

|part #| typ|
|-|-|
|gd32f405rgt6       |100mA|
|ATGM336H-5N31      |100mA|
|Ra-01S             |140mA|
|ESP32-C3-MINI-1U-N4|300mA|
