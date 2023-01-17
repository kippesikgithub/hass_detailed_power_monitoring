# Detailed Power monitoring in HA
Create detailed Power monitoring in HA

## Detailed Power Monitoring

Sankey Chart Live Power Monitoring
![image](https://user-images.githubusercontent.com/100353268/212080557-2451f3be-3050-4c8a-968c-46a6e8788576.png)

Sankey Chart Power Monitoring combined with Energy Dashboard
![image](https://user-images.githubusercontent.com/100353268/212080647-847d93ce-d461-4936-936c-18de1d73c009.png)


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
