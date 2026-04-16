# LFP Cell Single Particle Modeling

Single Particle Model (SPM) of a 2.5 Ah Lithium Iron Phosphate (LFP).

## Files
* `LFPCaseStudy_ZahidSarigol.slx`: Simulink simulation file.
* `LFP Case Study Zahid Sarigol.pdf`: The final report.
* The png plot files.

## How to Run the Model
1. Open MATLAB.
2. Open the `LFPCaseStudy_ZahidSarigol.slx` file.
4. To simulate, adjust the following blocks:
   * **DC Current Source:** Modify the current value (+/- 0.083 A for C/30, +/- 2.5 A for 1C).
   * **Stop Time:** Set to `3600*30` seconds for C/30 and `3600` seconds for 1C.
   * **Battery Single Particle Block:** Change the Initial Targets State of Charge (SOC) (0 for charging, 1 for discharging).
5. Click **Run**.
6. Double-click the `Terminal Voltages` and `Ampere-hour Throughput` scope blocks.
