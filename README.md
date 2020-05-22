# OpenAero
A collection of Linux drivers of various components for (Gigabyte) Aero devices.

## What's Done
### Keyboard
- [x] All normal keys (alphanumerics and special character) working beforehand.
- [x] Sleep, Mute, Volume Keys, Backlight [Fn + F1/F7/F8/F9/SPC] working even before this driver.
- [x] Brightness keys [Fn + F3/F4] working with this driver.
- [ ] Make Fn + ESC/F2/F5/F10/F11/F12 work.
- [ ] Make the C code into actual driver and ppa support.
- [ ] Look into the possibility of full keyboard RGB backlight support.
- [ ] Look into controlling fan profiles with [Fn + Esc] 
- [ ] Add into the main linux kernel ??

## Supported Devices
### Keyboard
| Device                                        |   VID:PID   |
| --------------------------------------------- | ----------- |
| Gigabyte Aero 15X V8                          |  1044:7A39  |
| Gigabyte Aero 15X V9                          |  1044:7A39  |


## Install Instructions
**Arch :** 
```
pacman -S linux-headers
pacman -S openaero-meta
```

## Notes
* I highly recommend using [light utility](https://github.com/haikarainen/light) for changing brightness. Link it to the BrightnessUp / BrightnessDown keyboard symbol if need be.

## Credits
**This project is heavily inspired (i.e copied 😄) from [OpenRazer](https://openrazer.github.io/).**

---
The project is licensed under the GPL and is not officially endorsed by [Gigabyte, Ltd](https://www.gigabyte.com//).
