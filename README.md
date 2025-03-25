A system is being developed to update a vehicle's firmware via Wi-Fi, utilizing a Raspberry Pi 4 to connect to the server, download, and decrypt firmware files. The system incorporates two STM32F103 microcontrollers, each linked to the CAN bus. The Raspberry Pi transmits the update package to the target ECU through the MCP2515, where a custom Bootloader then flashes the firmware into memory.
System Block Diagram:

 System Block Diagram:

![Blank diagram]()


 Project Design:
This section includes the main features of the project
1. System checks for new updates
2. Request update package
3. Download the update package
4. Installation
 System Flowchart:

![Grad Flow Chart]()

Simplified Schematic Diagram:

![Schematic Diagram]()
