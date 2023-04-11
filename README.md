# **Pic.0**
**Pic.0** - A macropad with OLED display

## Design
WIP

## Why did I want to build it?
I am not sure why. I thought it'd be a good learning curve and I could probably learn some stuff. Heh.

## Features
+ Open Source
+ Layers Support **(WIP)**
+ USB-C
+ Can be made into Hotswaps by changing the footprints in KiCAD
+ QMK / VIA support
+ Underglow
+ Last but not least, very small

## Parts
| Count        | Parts                                    | Description                                                                        |
| ------------ | ---------------------------------------- | ---------------------------------------------------------------------------------- |
| 1            | Pic.0 PCB                                |                                                                                    |
| 1            | Elite-C V4                               | The main microcontroller                                                           |
| 6            | MX style Low Profile Switches            |                                                                                    |
| 1            | Tactile push button (6mm x 6mm)          | For Reset                                                                          |
| 9            | WS2812B LEDs                             | Underglow                                                                          |
| 8            | 1N4148 Diodes (SMD Package 1206)         | For Ghosting reasons                                                               |
| 5            | 100nF Capacitors (SMD Package 1206)      | For "stuff"                                                                        |
| 1            | 330 Ohm Resistor (SMD Package 1206)      | Also for "stuff"                                                                   |
| 1            | 128x64 OLED Display                      | I used SSD1306 driver-ed display                                                   |
| 2            | EC11 Rotary Encoders                     | Shaft length as per taste                                                          |
| ??           | Acrylic Sheets                           | For base plate, and for display (Measurements? I dunno, didn't check)              |
| 4 for each   | 5mm M2 spacers, 12mm M2 screws, M2 nuts  | For holding the display to the PCB as the holes in the display are smaller than M3 |
| ??           | Some M3 standoffs, screws and nuts       | For base plate connection to PCB                                                   |

## Schematic
![Pic0](https://user-images.githubusercontent.com/22396923/230657075-0efdc150-4766-44db-8dbe-2f8cbfaad3df.png)
The schematic is available in the repository.

## QMK
Also WIP


