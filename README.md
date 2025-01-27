

 Design and Implementation of a 350W Resonant Soft-Switched and Isolated Solar Power Optimizer

 Project Description
This project focuses on minimizing power losses in Solar Power Optimizer (SPO) modules by developing a novel soft-switched converter. Leveraging a flyback-derived topology, the design achieves the following key improvements:

- Reduced Switching Losses and Current Stresses: Full soft-switching operation of all switches and diodes, along with reduced current stresses, leads to improved efficiency and extended component lifespan.
- High Voltage Gain: Achieves a voltage gain of 4–6, requiring fewer turns in the secondary winding compared to traditional flyback topology. This significantly reduces the number of series-connected SPOs needed for high-voltage DC links.
- Enhanced Efficiency: Exceeding 95%, making it ideal for high-performance solar systems.
- PID Mitigation: The isolated design minimizes parasitic paths, reducing potential-induced degradation (PID) in solar panels.

 Key Capabilities
- Sensing and monitoring of input/output voltage and currents.
- Wireless communication using ESP-01 modules.
- Implementation of the Perturb and Observe (P&O) Maximum Power Point Tracking (MPPT) algorithm.
- Over-voltage and over-current protection mechanisms.


 System Ratings
The system is designed to manage PV panels with the following specifications:
- **Maximum Input Voltage**: 50V
- **Output Power Rating**: 350W per SPO module

 Control System and Topology
The system employs the **P&O algorithm** for MPPT. Additionally, a novel control method was implemented to manage overvoltage scenarios during I-V curve scans, effectively controlling both the scan and output voltages.

 
  
 
