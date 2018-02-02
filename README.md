# Renesas_s5d9_bus_examples_i2c_spi_uart_usbx

Project Goals

Learn to configure port for popular bus standards.

Learn to generate both driver and framework versions. 

The driver version can work without ThreadX RTOS.

The framework version is suitable for applications that require ThreadX RTOS.

How to set up the hardware for testing.

Board



Renesas S5D9 IoT Fast Prototyping Kit



Software



1. Renesas E2 Studio Tool version 5.4.0.023

2. Renesas SSP version 1.30

3. S5D9 IOT ENABLER pack file





Hardware



1.The Jlink debugger board (included in S3A7 kit or purchase from SeeedStudio)

2. Pin Female Jumper To Grove 4 Pin Conversion Cable (Amazon Link)

3. Both SPI and I2C interface BMC 150 Motion and Accelerator Sensor (included S3A7 kit).  Use other SPI or I2C interface sensor module from SeeedStudio if you don't have BMC 150, but the code will require changes.

4. FTDI Serial TTL-232 USB Cable purchased from Adafruit.  This is for USB to UART conversion.



Note:  Item 3 is for the SPI and I2C tutorials.   Item 4 is for the UART tutorial.



Tutorial examples



1. Lesson 1a I2C with riic driver - Grove B port

2. Lesson 1b I2C with sci driver - Grove A port

3. Lesson 1c I2C with riic framework (RTOS) - Grove B port

4. Lesson 1d I2C with sci framework (RTOS) - Grove A port

5. Lesson 2a SPI with rspi framework (RTOS) - PMOD port

6. Lesson 2b SPI with sci framework (RTOS) - PMOD port

7. Lesson 3a UART with sci driver - Grove A port

8. Lesson 3b UART with sci framework (RTOS) - Grove A port

9. Lesson 4a USBX with usbx framework (RTOS) - USB port

10. Lesson 4b USBX with usbx framework (RTOS) and floating printf support - USB port

