# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![WhatsApp Image 2025-11-17 at 16 46 41_934b6486](https://github.com/user-attachments/assets/ce03dea5-deb1-4a5c-8f8a-60cc952cd88b)

![Screenshot 2025-05-10 160505](https://github.com/user-attachments/assets/4031c7a7-7c0f-4397-a936-ac4f90c4f402)

### Schematicand Symbol of 2-Input EX-OR Gate:

![WhatsApp Image 2025-11-17 at 16 54 17_b891205d](https://github.com/user-attachments/assets/4a55f9f6-48c1-416a-9f8c-9e516002f1e7)

![Screenshot 2025-05-10 160523](https://github.com/user-attachments/assets/4230854b-5f8e-43d0-9875-258b457660e3)

### Schematicand Symbol of Half Adder:
![WhatsApp Image 2025-11-17 at 16 46 41_54531238](https://github.com/user-attachments/assets/ab0cad77-fbc1-4ff2-8764-7d2a4c082531)

![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
![WhatsApp Image 2025-11-17 at 16 42 09_09a5d7cd](https://github.com/user-attachments/assets/08bb6ff7-483d-4aac-b7c7-2c7b6d6ac982)

## Output
### Transient Analysis Output:
![WhatsApp Image 2025-11-17 at 16 42 31_b6f8f895](https://github.com/user-attachments/assets/5a5123f4-a896-4ca9-b46a-be49b24df4ae)

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


![Uploading WhatsApp Image 2025-11-17 at 16.41.54_52aae137.jpg…]()


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
