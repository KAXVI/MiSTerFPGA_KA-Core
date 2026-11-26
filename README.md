# MiSTerFPGA_KA-Core

## NIGHT STRIKER

<img src="docs\image/NS01.png" width="45%"> <img src="docs\image/NS02.png" width="45%">\
<img src="docs\image/NS03.png" width="45%"> <img src="docs\image/NS04.png" width="45%">

### Feature

・Supports DIP switches\
・Supports CRT output, with horizontal/vertical position adjustment\
・Supports gamma and contrast correction\
・Supports analog controllers\
・Supports CyberStick\
・Supports vertical-axis inversion for controls\
・Supports position-hold functionality for controls\
・Supports high-score saving

### Core Internal Processing

| Process | Implementation |
|-|-|
| 68000 CPU ×2 | FX68K (within FPGA) |
| Z80 CPU | TV80 (within FPGA) |
| YM2610 Sound Generator | JT10 (within FPGA) |
| Road, sprites, background, and screen composition | RTL circuitry (within FPGA) |
| MAME C++ rendering logic | Used solely for comparative verification on a PC; not included in the RBF file |

### Recommended way to play

Setting the gamma to 0.80 and the contrast to 1.10 while playing on a CRT monitor recreates the experience of playing on an original arcade cabinet.

Be sure to try it out with a [CyberStick](https://www.micomsoft.co.jp/xe1aj-usb.html)!

