# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection

<img width="1896" height="1105" alt="569075096-f73b0390-6f89-4d53-b91e-88199d4dccb3" src="https://github.com/user-attachments/assets/99fa3a5c-1c37-44cd-ac22-050907a61a90" />


### 2. Network Server – Recent Events

<img width="1865" height="1081" alt="569075256-6baf773f-e9cd-4f3f-9735-6f438819789c" src="https://github.com/user-attachments/assets/9f039f9a-6f4a-41eb-af5d-0be0aa7e4aab" />


### 3. Dashboard Command Sending

<img width="1916" height="1080" alt="569075427-e1a1d67c-30d6-46af-bf41-6e4295d83adb" src="https://github.com/user-attachments/assets/7a732849-759e-401c-b703-39ff1742afea" />


### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
### Bulb OFF → Relay OFF

<img width="1669" height="883" alt="569075639-4974998d-1b29-43b1-be40-fd3b6509028d" src="https://github.com/user-attachments/assets/3948049d-65fc-429e-9b5f-8860d171e662" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
