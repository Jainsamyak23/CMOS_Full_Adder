# Implementation of FULL ADDER Using 28 MOS Transistors and 28nm CMOS Technology
FULL ADDER (one bit) is designed using 28nm CMOS technology by using Synopsys Custom Compiler.


# Table of Content 
- ABSTRACT 
- INTRODUCTION
- TOOLS USED
- CMOS FULL ADDER
- NETLIST
- ACKNOWLEDGEMENT 
- REFERENCE 


## ABSTRACT

Static CMOS logic is a traditional logic family known for ease of design, a good noise margins, low power dissipation, and robustness of the circuit. The performance of 
the adder circuits and compressors is based on TMSC 28nm CMOS process models at the supply of 1v, 500Mhz frequency evaluated by the comparing of simulation results 
obtained from different software. 

# INTRODUCTION

It is based on NPCMOS logic style. Any gate in this design method consists of complementary logic networks composed of PMOS for pull-up and NMOS devices for 
pull-down. The design guarantees the output node moves to and fro between the positive rail and ground so that the static power dissipation of the circuit is negligible. 
PMOS devices will be „ON‟, if input is „logic0‟ and NMOS devices will be „ON‟, if input is „logic1‟



This adder cell uses 28 transistor based on regular CMOS structure (pull-up and pull-down networks). Complementary transistor pairs make the circuit layout straight forward. 
CMOS generates carry through a static gate .The advantage of using CMOS is that it has layout regularity, high noise margins and stability at low voltage due to complementary 
transistor pair and smaller number of interconnecting wires 

# TOOL USED

- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# CMOS FULL ADDER CIRCUIT DESIGN

The CMOS design for FULL ADDER is shown in fig. 
![IMAGE](https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/Images/CMOS%20FULL%20ADDER.png)


- SCHEMATIC
![IMAGE](https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/Images/samyak_schematicjpg.jpg)

                                                                                                                                                                                                                                                                                                                                                                            
- SYMBOL
![IMAGE](https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/Images/samyak_symbol.jpg)                                                                                                                                                                                                                                                                                                                                                                            

- TESTBENCH SYMBOL
![IMAGE](https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/Images/samyak_testbench.jpg)                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
- PRIMEWAVE WINDOW
![IMAGE](https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/Images/samyak_primewave.jpg)                                                                                                                                                                                                                                                                                                                                                                                                                                                      
- TESTBENCH WAVEFORM
![IMAGE](https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/Images/samyak_waveform.jpg)                                          

# NETLIST
The netlist of the above circuit has also been uploaded to the github repo  - (https://github.com/Jainsamyak23/CMOS_Full_Adder/blob/main/netlist.txt)

# AUTHOR
SAMYAK JAIN, MTech VLSI and Embedded Systems , Defence Institute of Advanced Technology, Pune, Maharashtra

# ACKNOWLEDGEMENT 

- Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
- Synopsys, India
- VLSI System Design(VSD) Corporation Private Limited India
- Indian Institute of Technology, Hyderabad 
- Cloud Based Analog IC Design Hackathon
- Sameer Durgoji, NIT Karnataka
- Chinmay panda, IIT Hyderabad

# REFERENCES
[1] J. Uyemura, “CMOS Logic Circuit Design”, ISBN 0-7923- 8452-0, 
Kluwer, 1999

[2] J. M. Rabaey, A. Chandrakasan, B. Nikolic, “Digital Integrated 
Circuits- A Design Perspective”, 2nd Prentice Hall, Englewood Cliffs, 
NJ, 2002.



