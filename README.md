# SZ Neo Coolcam device support App for Homey @ Athom.com
Makes Homey work with these nice and cheap chinese z-wave products

## Supported devices with most common parameters:
* NAS-PD01ZE, Motion Sensor
* NAS-WR01ZE, Power Switching Plug

## Supported devices with some parameters:
* NAS-AB01ZE, Siren
* NAS-DS01ZE, Door Sensor
* NAS-WS01ZE, Flood Sensor

## Supported Languages:
* English
* Dutch (Nederlands)

## Todo
* Add more settings to devices

## Change Log:
### v 1.1.6
**update:**
NAS-WR01ZE - Updated mobile card & insights logging to include current and voltage
**note**
note: re-pair of Power Plug required to make use of current and voltage reporting capabilities

### v 1.1.5
**add support:**  
NAS-WR01ZE - Additional settings implemented (e.g. over-load current, alarm current, time switch function)
**update:**  
NAS-WR01ZE - Bug fixes defaultConfiguration and parameters, implementation of power consumption (kWh)
NAS-WR01ZE - textual fixes (setting-labels, -hints and association group-hints)
