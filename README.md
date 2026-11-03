# Current-sensing-circuit
4-layer MCU supply-current monitor: 1 Ω 0.1% shunt → INA821 in-amp → OPA365 driver → 16-bit 1 MSPS ADS8860 ADC with a REF6033 reference. 12 V input. OrCAD X 24.1 schematic and PCB, with JLCPCB-ready Gerbers and an LCSC BOM.

## PCB

| Top | Bottom |
|---|---|
| ![PCB top](images/pcb_top.png) | ![PCB bottom](images/pcb_bottom.png) |

59.35 × 58.42 mm, 4 layers. Rendered from the fab Gerbers; the bottom view is mirrored, as seen from below.

![All fab layers](images/pcb_layers.png)

## Schematic

**Signal chain:** shunt, INA821, OPA365 filter/driver and ADS8860 ADC
![Main schematic](images/schematic_main.png)

**ADC reference:** REF6033
![ADC reference schematic](images/schematic_adc_ref.png)

**Power and connectors:** 78L05, LP5907, TPS60403, headers and banana sockets
![Power and input schematic](images/schematic_power_input.png)
