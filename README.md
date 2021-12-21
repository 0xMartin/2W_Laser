# 2 W Laser controler
Controller for 2 W laser diode M140. The PCB offers basic control options (on / off, setting the current flowing into the laser diode). Trimmer R4 is used to set the maximum output and R3 to regulate the current flowing into the diode. Transistor Q1 and laser diode must have a smoother !!

## Connection diagram:
<div class="d-flex justify-content-center">
  <img src="./doc/circ.PNG" width="80%">
</div>

## Parts:
| RefDes  | Description   | Family        | Package                   |
|---------|---------------|---------------|---------------------------|
| D1      | 1N4007        | DIODE         | DO-35                     |
| R4      | 6k8kΩ         | POTENTIOMETER | 33292W-1-502LF            |
| LED1    | LED_blue      | LED           | LED9R2_5Vb                |
| Q1      | IPP200N15N3 G | POWER_MOS_N   | TO-220-3(PG-TO-220-3)     |
| R3      | 4k7Ω          | RESISTOR      | 16PMI-4K7 SR PASSIVES     |
| R2      | 4k7Ω          | RESISTOR      | RES1300-700X250           |
| C1      | 220nF         | CAPACITOR     | CAPPR250-630X1120         |
| R1      | 1kΩ           | RESISTOR      | RES1300-700X250           |
| R6      | 1kΩ           | RESISTOR      | RES1300-700X250           |
| R5_3W   | 1Ω            | RESISTOR      | RES1500-900X250           |
| Switch1 | Switch        | SWITCH        | 1101M2S3CBE2              |
| U1      | LM358AN       | OPAMP         | MDIP-8(N08E)              |
| Power   | HDR1X2        | CONNECTOR     | 1776275-2 TE CONNECTIVITY |
| Laser   | HDR1X2        | CONNECTOR     | 1776275-2 TE CONNECTIVITY |
| C4      | 4m7F          | CAPACITOR     | CAPPR500-1000X1250        |

## PCB:
> Size: 63.5mm x 26.92mm
<div class="d-flex justify-content-center">
  <img src="./doc/top.png" width="40%">
  <img src="./doc/bottom.png" width="40%">
</div>

## Final:
work in progress ...

## Graphs:
work in progress ...

## Test:
work in progress ...
