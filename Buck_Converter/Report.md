# Buck Converter Lab Report

## Objective
To study the operation of a Buck Converter and analyze its voltage regulation, inductor current, and efficiency.

## Theory
The Buck Converter is a DC-DC step-down converter that reduces input voltage to a lower output voltage using a switch (MOSFET), diode, inductor, and capacitor.

Key equations:
- Duty cycle: `D = Vout / Vin`
- Inductor current ripple: `ΔIL = (Vin - Vout) * D / (L * f)`
- Output voltage: `Vout = D * Vin`

## Circuit Diagram
<img width="857" height="417" alt="image" src="https://github.com/user-attachments/assets/4c1631b7-bcc7-4800-8869-fecdba547b41" />
  
Buck_Circuit.png`

## Theoritical Waveform

<img width="649" height="735" alt="image" src="https://github.com/user-attachments/assets/68caeb51-36e9-4c21-998e-fd0444888daa" />

## Simulation

- **MATLAB Simulink:**

<img width="640" height="284" alt="image" src="https://github.com/user-attachments/assets/21c744ab-583a-4e3e-890e-2dba4caaca63" />
<img width="617" height="506" alt="Screenshot 2026-03-08 215821" src="https://github.com/user-attachments/assets/2a511608-0575-4fab-b1ed-791304e3cc75" />
<img width="657" height="690" alt="Screenshot 2026-03-08 215844" src="https://github.com/user-attachments/assets/6b861b44-c9d1-41a1-bd8f-85a237443eae" />
<img width="643" height="589" alt="Screenshot 2026-03-08 215657" src="https://github.com/user-attachments/assets/29e3a4f7-6e73-45b8-ab91-670bed26cd09" />
<img width="634" height="516" alt="Screenshot 2026-03-08 215901" src="https://github.com/user-attachments/assets/19b69b9a-eec0-458d-b42e-3d610395e8e3" />

- **Proteus:** `

<img width="700" height="432" alt="image" src="https://github.com/user-attachments/assets/2e75a146-be11-4174-aca6-fbe783d41d40" />
<img width="1122" height="643" alt="Screenshot 2026-03-08 215400" src="https://github.com/user-attachments/assets/a24c2f95-3b64-4556-998b-b7c272af2395" />
<img width="1102" height="611" alt="Screenshot 2026-03-08 215422" src="https://github.com/user-attachments/assets/848ee24f-ce55-4bc1-86d9-dd23d46b6d49" />


## Calculations
- Duty cycle, inductor selection, ripple calculations, efficiency.  
- Reference your Excel file if needed: `Calculations.xlsx`

## Results
| Parameter | Simulated Value | Calculated Value |
|-----------|----------------|----------------|
| Vout      | 12 V           | 12 V           |
| ΔIL       | 0.5 A          | 0.52 A         |
| Efficiency| 92%            | 90%            |

## Conclusion
The Buck Converter successfully steps down the input voltage while maintaining continuous inductor current with minimal ripple.
