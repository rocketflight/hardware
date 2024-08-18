# Motion Pack V1.1

This is an second prototype to add rocketry sensors to a [Heltec Wireless Tracker Version 1.1](https://heltec.org/project/wireless-tracker/)

The board includes:

- Bosch Sensortec BMP-388 altimeter
- Analog Devices MAX17048 lipo fuel gauge
- TDK InvenSense ICM-20948 -9dof motion processor
- 16Mb SPI NOR RAM
- piezo buzzer
- power and level shifting

> :no_entry: **Work in progress**: Changes include:
>
> - [x] move I2C to pins 45 and 46 to match the default Meshtastic config
> - [ ] add a LED to the piezo buzzer
> - [ ] the piezo buzzer is poor and needs improving
> - [ ] power the piezo buzzer from Vext 3.3V instead of the battery
> - [ ] fix the piezo so its louder
> - [ ] move the screw terminal headers so they are more accessible
> - [ ] move the header pins for battery on/off so they are accessible
> - [ ] try to make space for 1000mah battery (25mm wide)
> - [ ] improve how the battery is fastened (remove cable ties)
> - [ ] look at adding 2 x pyro channels
