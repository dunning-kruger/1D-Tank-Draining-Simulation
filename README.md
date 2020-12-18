# 1D-Tank-Draining-Simulation
Using MATLab to simulate fluid height in a 1D tank with both an inlet and outlet.

## Objective
Fill and/or drain water from a tank to maintain a user specified tank height. The simulation implements a GUI to manage the discrete-event control system. The GUI has various buttons and knobs that allow the user to change the state of the system and control the response magnitude. 

This is accomplished by using MATLab's app designer timer function to calculate tank height over a user specificed time step.

## Initial Conditions
- Tank Height: 60 cm
- Desired Height: 0 cm
- Maximum Tank Height: 100 cm
- High Level Warning Height: 20 cm
- Low Level Warning Height: 90 cm
- Inlet Knob Position: 0 cm/s
- Outlet Knob Position: 0 cm/s
- Time step: 1 s