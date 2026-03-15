# Closed Loop PWM Controller Lab Report

## Objective
To implement and analyze a closed-loop PWM controller for a DC-DC converter in order to maintain a constant output voltage under varying load conditions.

## Theory
Closed-loop PWM control uses output-voltage feedback to dynamically adjust the duty cycle of the converter.

- Controller type: PI/PID
- Duty cycle relationship: `D(t) = Kp * e(t) + Ki * ∫e(t) dt`

## Circuit Diagram
![Closed Loop PWM Circuit](Figures/PWM_Circuit.png)

## Simulation Setup
This project was modeled and analyzed using:
- MATLAB/Simulink
- Proteus

### Simulink / Converter Response
![Output Voltage Response](Figures/PWM_Output_Voltage.png)

### Inductor Current
![Inductor Current](Figures/PWM_Inductor_Current.png)

### Additional Model View
![Simulink Model](Figures/Simulink_Model.png)

## Calculations
The controller tuning and numerical analysis were used to evaluate:
- error signal
- controller gains
- duty cycle adjustment
- output voltage regulation

Detailed calculations are provided in `Calculations.xlsx`.

## Results
| Parameter      | Simulated Value | Set Point |
|---------------|-----------------|-----------|
| Vout          | 12 V            | 12 V      |
| Ripple        | 0.1 V           | 0.12 V    |
| Settling Time | 2 ms            | 2.2 ms    |

## Key Outcome
The controller maintained the desired 12 V output with low ripple and fast settling time under changing load conditions.

## Repository Contents
- `Report.md` – project documentation
- `Figures/` – circuit and simulation screenshots
- `MATLAB_Simulink_Files/` – simulation files
- `Proteus_Files/` – Proteus implementation
- `Calculations.xlsx` – controller and performance calculations

## Applications
This project is relevant to:
- DC-DC converter control
- closed-loop control systems
- power electronics
- voltage regulation
- embedded control and automation

## Author
Disha Harwalkar
