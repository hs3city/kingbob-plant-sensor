# Kingbob Plant Sensor

[![License](https://img.shields.io/github/license/bruvv/LILYGO-T-Higrow-Esphome.svg)](https://github.com/bruvv/LILYGO-T-Higrow-Esphome/blob/main/LICENSE)

This [ESPHome](https://esphome.io/) configuration builds firmware for the King Bob plant sensor, who resides in [Hackerspace Trójmiasto](https://hs3.pl/). 

The project utilizes [LILYGO T-Higrow plantsensor](https://pl.aliexpress.com/item/32815782900.html?aff_fcid=37217c4588514cc7ad872a7dadd15e93-1689186417587-07350-_DefUZbV&tt=CPS_NORMAL&aff_fsk=_DefUZbV&aff_platform=shareComponent-detail&sk=_DefUZbV&aff_trace_key=37217c4588514cc7ad872a7dadd15e93-1689186417587-07350-_DefUZbV&terminal_id=7e431fd0a2f343a0a4f14da3e9ffb533&afSmartRedirect=y). Firmware is based on [LILYGO-T-Higrow-Esphome](https://github.com/bruvv/LILYGO-T-Higrow-Esphome/tree/main).

It is still work in progress. 🌿

## Adding the sensor to Home Assistant
Sensor can be added to HS3's Home Assistant within the ESPHome in Home Assistant dashboard. The .yaml configuration file should point to the project template within this repository:
```yaml
packages:
  esphome.project-template: github://hs3city/kingbob-plant-sensor/LILYGO-T-Higrow-ESP32.yaml@main
```
## Calibration
Calibration process is described in the official [LILYGO-T-Higrow-Esphome website](https://bruvv.github.io/LILYGO-T-Higrow-Esphome/).
