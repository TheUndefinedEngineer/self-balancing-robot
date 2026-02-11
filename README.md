# Self Balancing Robot (STM32F401)

A two-wheeled self-balancing robot based on STM32F401 and MPU6500.

## Current Status
✅ Motor driver tested  
✅ PWM control working  
⬜ IMU integration  
⬜ Sensor fusion  
⬜ Control algorithm (PID / LQR)

## Progress
- IMU accelerometer read via I2C
- Motors respond to forward/backward tilt using thresholds


## Hardware
- STM32F401CCU6
- MPU6500 IMU
- TB6612FNG motor driver
- N20 Microgear motors
- StepDown 3.3v buck converter
- 7.4V LiPo battery
- Decoupling Capcitors

## Toolchain
- STM32CubeMX
- VS Code
- ARM GCC
- CMake

## Notes
This repository tracks incremental development. Expect frequent refactors.
