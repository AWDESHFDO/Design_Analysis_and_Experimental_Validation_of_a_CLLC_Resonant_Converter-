
This project focuses on the design, simulation, and experimental implementation of a CLLC resonant converter aimed at achieving high-efficiency isolated DC–DC conversion for Electric Vehicle (EV) battery charging. The converter is optimized for soft-switching operation, high power density, and wide output voltage range, addressing the efficiency challenges in onboard and off-board EV chargers.



The CLLC resonant converter topology was selected for its bidirectional power flow capability, ZVS/ZCS operation, and high efficiency under variable load conditions. The project encompasses complete system-level design, including parameter selection of resonant components, magnetic design, and control strategy development for both open-loop and closed-loop configurations.


Topology: Dual-active bridge-based CLLC resonant converter
Soft-Switching Operation: Achieves Zero Voltage Switching (ZVS) and Zero Current Switching (ZCS) across a wide load range
Isolation: High-frequency transformer ensures galvanic isolation between input and output stages
Control: Closed-loop control for stable voltage regulation and dynamic load response
Simulation: Conducted using MATLAB/Simulink and PLECS for performance validation under different operating modes
Hardware Implementation: Realized using Wavect controller with a custom driver board designed in Altium Designer

Methodology
Designed the resonant tank using analytical modeling and frequency domain analysis.
Simulated the converter to study gain characteristics, resonant behavior, and soft-switching range.
Developed a hardware prototype, integrating the power stage, driver circuits, and control board.
Conducted open-loop and closed-loop testing using Chroma DC power supply and electronic load.
Captured key waveforms of resonant currents, voltages, and switching transitions using an oscilloscope and power analyzer.

Results
Verified soft-switching operation across full load range.
Achieved high efficiency (>94%) at rated power.
Demonstrated accurate voltage regulation and reduced THD under closed-loop operation.
Experimental results closely matched simulation outputs, confirming design accuracy and converter reliability.

Applications
On-board and off-board EV battery chargers
Renewable energy storage systems
Bidirectional power flow systems for smart grids and hybrid vehicles
