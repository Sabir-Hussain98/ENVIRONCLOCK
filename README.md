 ENVIRONCLOCK – Smart Multifunction Alarm Clock with Temperature Display
🧭 Project Overview

ENVIRONCLOCK is an embedded systems mini-project that integrates a real-time clock, temperature sensing, alarm functionality, and buzzer alerts, all presented on a 16x2 LCD display with smooth text scrolling animations.
It showcases the practical use of microcontrollers, sensors, and interrupt-driven programming for real-time applications.

🌟 Key Features

 Displays real-time clock (Hours, Minutes, Seconds)

 Measures and displays ambient temperature using LM35 sensor

 Alarm function with scrolling LCD animation

 Custom degree Celsius (°C) symbol generation on LCD

 Buzzer alert triggers when alarm time is reached

 Uses ADC to convert analog temperature data

 Implements interrupts for accurate RTC timing and responsive key inputs

 Hardware Components
Component	Description
🧠 Microcontroller	LPC2148 / ARM-7 / AVR – Core controller for all operations
 RTC Module	DS1307 or equivalent – Provides real-time clock functionality
 Temperature Sensor	LM35 – Converts ambient temperature to analog voltage
 Display	16x2 LCD for real-time data and animations
 Buzzer	Activates when alarm time matches system time
 Power Supply	Regulated 5V DC input
 Software Tools

💻 Keil µVision IDE – For Embedded C code development

🧩 Proteus 8 Professional – For circuit design and simulation

 Flash Magic – For programming LPC2148 microcontroller

 Working Principle

The RTC (DS1307) continuously provides real-time data (hours, minutes, seconds, date).

The LM35 sensor measures the ambient temperature; its analog output is converted to digital using the ADC module of the microcontroller.

The LCD displays current time, date, and temperature with smooth scrolling transitions.

When the alarm time equals the real-time clock, the buzzer activates to alert the user.

Interrupts from RTC and keypad ensure precise timing and fast user response.

Explanation:

The LPC2148 microcontroller interfaces with the RTC module, LM35 sensor, and LCD.

The buzzer is controlled through a GPIO pin and is triggered when alarm time matches real-time.

ADC channels are used for reading temperature sensor output.

External interrupts handle real-time updates and keypad inputs efficiently.

🚀 Applications

Smart digital clocks

Embedded system student projects

Temperature and alarm monitoring devices

Real-time embedded systems training modules

 Future Enhancements

 Add humidity and weather forecast features using DHT11 sensor

 Integrate IoT (Wi-Fi/Bluetooth) for mobile control and cloud sync

 Add voice command support for setting alarms

 Upgrade to touchscreen TFT LCD for an interactive UI

 Author

SABIR HUSSAIN
 Embedded Systems Engineer
 Passionate about real-time embedded applications and hardware–software integration
