# York FS Data-Logger
This is a custom PCB data-logger designed to work on our Formula Student car. It captures data from the vehicle's CAN bus, transmits telemetry, and logs to an SD card. Additionally, the data logger stores configuration information on EEPROM. 

## Key Features
- **CAN bus interface** for vehicle data logging  
- **SD card slot** for onboard storage
- **EEPROM** for storing config data
- **Real-time clock (RTC)** with battery backup for accurate timestamps  
- **USB interface** for configuration and file transfer  
- **UART output** to a SiK telemetry radio for live data streaming  
- **Status LEDs** for logging, USB power, and telemetry status

## PCB Notes
- Designed in KiCad 9.0
- 3D models stored in external library (lib)

<img width="1427" height="1072" alt="data_logger" src="https://github.com/user-attachments/assets/ec11ed2e-b2d6-4099-8221-15da9a07eebd" />
