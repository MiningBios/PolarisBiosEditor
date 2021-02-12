# PolarisBiosEditor v1.7.5

**Polaris BIOS Editor — One of the most important programs for increasing the performance of your graphics card.**

## Benefits of Polaris BIOS Editor

- **Versatility** — Suitable for all types of memory.
- **Security** — Our site is official. All the latest updates and detailed instructions — only at polaris-bios-editor.com<br>
Never download programs from comments, forums or other third party resources.
- **Acceleration** — Significantly increases the performance of your graphics card.
- **Availability** — Polaris Bios Editor is completely free software, including all previous and future updates!

- **Updates** — The latest version at the moment is 1.7.2. All other versions on third-party resources are not official, version 1.7.3 does not exist! Be careful! Versions 1.6.4, 1.6.5, 1.6.6, 1.6.7 are considered deprecated and not optimized.

# How to Use Polaris BIOS Editor 1.7.2
- Download the latest version of the program
- Unpack the .zip archive to any place convenient for you
- Launch PBE — Press the Open Bios button (Upper left corner)

![1](https://polarisbioseditor.eu/wp-content/uploads/2020/12/6xiip53-6xe.jpg)

- Your firmware opens, where your timings are circled in red on the kart.

![1](https://polarisbioseditor.eu/wp-content/uploads/2020/12/polaris.jpg)

- After opening the firmware, click on the One click timing patch (red arrow).
- All timings were automatically edited. Now press Save as and the firmware will be saved.

![1](https://polarisbioseditor.eu/wp-content/uploads/2020/12/polaris1.jpg)

- You can change the voltage in the **gpu** and **memory graphs**, (Section for experienced users only!)
- **Target temperature** — this temperature, which the card will try to maintain, either by increasing the fan speed or lowering the frequencies, which is used less often, it all depends on the manufacturer.
- **Power control limit** — if you don’t want to use **Afterburner**, then this is the same **Power limit,** lower it in the same way.


### v1.7.5
- Added UberMix 3.3
- Few small changes in code
### v1.7.4
- Fixed bug no supported memory found (K4G80325FC)
- Old version bump in properties
### v1.7.3
- Added support for memory Samsung K4G80325FC
- Added new device AMD Radeon RX 580 2048SP - 6FDF
### v1.7.2
- Fixed apply timings for Hynix memory
- Added support for RX590
- Added support for New Hynix memory H5GC8H24AJ
- Added timing for New Hynix H5GC8H24AJ

### v1.7.1
- Updated Elpida Timing

### v1.7.0
- Added New timing for Hynix.
- Added Clock Stretch Amount.
- Added option for choosing timings on hynix Between Universal Hynix timing and Good hynix timing.
- Universal Hynix timing work on: H5GC8H24MJ, H5GQ8H24MJ, H5GQ4H24AJ.

### v1.6.9
- Fixed UI (updated design)
- Fixed and Updated all Timing's
- Added New strap for Micron and Hynix
- Added option for choosing timings on samsung between uber-mix 3.1 and 3.2, and on Micron between Good Micron timing and S Micron timing.
- Added Icon
- Added option for max. Mem. freq. (after one click timing patch button click automatically change max. mem. to 2300 MHz)

### v1.6.8
- Fixed Samsung Uber-Mix strap
- Added support for Hynix H5GQ4H24AJ
- Fixed fan mod option

### v1.6.7
- created solution and project files for ide
- support for device id 0x67ef
- better timings for micron memory
- firmware signature test / firmware signature in ascii
- editing of bios message (experimental)
- online check for new versions
- online display of developer notice

### v1.6.6
- support for rx550 device id 0x699F

### v1.6.5
- support up to 48 entrys in the timings table (more than 2 memory vendors)

### v1.6.4
- elpida timings fixed
- K4G41325FS memory support

### v1.6.3
- timing modification starts now at 1500 instead of 1750
- device id 67FF now also supported

### v1.6.2
- experimental: ubermix timings are now also applied to 4g SAMSUNG vram (K4G41325FC, K4G41325FE)
- timing modification starts now at 1750 instead of 2000

### v1.6.1
- hynix memory H5GC8H24MJ now recognized (same timings as H5GQ8H24MJ)

### v1.6
- window resizes properly now
- memory vendor detection
- one click timing patch (samsung, hynix, elpida, micron)

### v1.5
- added FanControlMode setting
- implemented some timing editor related code (not usable yet)

### v1.4.1
- replaced WPF components with Windows Forms to archive mono compatibility

