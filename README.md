## Application code for sht31 sensor on Nordic nRF5340DK

### Wiring
1. VCC -> VDD
2. GND -> GND
3. SCL -> P1.03
4. SDA -> P1.02

### Usage
- Clone the repository to a folder on your PC.
- Using VSCode (with nrf Connect extension installed) select Open an existing application and click on the folder you created.
- Select 'Add build configuration' and in the Board section click the down arrow and select nrf5340dk_nrf5340_cpuapp.
- Click Build Configuration
- Click Flash
- In CONECTED DEVICES select the COMM port to which the board is connected and a continuous stream of readings will appear in the console.

