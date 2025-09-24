# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS
![image](https://github.com/user-attachments/assets/6fe3965a-47de-47d4-9dd1-0d52054de81b)


### 2. Schematic of Full Custom 2:1 MUX
<img width="1919" height="951" alt="Screenshot 2025-09-24 174912" src="https://github.com/user-attachments/assets/442dc751-fada-4069-b5ba-cb9c23e4147c" />




### 3. Transient Response Setup

<img width="1918" height="1079" alt="Screenshot 2025-09-24 174926" src="https://github.com/user-attachments/assets/762612ea-f7ec-43e9-8855-60cdce923dcb" />


## Output
<img width="1909" height="1077" alt="Screenshot 2025-09-24 174900" src="https://github.com/user-attachments/assets/bd09328f-c730-4618-bc94-57ef9d02c66e" />


### 1. Transient Analysis Output
<img width="1280" height="542" alt="image" src="https://github.com/user-attachments/assets/0e796bdb-f3d8-4d6d-b5a1-bb439d4b5da3" />


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
