# motor_speed_ctrl_pcb

The repository contains the schematic, PCB layout, arduino code and simulation of the motor speed controller.

The speed controller uses ATmega328P-PU SMD microcontroller and includes I2C/SPI/USART communication.
The PCB is also designed to be interfaced with incremental, absolute or potentiometer speed sensors. 
Two or more speed controllers can be daisy chained with I2C communication.

The arduino code uses the PID algorithm for controlling the speed of the motors.

The simulation uses continous and discrete models of the motor whose speed had to be controlled, for tuning the parameters of PID. 
This motor model can be replaced with the model of the motor that has to be controlled.
