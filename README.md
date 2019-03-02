# VESC-Modul-Hardware
The VESC 6 Modul is a small electronics only platform that is compatible with the VESC firmware. It contains all mandatory electronics and can be combined with a wide range of mosfets and current sensing configurations.


## Electronical Features
- 3S to 12S LiPo support (14S absolute maximum)
- 5V 500mA
- 3.3V 100mA
- 3.3V 25mA low noise analog reference for precise analog readings
- USB, UART, CAN, ADC, PWM interface support (as the original VESC 6)
- Hall Sensor and SPI Encoder support via HALL1,2,3 pins

## Mechanical Features
- **18x30mm** small size
- 4 layers
- castellated pads for best solderability and space usage
![Top View](VESC modul1.PNG)
Next to the STM32F405RGT, the DRV 8320RS is used for driving the 3-Phase-Inverter.
the Board features all voltage deviding and filtering hardware, so the user only needs to connect the inputs and outputs of the modul to the required periferals respectively.

