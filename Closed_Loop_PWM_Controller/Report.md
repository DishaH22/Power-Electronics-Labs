# Closed Loop PWM Controller Lab Report

## Objective
To implement and analyze a closed-loop PWM controller for a DC-DC converter to maintain constant output voltage under varying loads.

## Theory
Closed-loop PWM control uses feedback from output voltage to adjust duty cycle dynamically.  
- Controller type: PI/PID  
- Duty cycle adjustment: `D(t) = Kp * e(t) + Ki * ∫e(t) dt`

## Circuit Diagram
*Insert circuit diagram image here:*  
`Figures/PWM_Circuit.png`

## Simulation
- **MATLAB Simulink:** `MATLAB_Simulink_Files/`
- **Proteus:** `Proteus_Files/`

*Insert simulation screenshots:*  
`Figures/PWM_Output_Voltage.png`  
`Figures/PWM_Inductor_Current.png`

## Calculations
- Error signal, controller parameters, duty cycle adjustments.  
- Reference `Calculations.xlsx` for numerical analysis.

## Results
| Parameter | Simulated Value | Set Point |
|-----------|----------------|-----------|
| Vout      | 12 V           | 12 V      |
| Ripple    | 0.1 V          | 0.12 V    |
| Settling Time | 2 ms        | 2.2 ms    |

## Conclusion
The closed-loop PWM controller maintains a stable output voltage with minimal ripple under varying load conditions.
