# MiSTerFPGA_KA-Core

> [!CAUTION]
> These arcade cores were created for personal use on MiSTerFPGA.

> [!IMPORTANT]
> I love Taito Z.

- [NIGHT STRIKER](#night-striker)
- [CHASE H.Q.](#chase-hq)
- [Special Criminal Investigation / S.C.I.](#special-criminal-investigation--sci)

　　　\
　　　

# NIGHT STRIKER (1989)

<img src="docs\image\NS01.png" width="45%"> <img src="docs\image\NS02.png" width="45%">\
<img src="docs\image\NS03.png" width="45%"> <img src="docs\image\NS04.png" width="45%">

| Integrated Circuit | Processor | Internal Processing |
|-|-|-|
| Main&Sub CPU | 68000 x2 12MHz | FX68K (within FPGA) |
| Sound CPU | Z80 4MHz | TV80 (within FPGA) |
| Sound Chip | YM2610 8MHz | JT10 (within FPGA) |

- Roads, sprites, backgrounds, and screen layout are processed by RTL circuitry within the FPGA.
- No MAME source code or rendering logic is used.

## Feature

 - Supports DIP switches
 - Supports CRT output, with horizontal/vertical position adjustment
 - Supports gamma and contrast correction
 - Supports analog controllers
 - Supports CyberStick
 - Supports vertical-axis inversion for controls
 - Supports position-hold functionality for controls
 - Supports high-score saving

> [!NOTE]
> Recommended way to play\
> Setting the gamma to 0.80 and the contrast to 1.10 while playing on a CRT monitor recreates the experience of playing on an original arcade cabinet.\
> Be sure to try it out with a [CyberStick](https://www.micomsoft.co.jp/xe1aj-usb.html)!

　　　\
　　　

# CHASE H.Q. (1988)

<img src="docs\image\CHQ01.png" width="45%"> <img src="docs\image\CHQ02.png" width="45%">\
<img src="docs\image\CHQ03.png" width="45%"> <img src="docs\image\CHQ04.png" width="45%">

| Integrated Circuit | Processor | Internal Processing |
|-|-|-|
| Main&Sub CPU | 68000 x2 12MHz | FX68K (within FPGA) |
| Sound CPU | Z80 4MHz | TV80 (within FPGA) |
| Sound Chip | YM2610 8MHz | JT10 (within FPGA) |

- Roads, sprites, backgrounds, and screen layout are processed by RTL circuitry within the FPGA.
- No MAME source code or rendering logic is used.

## Feature

 - Supports DIP switches
 - Supports CRT output, with horizontal/vertical position adjustment
 - Supports gamma and contrast correction
 - Supports analog controllers
 - Supports CyberStick
 - Supports Some USB steering controllers
 - Supports high-score saving

## Support features

 - As a support feature, the current gear can be displayed on the screen.\
When this feature is enabled, it is processed in the same way as a HUD.\
This can be configured via the OSD (default is OFF=Manual).\
　　<img src="docs\image\CHQ002.png" width="10%">

 - As a support feature, Automatic gear shifting is available.\
When this feature is enabled, the system will automatically switch between LOW and HI gears based on your current speed.\
This can be configured via the OSD (default is OFF).\
　　<img src="docs\image\CHQ001.png" width="10%">

   
> [!NOTE]
> Recommended way to play\
> Setting the gamma to 0.80 and the contrast to 1.10 while playing on a CRT monitor recreates the experience of playing on an original arcade cabinet.\
> Be sure to try it out with a steering controllers!

　　　\
　　　

# Special Criminal Investigation / S.C.I. (1989)

<img src="docs\image\SCI01.png" width="45%"> <img src="docs\image\SCI02.png" width="45%">\
<img src="docs\image\SCI03.png" width="45%"> <img src="docs\image\SCI04.png" width="45%">

| Integrated Circuit | Processor | Internal Processing |
|-|-|-|
| Main&Sub CPU | 68000 x2 12MHz | FX68K (within FPGA) |
| Sound CPU | Z80 4MHz | TV80 (within FPGA) |
| Sound Chip | YM2610 8MHz | JT10 (within FPGA) |

- Roads, sprites, backgrounds, and screen layout are processed by RTL circuitry within the FPGA.
- No MAME source code or rendering logic is used.

## Feature

 - Supports DIP switches
 - Supports CRT output, with horizontal/vertical position adjustment
 - Supports gamma and contrast correction
 - Supports analog controllers
 - Supports CyberStick
 - Supports Some USB steering controllers
 - Supports high-score saving
 - Supports Negro Torino hack

## Support features

 - As a support feature, the current gear can be displayed on the screen.\
When this feature is enabled, it is processed in the same way as a HUD.\
This can be configured via the OSD (default is OFF=Manual).\
　　<img src="docs\image\SCI002.png" width="10%">

 - As a support feature, Automatic gear shifting is available.\
When this feature is enabled, the system will automatically switch between LOW and HI gears based on your current speed.\
This can be configured via the OSD (default is OFF).\
　　<img src="docs\image\SCI001.png" width="10%">

   
> [!NOTE]
> Recommended way to play\
> Setting the gamma to 0.80 and the contrast to 1.10 while playing on a CRT monitor recreates the experience of playing on an original arcade cabinet.\
> Be sure to try it out with a steering controllers!

