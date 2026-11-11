# Flight Controller Firmware Starter

Bring-up and initialization code for the **5-Inch Autonomous Wall-Inspection Flight Controller (STM32H743VIT6)**.

## Peripherals Configured
* **SPI1:** ICM-42688-P 6-axis low-noise IMU (up to 32 kHz gyro sampling)
* **I2C1:** DPS310 high-precision barometric pressure sensor
* **SPI2:** W25Q128 16MB Blackbox flash memory
* **USART1:** External GPS & Magnetometer
* **USART2:** Forward Wall ToF LiDAR rangefinder
* **UART4:** Downward Optical Flow sensor
* **USART3:** High-speed MAVLink companion computer link (Jetson/Pi)
* **UART7:** CRSF / ExpressLRS RC receiver
* **TIM1/TIM4:** DShot600 motor outputs (4-in-1 ESC)
