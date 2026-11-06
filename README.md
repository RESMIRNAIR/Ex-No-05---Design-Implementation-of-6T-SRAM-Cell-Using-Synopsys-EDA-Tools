# Ex No: 05 - Design & Implementation of 6T SRAM Cell Using Synopsys EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Synopsys EDA Suite
- Synopsys Custom Compiler – For CMOS schematic design.
- Synopsys PrimeWave Design Environment – For simulation setup and waveform analysis.
- Synopsys PrimeSim HSPICE / PrimeSim – For circuit simulation and analysis.

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**
- Linux-based operating system compatible with the installed Synopsys tools.

## Procedure:
### 1. Launch Synopsys Custom Compiler Environment :
     Open Synopsys Custom Compiler and set up the working library.
     Create a new design library and associate it with the appropriate CMOS technology PDK.
     Create a new schematic cell view for the CMOS circuit design.
### 2. Schematic Design:
    Launch Synopsys Custom Compiler and create a new design library associated with the appropriate CMOS technology PDK.
    Create a new schematic cell view for the required CMOS complex gate.
    Select the required NMOS and PMOS transistors from the technology library based on the given Boolean expression.
    Connect the NMOS and PMOS transistors appropriately to implement the required pull-down and pull-up networks.
    Connect the transistor gate terminals to the corresponding input signals.
    Connect the supply terminals to VDD and GND, ensuring that the bulk terminals are connected to the appropriate supply potentials.
    Connect DC voltage sources (VDC) to provide the required supply voltage and pulse voltage sources (VPULSE) to apply the input signals.
    Connect the output terminal to the common node of the pull-up and pull-down networks.
### 3. Simulation:
    Check the schematic for errors and verify the electrical connections.
    Create a testbench for the CMOS design.
    Launch Synopsys PrimeWave Design Environment.
    Select the appropriate simulator, such as PrimeSim HSPICE.
    Configure transient analysis to study the time-domain response.
    Set the simulation parameters, including supply voltage, input pulse period, rise time, fall time, and simulation stop time.
    Run the simulation and verify the simulation results.


## Circuit Diagram

<img width="579" height="442" alt="WhatsApp Image 2026-08-06 at 14 28 41" src="https://github.com/user-attachments/assets/65e51932-9284-40b2-b41a-a7cb47aee9d9" />


## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

 <img width="1251" height="702" alt="WhatsApp Image 2026-11-06 at 12 07 26 PM" src="https://github.com/user-attachments/assets/e9b28591-b5d3-4e4c-bfc6-249721c7d27d" />

<img width="1600" height="760" alt="WhatsApp Image 2026-11-06 at 12 08 12 PM" src="https://github.com/user-attachments/assets/1df2a17a-0e59-4181-b09e-9facc593dfb1" />


## Output
#### 1. Transient Analysis Output:

  <img width="1600" height="738" alt="WhatsApp Image 2026-11-06 at 12 06 49 PM" src="https://github.com/user-attachments/assets/4473f801-3237-4984-8942-038a989b08a8" />



## Results:
1. Successfully designed the 6T SRAM cell schematic using Synopsys EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


