# Flyback Converter

## Objective
To understand and analyze the operation of a flyback converter used for isolated DC-DC power conversion.

## Theory
A flyback converter is an isolated switch-mode power supply.  
Energy is stored in the transformer during the ON period of the switch and transferred to the output during the OFF period.

### Key Equation
- Turns ratio: `n = Ns / Np`
- Output voltage: `Vout = D * Vin * (Ns / Np) / (1 - D)`

## Circuit Diagram
![Flyback Circuit](Figures/Flyback_Circuit.png)

## Simulation Results
### Output Voltage
![Flyback Output Voltage](Figures/Flyback_Output_Voltage.png)

### Transformer Current
![Flyback Transformer Current](Figures/Flyback_Transformer_Current.png)

### Simulink Model
![Flyback Simulink Model](Figures/Flyback_Simulink_Model.png)

## Calculations
The project involved analysis of:
- duty cycle
- transformer turns ratio
- output voltage
- peak current
- voltage stress across components

## Results
| Parameter | Simulated Value | Calculated Value |
|---|---:|---:|
| Vout | 15 V | 15 V |
| Inductor / transformer current ripple | 0.3 A | 0.32 A |
| Efficiency | 88% | 87% |

## Repository Contents
- `Report.md` – project report
- `Figures/` – circuit and simulation screenshots

## Conclusion
The flyback converter provides isolated DC-DC conversion with good voltage regulation and is widely used in low-to-medium power applications.

