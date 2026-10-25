[README.md](https://github.com/user-attachments/files/33922701/README.md)
 Project Status: Under Active Development. This device currently has no firmware installed. It is an unprogrammed hardware shell that cannot communicate with your computer or music software out of the box yet.
 
A custom-designed, programmable mechanical keyboard featuring an ergonomic layout, onboard USB-C connectivity, and full-custom PCB architecture designed in KiCad.   📋 Table of ContentsOverviewFeaturesHardware Architecture & LayoutBill of Materials (BOM)Repository StructureBuilding & Assembly InstructionsFirmware SetupLicense🔍 OverviewThe [Project Name] is an open-source hardware project built from scratch to provide a reliable, sleek, and fully programmable input device. As visualized in the KiCad 3D viewer, the board integrates MX-style mechanical switches, surface-mount diodes, and a clean USB-C interface for modern compatibility.   Whether you are looking to streamline your daily workflow, optimize gaming macros, or dive into custom keyboard design, this repository contains everything you need to manufacture, assemble, and flash your own board.✨

FeaturesModern Connectivity: Reversible or standard Type-C USB port implementation for power and data transmission.   Mechanical Switch Support: Compatible with standard 3-pin and 5-pin MX-style mechanical switches.   Compact & Ergonomic: Optimized layout designed for minimal desk footprint and maximum efficiency.Open-Source Hardware: Fully editable KiCad schematic and PCB files allowing for easy customization and forks.Firmware Ready: Compatible with popular custom keyboard firmware ecosystems (e.g., QMK, VIA, or KMK).📐 Hardware Architecture & LayoutThe PCB design features:Microcontroller: [e.g., ATmega32U4 / RP2040 / STM32] handling USB communication and matrix scanning.Switch Matrix: Designed with individual switching diodes to prevent ghosting during multi-key rollover (NKRO).Low-Profile Integration: Compact component placement to maintain a low profile inside custom 3D-printed or CNC-machined cases.  



 <img width="557" height="574" alt="board" src="https://github.com/user-attachments/assets/edfaa78f-16ae-4569-9315-39a157f50e78" />

 <img width="1153" height="895" alt="Screenshot 2026-10-25 012502" src="https://github.com/user-attachments/assets/3397e90e-4b9e-4f80-84e6-53a2009186ce" />

