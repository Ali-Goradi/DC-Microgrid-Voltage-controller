# DC-Microgrid-Voltage-controller

A DC microgrid is still under research and test in laboratory. According to the experimental result from researchers, the efficiency of a DC microgrid is better and it is less complicated when compared to an AC grid. 
In this project, our objective is designing and implementing a PV-based DC microgrid with an energy storage system. A DC microgrid network consists of sources, DC load, and convertors (such as DC/DC boost, DC/DC buck), and AC/DC rectifier. One of the main objectives is to control the voltage from the solar panel with the help of a boost convertor. The other objective is to integrate the PV with the energy storage system (battery), by stabilizing the voltage bus for a certain level of voltage using a DC/DC buck boost bidirectional convertor on the energy storage system’s side. There are different techniques to stabilize the voltage bus. For the battery, we used the Cascade PI controller for the battery while the solar panel is classical PI controller.
The Project can be improved in advance control strategy by decoupling both systems, to reduce the effect between the PV and the Battery.


References:

[1] Modeling and Stability Analysis of a DC Microgrid Employing Distributed Control Algorithm. (2018, June). Retrieved from https://www.researchgate.net/publication/327199258_Modeling_and_Stability_Analysis_of_a_DC_Microgrid_Employing_Distributed_Control_Algorithm 

[2] Advantages and challenges of DC microgrid for commercial building a case study from Xiamen university DC microgrid. (2015, July). Retrieved from https://ieeexplore.ieee.org/abstract/document/7152068

[3] Real-time implementation of four-phase interleaved DC–DC boost converter for electric vehicle power system. (2016, December). Retrieved from https://www.sciencedirect.com/science/article/pii/S0378779616302929

[4] Doft, R. C., & Bishop, R. H. (n.d.). Modern Control Systems (12th ed.).

[5] Curtis D. Johnson (n.d.). Process Control Instrumentation Technology (8th ed.).

[6]  Serborg, Edgar, Mrllichamp, Doyle (n.d). Process Dynamics and Control (3th ed.).

[7] Modeling and Stability Analysis of a DC Microgrid Employing Distributed Control Algorithm. (2018, June). Retrieved from https://www.researchgate.net/publication/327199258_Modeling_and_Stability_Analysis_of_a_DC_Microgrid_Employing_Distributed_Control_Algorithm

[8] Guerrero, J. M., & Vasquez, J. C. (2017, December 31). INTELLIGENT DC MICROGRID LIVING LAB. Retrieved from https://www.et.aau.dk/research-programmes/microgrids/activities/intelligent-dc-microgrid-living-lab/

[9] Mohammad, N. (2013). Parasitic Effects on the Performance of DC-DC SEPIC in Photovoltaic Maximum Power Point Tracking Applications. Retrieved from https://www.researchgate.net/publication/276002414_Parasitic_Effects_on_the_Performance_of_DC-DC_SEPIC_in_Photovoltaic_Maximum_Power_Point_Tracking_Applications/figures?lo=1&utm_source=google&utm_medium=organic
[9] Mohammad, H Rashid. Power Electronics Devices Circuit, and Application (4th edition).



