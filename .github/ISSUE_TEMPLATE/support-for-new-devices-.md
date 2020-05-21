---
name: Support for new devices.
about: Support for new devices.
title: Support for [Name of Device]
labels: new device support
assignees: blmhemu

---

**Prechecks**
Is your device in the list of supported devices ?

**Provide**
* The full device name (E.x : Gigabyte Aero 15X V8)
* Output of `lsusb`

**Next Steps**
* Clone and make https://github.com/bentiss/hid-replay
* Run `sudo ./src/hid-recorder` in the repo.
* Select various hidraw interfaces and check if there is any output when you press Fn + ESC/F2/F5/F10/F11/F12
* Post the output for each key press in the above step. (There can be multiple outputs for each keypress)

**Additional context**
Add any other context or screenshots for the request here.
