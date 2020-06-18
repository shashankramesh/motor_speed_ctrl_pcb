# motor_speed_ctrl_pcb

The repository contains the schematic, PCB layout and arduino code of the motor speed controller.

The speed controller uses ATmega328P-PU SMD microcontroller and includes I2C/SPI/USART communication.
The PCB is also designed to be interfaced with incremental, absolute or potentiometer speed sensors. 
Two or more speed controllers can be daisy chained with I2C communication.

The arduino code uses the PID algorithm for controlling the speed of the motors.
