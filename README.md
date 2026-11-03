# Current-sensing-circuit
4-layer MCU supply-current monitor: 1 Ω 0.1% shunt → INA821 in-amp → OPA365 driver → 16-bit 1 MSPS ADS8860 ADC with a REF6033 reference. 12 V input. OrCAD X 24.1 schematic and PCB, with JLCPCB-ready Gerbers and an LCSC BOM.

## PCB

| 3D top | 3D bottom |
|---|---|
| ![PCB 3D top](images/pcb_3d_top.png) | ![PCB 3D bottom](images/pcb_3d_bottom.png) |

59.35 × 58.42 mm, 4 layers, 1.6 mm.

| L1 Top | L2 GND plane |
|---|---|
| ![Layer 1 top](images/pcb_layer1_top.png) | ![Layer 2 GND plane](images/pcb_layer2_gnd_plane.png) |

| L3 Power (12V, 5V, 3V3, −3V3) | L4 Bottom (GND) |
|---|---|
| ![Layer 3 power](images/pcb_layer3_power.png) | ![Layer 4 bottom](images/pcb_layer4_bottom.png) |

## Schematic

**Signal chain:** shunt, INA821, OPA365 filter/driver and ADS8860 ADC
![Signal chain schematic](images/schematic_1_signal_chain.png)

**ADC reference:** REF6033
![ADC reference schematic](images/schematic_2_adc_reference.png)

**Power and connectors:** 78L05, LP5907, TPS60403, headers and banana sockets
![Power and input schematic](images/schematic_3_power_input.png)
