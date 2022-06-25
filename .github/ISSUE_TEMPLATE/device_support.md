---
name: Device support
about: Request support for a particular device
title: '[Device] '
labels: enhancement
assignees: ''

---

Please use the template and fill in all the data requested below!

**Device description**
Which device would you like to be supported in this plugin?

**Supported in Zigbee2MQTT?**
Is this device already supported by Zigbee2MQTT / zigbee-herdsman-converters?
If this is NOT the case, please add support for the device there first.
Read there manual on [How to support new devices](https://www.zigbee2mqtt.io/advanced/support-new-devices/01_support_new_devices.html) for more information.
If this is the case, please provide the version in which support is present/added.

**Device model / Exposes information**
Provide the device model (also known as [exposes information](https://www.zigbee2mqtt.io/guide/usage/exposes.html)) for this particular device, as published to `zigbee2mqtt/bridge/devices` by Zigbee2MQTT.

```json
please put the device model JSON in this code block
```

**Missing features/functionality**
Please describe the features/functionality of this device that are currently not exposed to HomeKit via this plugin.

**Suggested services and characteristics**
For each of the missing features, please mention to which HomeKit Services and Characteristics it should be mapped.
The [Homebridge Plugin Development documentation](https://developers.homebridge.io/) provides a nice overview of the standard HomeKit services and characteristics.
Note that some manufacturers also use custom services and characteristics (the Elgato Eve products for instance), which could also be mimicked if they have been reverse engineered.