# Raspberry Pi flight controller RasPilot

## RasPilot hardware parameters

### Characteristics

* Support Raspberry Pi 1 A + / B +; 2 B +; 3 
* STM32F103 failsafe co-processor
* ardupilot Flight Control Code
* pixhawk interface is compatible
* USB (RPi) / Servo Rail BEC / Power Module three-way power input

### Sensors

* ST Micro L3GD20H 16 bit gyroscope
* ST Micro LSM303D 14 bit accelerometer / magnetometer
* Invensense MPU 6000 3-axis gyro / accelerometer
* MEAS MS5611 barometer

### Interfaces

* 2x UART
* 1x CAN
* 8x PWM
* Spektrum DSM / DSM2 / DSM-X® Satellite receiver compatible
* Futaba S.BUS® compatible input and output
* PPM sum Receiver
* RSSI (PWM or voltage) input
* 1x I2C
* 3.3V & 6.6VA / D input
* Safety switch
* Buzzer Interface
* Onboard tri-color LED

## Hardware installation and wiring

1 mount enclosure. As shown, with pillars and nuts raspberry pie is fixed to the bottom case. Plug expansion board flight control, and then screw on the housing. 

![](https://github.com/raspilot/docs/blob/master/raspilot_p1.jpg)
![](https://github.com/raspilot/docs/blob/master/raspilot_p2.jpg)

2 Interface Description: 

![](https://github.com/raspilot/docs/blob/master/connectors.jpg)
