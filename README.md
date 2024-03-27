# Serial to LCD Display

## Description

This code allows text sent over the serial port (e.g., from the Serial Monitor) to be displayed on an attached LCD screen. Here's a breakdown:

- **Compatibility**: Designed for Arduino IDE 1.0 and above, compatible with library version 1.1.

- **Libraries Used**: Utilizes the Wire library for I2C communication and the LiquidCrystal_I2C library for interfacing with the LCD.

- **LCD Initialization**: Initializes the LCD with the specified address (0x27) and dimensions (20 columns, 4 rows). Backlight is turned on.

- **Serial Communication**: Sets up serial communication at a baud rate of 9600.

- **Main Loop**: 
  - Waits for characters to arrive over the serial port.
  - Clears the LCD screen.
  - Reads and displays each character to the LCD as it arrives.

This code effectively bridges communication between the serial port and the LCD display, allowing for remote text display control via serial input.
