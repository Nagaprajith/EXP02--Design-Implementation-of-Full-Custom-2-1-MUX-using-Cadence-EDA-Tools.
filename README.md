# EXP02--Design-Implementation-of-Full-Custom-2-1-MUX-using-Cadence-EDA-Tools.
## NAGA PRAJITH N(212223060178)

## Aim

#### The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

## Cadence EDA Suite
~~~
Virtuoso Schematic Editor (for circuit design)
Spectre Simulator (for circuit simulation)
~~~
## Process Design Kit (PDK)
~~~
CMOS technology library (e.g., 180nm, 45nm node)
~~~
## Computer System
~~~
Minimum 4GB RAM and a multi-core processor
~~~
## Procedure:
~~~
1. Launch Cadence Virtuoso Environment:
 Open the Cadence Virtuoso tool and set up the working library.
 Create a new schematic cell view for the CMOS Inverter design.
2. Schematic Design:
Select the NMOS and PMOS transistors from the library.
Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
Join the gate terminals of both transistors to form the input node.
Connect input voltage sources Vdc and Vpulse
3. Simulation:
Check the Design for Errors and proceed for Simulation
Launch the Analog Design Environment (ADE).
Configure transient analysis for time-domain response.
Set the simulation parameters such as voltage sweep range and step size.
Use Spectre simulator to perform transient and DC analyses.
4. Waveform Analysis:
Observe the output voltage waveform concerning the input voltage.
~~~
## Circuit Diagram:
### 1. CMOS Inverter:
<img width="750" height="421" alt="image" src="https://github.com/user-attachments/assets/ae8dc719-6a98-4aa2-9c05-22bd75b62439" />

### 2. Schematic of CMOS Inverter:
<img width="1265" height="650" alt="image" src="https://github.com/user-attachments/assets/f0a3329e-2d46-47c2-b85c-0a3f306cb7fe" />

## Output
<img width="1276" height="650" alt="image" src="https://github.com/user-attachments/assets/e0144022-35ee-4cf1-aed4-c36a3e57aaf8" />

## Results:
~~~
Successfully designed the CMOS inverter schematic using Cadence EDA tools.
The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.
~~~
