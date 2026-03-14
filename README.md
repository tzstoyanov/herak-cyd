# herak-cyd

## Overview
ESPHome applications controlling mini LCD displays, used in my house.
Integrated with Home Assistance, running on the same network.
Tested with:
- [JC3248W535C_I_Y](http://pan.jczn1688.com/s/2r809e)

## Prerequisites
### Get the code
The project uses sub-modules, so clone the repo with all sub-modules:
```
git clone --recurse-submodules  https://github.com/tzstoyanov/herak-cyd.git
```
### Install 
- [ESPHome](https://esphome.io/guides/installing_esphome/)
- [ESPHome integration](https://www.home-assistant.io/integrations/esphome/) on your Home Assistant instance
### Customize the code
- Add your secrets to [secrets.yaml](secrets.yaml)
- Create yaml file describing the logic of your screen. Look at [gogo-h2-cyd.yaml](gogo-h2-cyd.yaml) for an example.
### Compile and copy to device
[Connect](https://esphome.io/guides/physical_device_connection) the LCD device and run `esphome run <your_custom>.yaml` to compile and upload the image.

## Credits
- [esphome-lvgl](https://github.com/RyanEwen/esphome-lvgl)
- [esphome-modular-lvgl-buttons](https://github.com/agillis/esphome-modular-lvgl-buttons)

## License
herak-cyd is available under the [GPLv2.0 or later license](LICENSE).
