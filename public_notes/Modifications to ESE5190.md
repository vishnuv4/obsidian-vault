# Introduction
## Motivation
- RTOS, while being a useful embedded systems concept, isn't something that students use in final projects. 
- Students get very little exposure to serial communications, which is something almost every team struggles with in the final project.

# Course Material -- Requirements
1. The content from Lab 5 shall be merged with the content in Worksheet 4: RTOS.
1. Pong shall be Lab 5.
1. Lab 4 shall be a brand new lab on serial communications, with its own requirements.
1. The serial part of Worksheet 3: Stacks, Assembly, Serial shall be added to Lab 4

# Lab 4: Serial Communications -- Requirements
The lab shall walk students through communication between two XMINIs.

1. There shall be 4 main deliverables in the lab - SPI controller, SPI peripheral, I2C controller, I2C peripheral.
1. The end task for each shall be to press the on-board button on the controller MCU and have the on-board LED of the other board light up.
1. These tasks shall be broken up appropriately in a manner that walks a complete beginner through the code
	- TODO: Rewrite this, bad requirement but conveys the idea

# Notes

### Notes on requirements

- The sercoms lab has to be before Pong, otherwise students will just use the SPI code from Pong and won't do it themselves.
- Perhaps the serial part of WS3 can be removed. 
	- While I appreciate what it's trying to teach, students don't really use NRZ encoding and we can probably allocate those points to something more fundamental.
- Instead, we can maybe go a bit more into depth about memory or the compilation/linking/loading process.
	- While it's not useful for OTS micros, it can be incredibly important to know how code works with memory while working on embedded firmware for a custom IC, as opposed to an off-the-shelf IC.
	- We can help them understand how to think about RAM, ROM, Flash, EEPROM - what the properties are of each memory, how code interacts with each, and how that determines what type of data is stored where.
	- This kind of exercise is better suited to a worksheet than a lab anyway.
- If 4 projects - SPI RX/TX, I2C RX/TX - is too much for students, we could give them one or two.
- 

## Other topics that can be covered

- Motors is one thing that would be nice to cover. However, this can add a lot to the budget and it's unclear how it would fit into the existing scheme of things.
- Linker scripts and map files? Possibly too advanced, but I believe there might be a way to structure and organize it well enough to atleast impress upon students how important they are.