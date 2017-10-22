# helicopter_externproj
### The Source Code of Coaxial dual rotor helicopter flight control for a external project.

#### main controller ic: `GD32F130G6U6, cortex-m3@48MHz, FLASH Size: 32KB, SRAM Size: 4KB.`
#### development IDE: `Keil MDK uVision V5.24.2.0 .`
#### Toolchain: `MDK-ARM Plus Version: V5.24.1 .`
#### RF Processor: `TI CC2530, 2.4-GHz IEEE802.15.4 ZigBee SoC.`
#### IMU Sensor: `Invensense MPU6500 Motion sensor.`
#### Steer Motor Driver Chip: `DRV8833, a dual H-bridge motor driver ic.`

### NOTE:
#### the frequency of high speed crystal oscillator on flight-controller main-board is 12MHz, and the processor core operating at 48MHz frequency, so you have to modify the 'HXTAL_VALUE' macro in file 'gd32f1x0.h' to '((uint32_t)12000000)', so that the mcu can run steadily.
