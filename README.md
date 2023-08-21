# Detailed Power monitoring in HA
Create detailed Power monitoring in HA

## Detailed Power Monitoring

#### Sankey diagram simple overview
![image](https://github.com/kippesikgithub/hass_detailed_power_monitoring/assets/100353268/c80061ea-6392-4408-a57a-6872167159ad)

#### Sankey diagram detailed overview
![image](https://github.com/kippesikgithub/hass_detailed_power_monitoring/assets/100353268/24246949-30ea-4902-80b8-5377cdbbc73b)


## Needed Parts
- Power Monitors
- Powercalc integration for calculating Power usage lights

### Blitzwolf SHP13
- Zigbee (z2m compatible)
- Normal plug format
- HA using polling for power monitoring

### Blitzwolf SHP15
- Zigbee (z2m compatible)
- Normal plug format

### Tuya Powerplug Orange
- Zigbee (z2m compatible)
- Normal plug format
- cheapest in NL webshop https://zdvshop.nl/winkel/tuya-zigbee-smart-stekker/

### Shelly Plug-s
- Wifi
- Normal plug format

### Shelly 1PM
- WIFI
- Can be used in/behind the wall socket
- Can be used in 3d printed housing

## Lights can be measured with the Powercalc integration.
## Home Assistant
### create Room groups for the measuring devices (Watt and kWh)
###
