# Rocket Datalogger

![Roket bord](/docs/roket-bord.png)

This is an STM32-based model rocket datalogger. It logs from the following sensors:

- DAN-F10-00B ublox dual band GNSS module
- ADXL375 high G accelerometer
- BNO055 9-DOF inertial measurement unit
- MS5607-02BA high resolution altimeter sensor
- BME280 humidity, pressure and temperature sensor

The board is powered from a single 1S LiPo battery with a standard JST-PH connector. A USB-C connector is provided for downloading the flight data. a 6-pin JST-PH connector is provided to extend the device's functionality with 6 3.3V-level GPIO pins.

The GNSS module is on a seperate PCB connected with a JST-PH connector, to give the integrated antenna the appropriate orientation (facing the sky).