# Projects
Since I could not figure out how to get SW4STM32 to play nicely with git directly, my workspace will live here for now...

## Projects currently worked on

#### Motor Control
implementation and testing of a motor control loop for speed & position control using freeRTOS and the builtin quadrature encoding of the STM32.

## Possible Projects

#### G-Code Interpreter
An interpreter for G-Code (used for CNC machines) to read code from USART, possibly USB/Filesystem(SD Card/USB OTG) in the future, but only once this has been transformed into a library

#### XY-Table (combining 2 axis motor control and the G-Code interpeter)
combining the two previous projects to build a G-Code controlled CNC XY-Table
