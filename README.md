A system is being developed to update a vehicle's firmware via Wi-Fi, utilizing a Raspberry Pi 4 to connect to the server, download, and decrypt firmware files. The system incorporates two STM32F103 microcontrollers, each linked to the CAN bus. The Raspberry Pi transmits the update package to the target ECU through the MCP2515, where a custom Bootloader then flashes the firmware into memory.
System Block Diagram:
-> System Block Diagram:
![Blank diagram] (https://github.com/jeremynguyenn/FOTA-Car-software-Update-system/blob/main/pic/259555974-d9d8b0aa-5a0d-4105-8775-40571a3df725.png)
System Flowchart:
Simplified Schematic Diagram:
