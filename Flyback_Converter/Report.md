# Flyback Converter Lab Report

## Objective
To understand and analyze the operation of a Flyback Converter, used for isolated DC-DC conversion.

## Theory
The Flyback Converter is a type of isolated switch-mode power supply. It stores energy in a transformer during the ON period of the switch and releases it to the output during OFF period.

Key equations:
- Turns ratio: `n = Ns / Np`
- Output voltage: `Vout = D * Vin * (Ns / Np) / (1-D)`

## Circuit Diagram
*Insert circuit diagram image here:*  
`Figures/Flyback_Circuit.png`

## Simulation
- **MATLAB Simulink:** `MATLAB_Simulink_Files/`
- **Proteus:** `Proteus_Files/`

*Insert simulation screenshots:*  
`Figures/Flyback_Output_Voltage.png`  
`Figures/Flyback_Transformer_Current.png`

## Calculations
- Duty cycle, transformer turns, peak current, and voltage stress.  
- Reference your Excel file: `Calculations.xlsx`

## Results
| Parameter | Simulated Value | Calculated Value |
|-----------|----------------|----------------|
| Vout      | 15 V           | 15 V           |
| ΔIL       | 0.3 A          | 0.32 A         |
| Efficiency| 88%            | 87%            |

## Conclusion
The Flyback Converter provides isolated step-up/down conversion with good voltage regulation.
