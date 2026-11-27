# MiSTerFPGA_KA-Core

These arcade cores were created for personal use on MiSTerFPGA.

- NIGHT STRIKER
- CHASE H.Q.

## NIGHT STRIKER

<img src="docs\image/NS01.png" width="45%"> <img src="docs\image/NS02.png" width="45%">\
<img src="docs\image/NS03.png" width="45%"> <img src="docs\image/NS04.png" width="45%">

### Feature

 - Supports DIP switches
 - Supports CRT output, with horizontal/vertical position adjustment
 - Supports gamma and contrast correction
 - Supports analog controllers
 - Supports CyberStick
 - Supports vertical-axis inversion for controls
 - Supports position-hold functionality for controls
 - Supports high-score saving

I have recreated the TC0150ROD chip using RTL circuitry. This resolves rendering issues previously encountered in MAME, providing an experience that more closely mirrors the original arcade hardware.

### Core Internal Processing

| Process | Implementation |
|-|-|
| 68000 CPU ×2 | FX68K (within FPGA) |
| Z80 CPU | TV80 (within FPGA) |
| YM2610 Sound Generator | JT10 (within FPGA) |
| Road, sprites, background, and screen composition | RTL circuitry (within FPGA) |
| MAME C++ rendering logic | Used solely for comparative verification on a PC during the production process; Not included in the RBF file |

### Recommended way to play

Setting the gamma to 0.80 and the contrast to 1.10 while playing on a CRT monitor recreates the experience of playing on an original arcade cabinet.

Be sure to try it out with a [CyberStick](https://www.micomsoft.co.jp/xe1aj-usb.html)!


## CHASE H.Q.

<img src="docs\image/CHQ01.png" width="45%"> <img src="docs\image/CHQ02.png" width="45%">\
<img src="docs\image/CHQ03.png" width="45%"> <img src="docs\image/CHQ04.png" width="45%">

### Feature

 - Supports DIP switches
 - Supports CRT output, with horizontal/vertical position adjustment
 - Supports gamma and contrast correction
 - Supports analog controllers
 - Supports CyberStick
 - Supports Some USB steering controllers
 - Supports high-score saving

### Support features

 - As a support feature, the current gear can be displayed on the screen.\
When this feature is enabled, it is processed in the same way as a HUD.\
　　　　<img src="docs\image/CHQ002.png" width="10%">

 - As a support feature, Automatic gear shifting is available.\
When this feature is enabled, the system will automatically switch between LOW and HI gears based on your current speed.\
　　　　<img src="docs\image/CHQ001.png" width="10%">

### Core Internal Processing

| Process | Implementation |
|-|-|
| 68000 CPU ×2 | FX68K (within FPGA) |
| Z80 CPU | TV80 (within FPGA) |
| YM2610 Sound Generator | JT10 (within FPGA) |
| Road, sprites, background, and screen composition | RTL circuitry (within FPGA) |
| MAME C++ rendering logic | Not in use |

### Recommended way to play

Setting the gamma to 0.80 and the contrast to 1.10 while playing on a CRT monitor recreates the experience of playing on an original arcade cabinet.

Be sure to try it out with a steering controllers!

