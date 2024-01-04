

## Components used :

  * STM32F446RE Microcontroller
  * HC­SR04 Ultrasonic Sensor  
  

## How to build

Run this command:

    ./run.sh compile_only tempreture_contoll NO

## How to flash

You need to install OpenOCD and GDB in your system. Then:

    ./run.sh flash

## How to monitor

You need to install "picocom" in your system. Then:

    ./run.sh monitor


## wiring

 | sensor pins     | mcu pins | 
|-----------|-----|
| vcc     | U5v(pin8) | 
| Trig    | PA5 (output) | 
| echo    | PA6 (input) | 
|  GND    | GND (pin7)|


## Requirements

* CMake (for linux users : sudo apt install cmake)
* Make 
* gcc-arm-none-eabi
* openOCD
* GDB


 ## Installation

 To install the project, follow these steps:

  1. Clone the repository
  2. Open the project in your preferred IDE
  3. Compile and upload the code to the NUCLEO_F446RE microcontroller

## datasheet

   HC­SR04 Ultrasonic datasheet: 
    [Download PDF]( datasheet/HC-SR04.PDF )
    