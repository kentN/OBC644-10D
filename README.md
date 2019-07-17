# OBC644-10D
ATmega644/1284-based arduino compatible on-board computer Reference Model

![PCB_img](/img/OBC644-10D_img.JPG "OBC644-10D")
![PCB_3D](/img/OBC644-10D-BRD.png?raw=true)

----------

## Features ##
- 3.3V system / LVTTL Logic level
- Two user Power Output with ON-OFF Control
- ATmega644P or ATmega1284P, 8MHz
- Size: 45x45mm  pin pitch compatible with UP-204GSR Universal PCB
- microSD hinge socket
- Two SPI ROM Option (FlashROM, FRAM, etc..) support SO8W and SO8N
- MPU-9250 9Dof Sensor
- MS5611  Baromater
- RX8900 RealTime Clock (TCXO) (Backup Battery Option)
- INA226 Current Shunt monitor
- I2C x1, UART x2, SPIx1, UserADCch x8, GPIOx14  

----------

## System Block ##
![system_diagram](/img/SystemBlock.png?raw=true)

## PIN Map ##
- VIN has Reverse current protection

----------

## Applications ##

- analog & Motion Datalogger
- Energy Harvest sensor
- DIY Space
- DIY HAB

----------

## Project Environment ##

- KiCad (4.0.x)
- Arduino IDE (1.8.X)
- Sanguino bootloader ( https://github.com/Lauszus/Sanguino )
- SDfatlib 
