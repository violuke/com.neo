# SZ Neo Coolcam device support App for Homey @ Athom.com
Makes Homey work with these great and cheap Chinese z-wave products

## Supported devices with most common parameters:
* NAS-PD01ZE, Motion Sensor
* NAS-WR01ZE, Power Switching Plug
* NAS-SC01ZE, Touch Wall Switch Single
* NAS-SW01ZE, Touch Wall Switch Dual
* NAS-AB01ZE, Siren / Doorbell speaker
* NAS-DS01ZE, Door Sensor
* NAS-WS01ZE, Flood Sensor
* NAS-RC01ZE, SOS KeyFob    

## Supported devices with some parameters:
None until Neo releases new products

## Supported Languages:
* English
* Dutch

## Support notes:
Most reliable way to update battery powered devices   
1. Place the sensor near Homey (< 1 meter)   
2. Change the settings to the values you want   
3. Wake up the sensor (triple click the button)   
4. During the blinking of the LED (indicating connection to Homey) press "save settings"   

If problems persists:    
a. Temporarely disable other Z-wave apps   
b. change the setting to another value with above steps   
c. check if effective and retry to the desired value    

## Change Log:       
 
### v 1.1.23    
**fixed:**    
NAS-SW01ZE - Support for V1 and V2 Touch Wall Switch Dual  

### v 1.1.22    
**update:**    
all - Add productDocumentation and unlearnmode    
all - Updated NEO branded images    

### v 1.1.21    
**fixed:**        
NAS-AB01ZE - Add action card for setting alarm or doorbell tune    
NAS-AB01ZE - Fixed alarm state action card    

### v 1.1.20    
**fixed:**        
NAS-DS01ZE - Settings naming error corrected (basic_set_level)       

### v 1.1.19
**fixed:**    
NAS-SW01ZE - updated driver, tested and working ok (re-pair of device required)   

**update:**    
NAS-SW01ZE - Add switch LED action card to enable / disable the LED's   
NAS-AB01ZE - Updated action card for alarm mode (Siren / Doorbel)   
NAS-AB01ZE - Updated action card for alarm state (Sound / Silence)  
Updated Z-wave driver (1.1.8)   

### v 1.1.18
**update:**    
NAS-AB01ZE - Add Siren / Doorbel switch mode action card    
Updated Z-Wave driver (1.1.6)    

### v 1.1.17
**update:**
NAS-WR01ZE - Add Power Meter reset flow card    

### v 1.1.16
**update:**
All devices - update battery_alarm, code clean-up, minor fixes   

### v 1.1.15
**update:**    
NAS-SW01ZE - Defined multinode 1, should be done by itself but made sure multinode 1 is also defined just i case this might ever change.    

### v 1.1.14
**update:**    
NAS-AB01ZE - Updated mobile card to show battery alarm and toggle on icon     

**notes:**   
Somehow battery reporting has stopped again with the Homey 1.1.4 firmware.  
In order to get it working again re-pair of device is required, for now this looks like the only solution.  

### v 1.1.13
**update:**    
Support for GetOnWakeUp in Z-Wave driver enabled
Updated Z-Wave driver

### v 1.1.12
(Only released in Developers Preview for testing)

### v 1.1.11
**update:**    
NAS-AB01ZE - Updated driver for compatibility 1.1.3 firmware     
NAS-DS01ZE - Updated driver for compatibility 1.1.3 firmware     
NAS-PD01ZE - Updated driver for compatibility 1.1.3 firmware       
NAS-WS01ZE - Updated driver for compatibility 1.1.3 firmware     
NAS-WR01ZE - Updated driver for compatibility 1.1.3 firmware (standardized custom capabilities)     

### v 1.1.10
**update:**    
NAS-AB01ZE - Add battery alarm and updated battery reporting + All settings added so the siren can also be used as doorbell speaker   
NAS-DS01ZE - Add battery alarm and updated battery reporting + All settings added     
NAS-PD01ZE - Add battery alarm and updated battery reporting   
NAS-WS01ZE - Add battery alarm and updated battery reporting    
NAS-WR01ZE - re-added custom capabilities due to delays on Homey v1.1.3   

**notes:**   
In order to make use of the battery alarm functionality, re-pair of device is required.    
Battery reporting should work after app / driver update
-------------

Older changelog notes have been ereased from this timeline......
