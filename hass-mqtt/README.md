# hass-mqtt-stack

### mqtt-spy
* use java-8 'sudo archlinux-java set java-8-openjdk'
* subscribe to 'homeassistant/+/+/+'

### mqtt-discovery

* add to config:
```
mqtt:
  broker: localhost
  discovery: true
```
* https://www.home-assistant.io/docs/mqtt/discovery/