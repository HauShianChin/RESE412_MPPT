# RESE412_MPPT

MPPT PCB design in Simulink and Altium Designer 

## Final RESE412 assignment 1.pdf

This report, I explored the sizing of a nanogrid and a microgrid, performing a topology analysis. The analysis compares a community of individual nanogrids, with the more traditional method of microgrid design. Individual household power systems operating independently, versus a collective microgrid approach will be discussed.

When both the individual nanogrid and microgrid topologies are designed and simulated, I observed the losses within each topology to ascertain the efficiency of the systems. This information, along with the financial cost of the system will allow me to make a recommendation to a community as to which topology will be more economically viable in the long term.

## RESE412 assignment 2 demand side management.pdf

In report, I will be building on the previous assignment's model to improve the microgrid system with control. Additionally, I will be implementing demand side management (DSM) using a single thermostatically controlled load (water heater) in each house using Simulink. I will revisit the stand-alone PV/battery system and see if I can reduce the capital cost of the solution.

The aim is to shift the water heater load to a time that better suits PV power production. With this shift in load, I should be able to reduce your battery storage and in theory reduce the capital cost of the microgrid solution (ignoring the cost of control infrastructure). Another constraint is that the water reaches “T High WH” at least once a day (T High WH can be found in the Simulink model, ideally its 60 degrees, However, set a little lower in a couple of the houses). This is to ensure bacteria doesn’t build up in the water heater of the Simulink model.

## MPPT assignment 3 412 final and proofread.pdf

A maximum power point tracker (MPPT) is a device that you will see regularly in household renewable energy systems. It manages the output of the solar panels, typically incorporating a battery management system, sometimes even coupled with an inverter. The MPPT dynamically alters the impedance seen by the photovoltaic (PV) panels. This is particularly advantageous in cloudy conditions or if the load is changing regularly. In this project, I will be designing and building an MPPT that will connect to two 10W polycrystalline panels. Students will test their MPPT against a system which does not have any control in order to determine the success of the MPPT controller. 
