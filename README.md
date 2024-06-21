SHT31: I2C humitity sensor
##########################

Description
***********
 - `SHT3X-DIS sensor <https://www.sensirion.com/en/environmental-sensors/humidity-sensors/digital-humidity-sensors-for-various-applications/>`_
Wiring
******
Wiring for use with Nordic nRF5340DK board
VBCC -> VDD
GND -> GND
SDA -> P1.02
SCL -> P1.03

Building Flashing and Viewing output in console.
***********************************************
in VSCode install nRF Connect for VS Code.
In VSCODE 
1 select nRF Connect icon.
2 select Open an existing application and select the folder where you have cloned this application.
3 select add build configuration
4 select nrf5340dk_nrf5340_cpuapp as the board
5 select Build Configuration
6 select Flash
in CONNECTED DEVICES section select the COM on which the board is connected and select it again in the dropdown.

Note: if you remove the build configuration and add a new configuration using the nrf5340dk_nrf5340_cpuapp_ns board
and again follow the above procedure no output to the console is visible. 





