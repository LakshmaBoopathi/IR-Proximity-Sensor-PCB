IR Proximity Sensor with Buzzer Alert

Overview

This project is an IR proximity sensor circuit designed using KiCad.
The circuit detects nearby objects using an IR transmitter and receiver pair and activates a buzzer alert.

**Components Used**

LM358 Op-Amp

BC547 Transistor

IR LED (LD271)

1N4148 Diode

Buzzer

Resistors

Potentiometer

LEDs

5V Power Supply

Software Used

KiCad 9.0

**Files Included**

Schematic (.kicad_sch)

PCB Layout (.kicad_pcb)

KiCad Project File (.kicad_pro)

**Footprint Assignments**

| Symbol | Component                    | Recommended Footprint                                           |
| ------ | ---------------------------- | --------------------------------------------------------------- |
| BZ1    | Buzzer                       | `Buzzer_Beeper:Buzzer_12x9.5RM7.6`                              |
| D1     | 1N4148 Diode                 | `Diode_THT:D_DO-35_SOD27_P7.62mm_Horizontal`                    |
| D2     | IR LED (LD271)               | `LED_THT:LED_D5.0mm`                                            |
| D3     | IR Receiver LED / Photodiode | `LED_THT:LED_D5.0mm`                                            |
| D4     | Normal LED Indicator         | `LED_THT:LED_D5.0mm`                                            |
| J1     | 2-Pin Power Connector        | `Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical`    |
| Q1     | BC547 Transistor             | `Package_TO_SOT_THT:TO-92_Inline`                               |
| R1     | Resistor                     | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` |
| R2     | Resistor                     | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` |
| R3     | Resistor                     | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` |
| R4     | Resistor                     | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` |
| R5     | Resistor                     | `Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` |
| RV1    | 10k Potentiometer            | `Potentiometer_THT:Potentiometer_Bourns_3296W_Vertical`         |
| U1     | LM358 IC                     | `Package_DIP:DIP-8_W7.62mm`                                     |
