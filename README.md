# RT1052 power_mode_switch_ca for _seeed_ Arch Mix Board
The RT1052 Power Mode Switch (CA --- FreeRTOS) demo - ported over to the Arch Seeed board. 

Info on the Arch Mix seeed board can be found [here](https://wiki.seeedstudio.com/Arch_Mix/)
Tutorial on getting up and running on the Arch Mix seeed board avialable from McuOnEcplipse - [here](https://mcuoneclipse.com/2019/07/25/seeed-studio-arch-mix-nxp-i-mx-rt1052-board/)

Based off of the MCUXpresso 11.1.1 SDK2.7.0 power_mode_switch_ca project. 
The project has been alterered to run on the Arch Mix seeed board:
- FLASH is a NOR FlexSPI flash (IS25W P064A) same as the RT102x EVKs



## Debugging

On both custom hardware and the seeed Arch Mix board - it appears this demo doesn't properly handle user input over UART / terminal. 

For sanity's sake, to update power modes and test - set a breakpoint at the assign powermode line and update, as per:

![](https://user-images.githubusercontent.com/6960865/85893682-52909680-b7c1-11ea-89cc-70081235a3e1.png)
