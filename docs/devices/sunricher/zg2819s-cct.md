---
title: "Sunricher ZG2819S-CCT Homebridge/HomeKit integration"
description: "Add HomeKit support to your Sunricher ZG2819S-CCT, using Homebridge, Zigbee2MQTT and homebridge-z2m."
---
<!---
This file has been GENERATED using src/docgen/docgen.ts
DO NOT EDIT THIS FILE MANUALLY!
-->
# Sunricher ZG2819S-CCT
> Zigbee handheld remote CCT 4 channels


# Services and characteristics
The following HomeKit Services and Characteristics are exposed by
the Sunricher ZG2819S-CCT

* [Battery](../../battery.md)
  * Battery Level
  * Charging State
  * Status Low Battery



## Exposes

```json
[
  {
    "type": "numeric",
    "name": "battery",
    "property": "battery",
    "access": 1,
    "unit": "%",
    "description": "Remaining battery in %",
    "value_min": 0,
    "value_max": 100
  },
  {
    "type": "enum",
    "name": "action",
    "property": "action",
    "access": 1,
    "values": [
      "color_move",
      "color_temperature_move",
      "hue_move",
      "brightness_step_up",
      "brightness_step_down",
      "recall_*",
      "on",
      "off",
      "toggle",
      "brightness_stop",
      "brightness_move_up",
      "brightness_move_down",
      "color_loop_set",
      "enhanced_move_to_hue_and_saturation",
      "hue_stop"
    ],
    "description": "Triggered action (e.g. a button click)"
  },
  {
    "type": "numeric",
    "name": "linkquality",
    "property": "linkquality",
    "access": 1,
    "unit": "lqi",
    "description": "Link quality (signal strength)",
    "value_min": 0,
    "value_max": 255
  }
]
```

# Related
* [Other devices from Sunricher](../index.md#sunricher)
* [Zigbee2MQTT documentation for this device](https://www.zigbee2mqtt.io/devices/ZG2819S-CCT.html)