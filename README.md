# SKR-Mini-E3-V1.2-512K-to-Play
SKR Mini E3 V1.2 firmware for Printrbot Play w/o heated Bed
This Firmware is used at your own risk.
This is for a Printrbot Play without heated Bed and has 3 point leveling for the induction probe. It has features set such as S_CURVE, LIN_ADV and ARC support.
It is set for the default size of 102mm X 102mm X 131
The SKR Mini5.stl is the one I finally used. It is a printable adapter plate from printrboard to SKR MINI. It orients the board 90degrees to the original board position. It lines the MicrSD on the board with the SD port in the Play chassis. This allowed me to use a Stock "CR10" LCD display where you need to use the onboard SD card to load files. The recommended TFT displays have USB and SD ports on them so this is not necessary to do for them. For the TFT displays you can use SKR Mini3.stl, but if you want to update firmware you will have to find a way to get to the MicroSD onboard to carry out that update. I recommend using the SKR Mini5.stl!

Board:
The Bigtreetech SKR Mini E3 Mini V1.2 board This board was designed as a direct replacement part for the Creality Ender 3 series of 3D Printers. It's size and layout match the Creality 1.1.4 and Creality 1.1.5 boards plus add extra connectors for TFT, NEOPixel, Filament runout sensor, BLTouch (servo connector), and extra fans
Specifications: Size: 100mm * 70.25mm
ARM Cortex-M3 CPU @ 75Mhz 256Kb documented available Flash (512 undocumented), 48K RAM.
Voltage: 12v or 24V operation depending on PSU, Hotend and Heated Bed unit used.
Drivers: Integrated TMC2209 drivers UART mode
Motor drive interfaces: X Axis, Y Axis, Z Axis, Extruder 0 (single extruder board)
Temperature Sensor interface: TH0, THB, 2 channel 100K NTC (thermal resistance)
Displays supported: 2.8"TFT, 3.5"TFT, Ender 3 original (CR10 display) LCD 12864 display
PC Communication interface: Mini USB type B @ 115200baud
File format: G-code
Recommended software: CURA, Simplify3D, Pronterface, Repetier-host, Makerware.

Connectors:
Connector type; JST-XH 2.54mm : Example: JST-XH connector set on Amazon
The Connectors on Printrbots are Molex(white) and Dupont(Black). To switch over to the SKR boards these have to be replaced or adapted to JST-XH connectors.
The Adaptrboard set adapts the Printrbot connectors to the SKR. They are a set of boards with incoming and outgoing terminals. The outgoing side plugs in from the Printrbot appropriate components plugs (X axis, Y axis, Z axis, Hotend etc.). The incoming side is to the SKR board you chose. The incoming side has short extensions (100mm about 4") between the SKR board and the Adaptrboards.
Manually replace the Molex and Dupont connectors with JST-XH connectors by cutting, stripping and crimping wires. 27 to 29 (1 fan, the hotend and the heated bed go into screw block and just need cutting and stripping) wires depending on whether you have a heated bed or not. Plus more if you have LEDS, NEOPixel, extra switches.
Another method would be to buy JST-XH 2.54mm Male wired cable connectors. Then cut, strip and solder and cover with shrink tube. This is probably as time consuming as crimping in the end. For some this is easier than crimping all those small pins to wires.
Of all these methods the cheapest is to crimp your own, the easiest is to buy the Adaptrboards and the most expensive is to solder them up. The Adaptrboards also have the advantage in they address the induction probe without having to wire in additional components. But if you are in a hurry and want to upgrade now, these are your options.
