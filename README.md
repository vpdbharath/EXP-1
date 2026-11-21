## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| BHARATH D|  | 26018983 |  |
|---|---|---|---|
| 21.11.2026 | | 26ODJ102 | |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram
<img width="1487" height="1302" alt="image" src="https://github.com/user-attachments/assets/d872d6ca-54bb-490d-a652-e67f42f07399" />


*[ Insert the KVL circuit diagram here ]*

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram
<img width="1280" height="995" alt="image" src="https://github.com/user-attachments/assets/271642f1-9c7b-45f5-a401-17062e8df8b5" />


*[ Insert the KCL circuit diagram here ]*

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation
<img width="863" height="594" alt="image" src="https://github.com/user-attachments/assets/75e72701-1efb-4607-80bc-5114c57379a8" />


*[ Paste the Proteus KVL simulation screenshot here ]*

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation
<img width="856" height="376" alt="image" src="https://github.com/user-attachments/assets/6f21222a-7e96-4c2f-aae7-8d8ad3537b11" />


*[ Paste the Proteus KCL simulation screenshot here ]*

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements
<img width="1600" height="732" alt="image" src="https://github.com/user-attachments/assets/f5b7c277-2ae8-4e8e-ab67-added71ced21" />


### B. KCL – Current measurements
<img width="1280" height="678" alt="image" src="https://github.com/user-attachments/assets/a83fb0f0-e885-4370-af8b-2a1e7a79e24b" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.
<img width="1600" height="732" alt="image" src="https://github.com/user-attachments/assets/a7a94c69-6584-479b-b860-3e47130420f2" />
<img width="1463" height="1047" alt="image" src="https://github.com/user-attachments/assets/7bdaa070-fe64-4875-9067-aa4f0ceb7d88" />



*[ Paste the KVL calculation screenshot here ]*

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1600" height="1128" alt="image" src="https://github.com/user-attachments/assets/44c5d437-5fc9-4d27-a78d-c889e79669bb" />

<img width="1160" height="1600" alt="image" src="https://github.com/user-attachments/assets/1c942531-8a57-4999-99c4-dd2c86e3e584" />






*[ Paste the KCL calculation screenshot here ]*

**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
