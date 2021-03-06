
<p align="center">
  <img src="https://github.com/home-assistant/home-assistant-assets/blob/master/loading-screen.gif">
</p>

These are the [Home Assistant](https://home-assistant.io/) configuration files used in my Home Assistant (HA) setup. I relied on repositories of other HA users quite a bit when I was getting started for ideas and example code.  Hopefully this repository will help someone else who is getting started. 

# Automations:
A detailed description of each of my automations and a link to the yaml file is located [HERE](https://github.com/SilvrrGIT/HomeAssistant/tree/master/automation#automations)

This is the most important part of Home Assistant!  Remote control and voice commands are nice, however, that is not home automation, just remote control.  Automations should make your life easier, look at what you do every day, the simplest things, and automate them.  To me Home Automation is collecting data about your home and automatically acting based on that data.

# My Home Assistant Setup:

I run my home assistant instance on a [HP ProDesk 600 G1 Desktop Mini PC](https://support.hp.com/us-en/document/c04240180#AbT0) with i5 4590T low power processor. The base operating system is [HomeAssistant Operating System](https://github.com/home-assistant/operating-system) and it runs the Intel-NUC image of [Home Assistant ](https://www.home-assistant.io/hassio/installation/). It also runs the following add-ons. 

* [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home)
* [Backup to Google Drive](https://github.com/sabeechen/hassio-google-drive-backup)
* [Mosquitto MQTT broker](https://www.home-assistant.io/addons/mosquitto/)
* [Network UPS Tools](https://github.com/hassio-addons/addon-nut)
* [RPC Shutdown](https://www.home-assistant.io/addons/rpc_shutdown/)
* [SSH](https://www.home-assistant.io/addons/ssh/)
* [Samba](https://www.home-assistant.io/addons/samba/)
* [Unifi Controller](https://github.com/hassio-addons/addon-unifi)
* [VScode](https://github.com/hassio-addons/addon-vscode)

I'm currently running [Home Assistant](https://home-assistant.io) version __0.114.0__.

# UI Based Integrations:
The following integrations are setup in the User Interface (UI) and may be a missing peice as to the full configuration of my HA setup. 

* [IKEA Trådfri (Tradfri)](https://www.home-assistant.io/integrations/tradfri/)
* [Internet Printing Protocol (IPP)](https://www.home-assistant.io/integrations/ipp/)
* [iOS](https://www.home-assistant.io/integrations/ios/)
* [LIFX](https://www.home-assistant.io/integrations/lifx/)
* [MQTT](https://www.home-assistant.io/integrations/mqtt/)
* [NUT](home-assistant.io/integrations/nut/)
* [Samsung TV](https://www.home-assistant.io/integrations/samsungtv/)
* [Speedtest](https://www.home-assistant.io/integrations/speedtestdotnet/)
* [Unifi Controller](https://www.home-assistant.io/integrations/unifi/)
* [ZWave](https://www.home-assistant.io/docs/z-wave/installation)

# A Few Stats On my Setup:
| Tracked Devices | Lights | Binary Sensors | Switches | Automations | Scripts | Sensors | Zwave Devices |
|:---------------:|:------:|:--------------:|:--------:|:-----------:|:-------:|:-------:|:-------------:|
|43               |21      |0               |19        |68           |10       |116      |11             | 

# Connected Devices:

### Cloud Controlled Devices:

* [Google Nest Hub](https://store.google.com/us/product/google_nest_hub) Used for voice commands to turn devices on/off and casting a view with a few switches
* [iPhone 11](https://www.apple.com/iphone-11/) Used for presence detection

### Wifi Connected Devices
* [Xiaomi Yeelight RGBW E27 Smart LED Bulbs](http://www.gearbest.com/smart-lighting/pp_361555.html) *
* [Xiaomi Yeelight E27 Smart LED Bulbs](http://www.gearbest.com/smart-light-bulb/pp_278478.html) *
* [Sonoff Basic (Flashed with Tasmota)](https://www.amazon.com/Sonoff-Wireless-Modified-Low-cost-Compatible/dp/B06WWNBD3Y?ref=ast_p_ei)*
* [Sonoff POW (Flashed with Tasmota)](https://www.amazon.com/Sonoff-Consumption-Monitoring-Appliances-Compatible/dp/B06XSD6PD6?ref=ast_p_ei)*
* [Sonoff TH16 (Flashed with Tasmota)](https://www.amazon.com/Sonoff-TH16-Temperature-Monitoring-Compatible/dp/B06XTNSJ46)*
* [OpenGarage Door Controller ](https://www.amazon.com/OpenGarage-WiFi-enabled-Garage-Door-Opener/dp/B01M4RL0CL)*
* [Kuled WiFi Light Switches (Flashed with Tasmota)](https://www.amazon.com/Required-Wireless-Requires-Schedule-Compatible/dp/B079FDTG7T)*
* [Firefly Electronix Wifi Doorbell](https://www.fireflyelectronix.com/product/wifidoorbell)*
* [Lifx Mini Color Bulb](https://www.lifx.com/collections/lamps-and-pendants/products/lifx-mini-color)*
* [Wifi RGBW LED Strip](https://www.amazon.com/gp/product/B07QBKRCW1)*
* [Reolink E1 Zoom](https://reolink.com/product/e1-zoom/)*
* [Raspberry Pi Zero W](https://www.raspberrypi.org/products/raspberry-pi-zero-w/)* with 2 DS18B20 and 1 DHT22 sensors connected

### Zwave / Zigbee Devices
* [Ikea TRÅDFRI LED Bulbs](http://www.ikea.com/us/en/catalog/products/20318267/)
* [Ikea TRÅDFRI Remote](http://www.ikea.com/us/en/catalog/products/20303317/)
* [Mono Price Z-wave Door Tilt Sensor ](https://www.monoprice.com/product?p_id=11987)
* [GE Z-Wave Plus Hinge Pin Door Sensors ](https://www.amazon.com/GE-Wireless-Attaches-Existing-32563/dp/B01KQDIUAW/)
* [Aeotec Z-wave Range Extender ](https://www.amazon.com/Aeotec-Range-Extender-Z-Wave-repeater/dp/B01M6CKJXC)
* [Dome Miniature, Z-Wave Plus Door/Window Sensor](https://www.amazon.com/Dome-Home-Automation-Miniature-DMWD1/dp/B01JGMZNNG)
* [Go Control Thermostat](https://www.gocontrol.com/detail.php?productId=3)
* [Aeotec Home Energy Meter Gen2 ](https://aeotec.com/z-wave-home-energy-measure/)
* [Zooz Z-wave Dimmer Switches ](https://www.amazon.com/Z-Wave-Switch-Existing-Switches-Add-Ons/dp/B07K37BNMC?th=1)

### Hardwired Devices
* [Cyberpower CP1500PFCLCD UPS ](https://www.amazon.com/CyberPower-CP1500PFCLCD-Sinewave-Outlets-Mini-Tower/dp/B00429N19W) used to detect power outages and keep network and HA running in a power outage.
* [Ubiquiti Unifi AP-AC Long Range - Wireless Access Point](https://www.ui.com/unifi/unifi-ap-ac-lr/) used for presence detection
* [Ubiquiti Unifi Security Gateway](https://www.ui.com/unifi-routing/usg/) used for network stats
* [Ikea TRÅDFRI Gateway](http://www.ikea.com/us/en/catalog/products/00337813/) *
* [Yamaha RX-V481 Network AV Receiver](https://usa.yamaha.com/products/audio_visual/av_receivers_amps/rx-v481_u/index.html#product-tabs) *

*Block these from external network access and they will still work on your local network with Home Assistant.

# Front End Screen Shots:

## Home
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/rooms.png">
</p>

## Weather
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/weather.png">
</p>

## Data
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/data.png">
</p>

## Switches
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/switches.png">
</p>

## Device Status
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/devicestatus.png">
</p>

## Home Assistant Status
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/ha.png">
</p>

## Network Status
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/network.png">
</p>

## Automations
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/automations.png">
</p>

## Cameras
<p align="center">
  <img src="https://raw.githubusercontent.com/SilvrrGIT/HomeAssistant/master/www/cameras.png">
</p>

# Questions?

The best way to get help on Home Assistant is the [Home Assistant Forum](https://community.home-assistant.io/).  If you have a specific question about my configuration send me a Private Message on the HA forum, my username over there is [Silvrr](https://community.home-assistant.io/u/silvrr/).  If you have found something incorrect, please submit an issue here on Github and I will get it fixed.