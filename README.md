# Street Lamp Substation

The Street Lamp Substation serves as a vital communication bridge between the linear network of street lamps and the main station responsible for monitoring any faults within the system. This repository contains the code and documentation for the substation device.

## Functionality

The substation employs the following components and functionalities:

- **ESP32 Module**: Receives data from the street lamps.
- **Arduino**: Processes the received data before transmission.
- **GSMA Connectivity**: Transmits processed data to the main station.
- **3.7-Volt LiPo Battery**: Provides stable power supply to the GSM board.
- **16x2 LCD Display**: Indicates the status of data reception and transmission.

## Setup Instructions

To set up the Street Lamp Substation, follow these steps:

1. **Hardware Setup**:
   - Connect the ESP32 module to the street lamp network using esp- now protocall.
   - Connect the Arduino to the ESP32 module using UART communication.
   - Ensure the GSM board is connected to the Arduino for data transmission.
   - Install the 3.7-volt LiPo battery to power the GSM board.

2. **Software Setup**:
   - Upload the provided code to the Arduino.
   - Ensure all necessary libraries are installed for proper functionality.
   - Configure the GSM board settings for communication with the main station.

3. **LCD Display**:
   - The 16x2 LCD display will show real-time information about data reception and transmission status.

## Troubleshooting

If you encounter any issues during setup or operation of the Street Lamp Substation, refer to the following troubleshooting steps:

- Check the connections between components to ensure they are properly connected.
- Verify the code uploaded to the Arduino for any errors or bugs.
- Ensure the LiPo battery is adequately charged to provide power to the GSM board.

If the issue persists, please consult the documentation or seek assistance from the project maintainers.

