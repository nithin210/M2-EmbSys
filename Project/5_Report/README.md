# Description
   Infrequently electric fan utilization is dissipated as a result of human behaviour. Humans generally requests something that effortlessly to be utilized without squandering vitality. To minimize or diminish the force use, this venture added to a programmed framework where pace is controlled by the room temperature.
   Generally, electronic gadgets create enough heat due to internal loss. There is a necessity to decrease heat so that electronic devices won’t lose their characteristic. The heat can be minimized in various methods. One of the method is temperature dependent dc fan implementing microcontroller. When environment temperature sensed by the sensor crosses the threshold value, fan is switched on and temperature is reduced. The fan will remain on till the temperature reduces below the threshold value. This general idea is used in this project.

# Requirements
## High Level Requirements
| ID | Description | 
| --- | --- | 
| HR01 | Temperature monitoring.  | 
| HR02 | Controlling temperature using L293D | 
| HR03 | Maintaining the temperature. | 

## Low Level Requirements
| ID | Description | 
| --- | --- | 
| LR01 | Temperature sensor. | 
| LR02 | AVR ATMega328 | 
| LR03 | L293D | 
| LR04 | Cooling fan. | 

# Advantages
1. It is economical and easy to handle
2. Fan runs automatically
3. It is easy to install in heat dissipating devices to cool them down
4. Saves energy by turning off fan automatically at room temperature

# Disadvantages
1. Micro controller is the heart of the circuit, if controller is damaged the whole system will be interrupted.
2. Speed control is independent of individual preference.

# Block Diagram
![BlockDiagram](https://github.com/nithin210/M2-EmbSys/blob/c58d8c9c9c4622ed30df9f080114df4628614329/Project/5_Report/BlockDiagram.jpeg)

# Memory: 
ATmega8 microcontroller contains 8 Kb Flash system memory around 10,000 times it can be write or 
erased.
It has 512 bytes of EEPROM and it can perform write or erase operation 100,000 times.
It also has 1 Kb internal Static RAM.

# Input/output Ports:
There are 23 input lines which comes from three different ports. The three different ports are Port B, Port 
C and Port D.

# Interrupts:
Port D has two external input source. Nineteen different types of interrupt vectors handling nineteen 
operations produced by the internal peripheral.

# Timer and Counter:
Different types of timers are available in microcontroller ATmega8 which are used internally. 2 of them 
are of 8 bits and 1 of them is of 16 bits which works in different operations and also supports internal 
and external clock.

# Serial Peripheral interface:
In ATmega8 microcontroller three types of communication devices are inbuilt. Serial Peripheral 
interface, USART and two wire interface are used for communication purpose. For controlling Serial 
Peripheral interface four pins are used in ATmega8 microcontroller for the purpose of communication.

# USART:
USART is highly efficient in communication. 3 pins are declared for the USART communication. This 
communication is used in almost all projects. Asynchronous and synchronous data transfer is possible in 
ATmeg8.

# Two Wire Interface:
ATmega8 microcontroller has a third communication devices known as two wire interface. This helps in
communication between two devices. It is possible with the help of two wire and common ground 
connection. Pull up resistor are used to complete the circuit.

# Analog Comparator:
In ATmega8 microcontroller two external pins are embedded which are used for comparison of two 
voltages. A comparator is a device which compares between two signals. So these two voltages are used 
as an input to the comparator.

# Analog to Digital Converter:
ADC are inbuilt in the microcontroller which converts the analog signal into digital signal internally. 
ADC converts the analog signal into digital signal of 10 bit resolution. This part is very essential part of 
the microcontroller.
The flash programmable memory can be many times read and write using the serial port interface (SPI). 
This memory is burn by AVR programmer. Port C can be selected as an input port and the input is given 
to anyone of the bits of Port C (PC0 to PC7). 
From the below figure a general idea is given about ATmega8 microcontroller. Its interfacing between
the ports, buses, CPUs and serial port communications, ALU units, interrupt signals, registers, internal 
oscillators, timer and counter, these all are shown in block diagram which can be understood easily. Port 
B used as an output port in ATmega8 microcontroller.

# ATmega8:
The ATmega8 microcontroller contains 32 general purpose working registers. As shown in the below 
figure these registers are directly connected to ALU. Two registers can carry one single instruction
consequently in one clock cycle.

# Output:
![Image_1](https://github.com/nithin210/M2-EmbSys/blob/5960f57a232b1cb8739e373e06ad361a4987e1d0/Project/5_Report/Image_1.PNG)

![Image_2]()
