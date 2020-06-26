# RT1052 power_mode_switch_ca (Modified)
The RT1052 Power Mode Switch (CA --- FreeRTOS?) demo. 

Based off of the MCUXpresso 11.1.1 SDK2.7.0 power_mode_switch_ca project. 
The project has been alterered for:
- FLASH is a NOR FlexSPI flash (W25Q512JV) similar to what's used in the RT102x/RT101x EVKs
- Push Button is moved from "Wake" Pin to GPIO1 Pin 18


## Debugging

As this is tested w/o the UART "Debug Console" - set a breakpoint at the assign powermode line and update, as per:

![](https://user-images.githubusercontent.com/6960865/85893682-52909680-b7c1-11ea-89cc-70081235a3e1.png)
