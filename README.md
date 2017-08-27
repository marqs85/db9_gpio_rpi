db9_gpio_rpi
==============
db9_gpio_rpi is a driver (Linux kernel module) for DB9 joysticks and gamepads connected to Raspberry Pi's GPIO. See [wikipage](https://github.com/RetroPie/RetroPie-Setup/wiki/GPIO-Modules#db9_gpio_rpi) for further details.

Building dkms package on RPi
---------------------------------------------------
1. Install kernel headers
2. Copy db9_gpio_rpi-\<VERSION> folder to /usr/src/
3. dkms add db9_gpio_rpi/\<VERSION>
4. dkms build db9_gpio_rpi/\<VERSION>
5. dkms mkdeb db9_gpio_rpi/\<VERSION> --source-only
