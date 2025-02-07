# TEMPERATURE-MONITORING-SYSTEM

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : MADHUMITHA K

*INTERN ID* : CT08LRW

*DOMAIN* : EMBEDDED SYSTEMS

*DURATION* : 4 WEEKS

*MENTORS* : NEELA SANTOSH

*Description* :

This program is aimed at using an Arduino or a similar board to display the current temperature on a 20x4 LCD screen via the I2C interface. It reads temperature data from a thermistor connected to analog pin A0 and shows the temperature in Celsius on the LCD. During the setup() function, the LCD is initialized, and the backlight is activated. Initially, the screen displays "Hello World" as a greeting. The loop() function then continuously reads the temperature every second, clears the screen, and updates it with the current temperature value by calling the readTemp() function. The readTemp() function determines the temperature using the Steinhart-Hart equation, which is commonly used to convert thermistor resistance to temperature in Celsius. The constant BETA is utilized for the thermistor's specific properties, and the analog value from pin A0 is read to compute the temperature. This value is then converted to Celsius and returned for display. This project showcases how to use a thermistor with an Arduino, apply temperature conversion equations, and present the results on an LCD, making it a valuable tool for basic temperature sensing and monitoring applications.

*OUTPUT:*

![Image](https://github.com/user-attachments/assets/186630ff-c1bb-473c-b5b7-9265987e269f)
