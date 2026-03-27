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
<img width="1920" height="1200" alt="Screenshot (442)" src="https://github.com/user-attachments/assets/d18336bd-6cc8-4997-b4cb-4132dbd6d30e" />
<img width="1920" height="1200" alt="Screenshot (443)" src="https://github.com/user-attachments/assets/1786cba0-7087-45ef-868f-d08871cbfd67" />
<img width="1920" height="1200" alt="Screenshot (444)" src="https://github.com/user-attachments/assets/38951be3-ca69-4df0-ba88-cb6bf4c579df" />
<img width="1920" height="1200" alt="Screenshot (445)" src="https://github.com/user-attachments/assets/df3befbb-0338-47d8-a34a-a7fe9e06b18b" />
<img width="1920" height="1200" alt="Screenshot (446)" src="https://github.com/user-attachments/assets/8cd00059-6394-451b-b518-0672fe426623" />


### 2. Network Server – Recent Events
<img width="1920" height="1200" alt="Screenshot (431)" src="https://github.com/user-attachments/assets/5771f4ee-5b97-4835-b4c3-389481c6853f" />
<img width="1920" height="1200" alt="Screenshot (433)" src="https://github.com/user-attachments/assets/420b533e-3285-4581-8435-51029f2a9957" />



### 3. Dashboard Command Sending

-

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1920" height="1200" alt="Screenshot (430)" src="https://github.com/user-attachments/assets/81598aaa-8966-4e0b-8259-23957fd8e16b" />

### Bulb OFF → Relay OFF
<img width="1920" height="1200" alt="Screenshot (434)" src="https://github.com/user-attachments/assets/cbb788cc-a912-4b86-b1bb-40facdec2040" />
<img width="1150" height="853" alt="image" src="https://github.com/user-attachments/assets/5dcaeb82-3dc5-48c6-b535-1a0f3f5fa01f" />
<img width="1149" height="854" alt="image" src="https://github.com/user-attachments/assets/d16a4d56-e1ad-4a9e-b9b4-42564140a9ee" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
