## The Board

The schematic is loosely based on [our panda jungle v2](https://www.comma.ai/shop/panda-jungle), a development and debugging board for comma devices and pandas. This version includes:

* 12V DC input with onboard 5V and 3.3V supplies
* Four [OBD-C](https://github.com/commaai/hardware/blob/master/harness/OBD-C.sch.pdf) device ports with individually controlled power and current monitoring
* Four CAN-FD transceivers and ignition simulation circuitry
* A USB hub and USB-C host connection
* A microcontroller and microSD card slot
* A push button and status LEDs

Explore in your browser with KiCanvas: [PCB layout](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fcommaai%2FPCBGolf%2Fblob%2Fmaster%2Fpcbgolf.kicad_pcb).

Schematics: [Power](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fcommaai%2FPCBGolf%2Fblob%2Fmaster%2Fpcbgolf.kicad_sch) · [Microcontroller](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fcommaai%2FPCBGolf%2Fblob%2Fmaster%2Fpcbgolf_2.kicad_sch) · [USB & microSD](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fcommaai%2FPCBGolf%2Fblob%2Fmaster%2Fpcbgolf_3.kicad_sch) · [CAN](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fcommaai%2FPCBGolf%2Fblob%2Fmaster%2Fpcbgolf_4.kicad_sch) · [OBD-C ports](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fcommaai%2FPCBGolf%2Fblob%2Fmaster%2Fpcbgolf_5.kicad_sch)

## The Challenge

The goal is to make the most compact, efficient PCBA that retains the same interfaces and functionality as the original design.

### Rules

* The bare PCB(s) must be fully manufacturable by JLCPCB.
* It must be possible to actually assemble the PCBA.
* The assembled product must work and be usable.
* Mating connectors must remain mechanically and electrically compatible.
* Optimizations that require firmware changes are allowed.
