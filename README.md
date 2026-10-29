# Wind Farm Simulation Using DFIG

## Overview
I simulated a 9 MW wind farm in MATLAB/Simulink using a Doubly-Fed Induction Generator (DFIG). The wind farm consists of six 1.5 MW wind turbines connected to a 120 kV utility grid through transformers and a 30 km transmission line. I used a detailed electrical model to study the dynamic behaviour of the wind energy conversion system and its interaction with the grid.

## Simulation Setup
- **Wind Farm Capacity:** 9 MW (6 × 1.5 MW)
- **Generator:** Doubly-Fed Induction Generator (DFIG)
- **Wind Speed:** 15 m/s
- **Grid Voltage:** 120 kV
- **Distribution Voltage:** 25 kV
- **Simulation Type:** Discrete-time simulation
- **Sampling Time:** 5 × 10⁻⁶ seconds
- **Simulation Duration:** 0.2 seconds
- **Reactive Power Reference:** 0 pu

## System Components
- I modelled six wind turbines driven by a DFIG-based wind energy conversion system.
- I connected the wind farm to a 25 kV distribution network through a transformer rated at 25 kV/575 V.
- I incorporated a 30 km transmission line and a 120 kV grid connection.
- I configured the simulation to monitor electrical and mechanical variables during operation.

## Simulation Analysis
I monitored the following parameters using Simulink scopes:
- Three-phase voltages and currents at the 25 kV and 575 V buses.
- Active power output (MW) and reactive power output (Mvar).
- DC-link voltage (Vdc).
- Rotor speed in per unit (pu).

I used these measurements to examine the wind farm's power output, electrical response, and interaction with the grid.

## Tools & Technologies
- MATLAB
- Simulink
- Simscape Electrical

## Reference
[MathWorks – Wind Farm DFIG Detailed Model](https://www.mathworks.com/help/physmod/sps/ug/wind-farm-dfig-detailed-model.html)
