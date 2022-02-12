# BLDC and ESC

This project is still in progress! 

The objective of this project is to design and build a 3D printed motor. For this project, I chose to build a brushless DC motor due to the complex nature of its drive circuitry. I felt this would make a great project to learn about power electronics and motors. 

I've designed version 1 of this motor and 3D printed it with PETG and iron infused PLA (for increased flux density).

The rest of mechanical design process is going to be as follows:
- Wind 20 gauge magnet wire around the stator in a Y configuration.
- Insert and glue the neodymium magnets and bearings/shaft collars.

My current objectives for the ESC are as follows:
- Generate a block diagram that utilizes the following components: A 3 phase half bridge (inverter) and arduino to read BEMF and output appropriate PWM signals.
- Generate a circuit schematic that indicates correctly rated power transistors and power resistors.
- Design a PCB layout from the schematic and have it manufactured.
- Assemble the PCB and test the motor with the newly built ESC.

For initial motor testing, I'm going to be using an off the shelf ESC for BLDC motors. I aim to identify the maximum torque, power, rpm and voltage/current ratings for the motor, as well as motor constants.

I will continue to design a PCB layout for my own ESC and retest the motor with new ESC.

I hope to design a version 2.0 for the motor, and higher mechanical power output. Version 1.0 is designed with 3D printing constraints in mind. I plan to make version 2.0 larger, with more room for coils and therefore larger inductive capability. I plan on using a CNC machine to have all the components for version 2.0 made from metal. (Electrical steel sheets for the stator, and aluminum for the rotor and other parts.

Follow my GitHub you can keep track of my progress!
