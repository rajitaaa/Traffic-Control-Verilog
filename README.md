# Traffic-Control-Verilog


The project shows how a 4-way junction traffic light works and the lights at every junction change colours with time (depending on clock cycles).
The north and south lights are in sync with each other and opposite to the east and west lights.

HOW TO USE THE LOGISIM CIRCUIT: (LogisimTraffic.circ) 

Our logisim circuit is a simulation of a 4 way traffic control system, where the north and south traffic lights work together and the east and west lights work together.

The circuit doesn't require any manual input and works entirely on clock pulses.

To run the circucit, first go to simulation and reset the simulation and then enable the clock ticks. The frequency of the clock can be adjusted.
The traffic lights change colour according to the clock pulses.

VERILOG:
There are two verilog files where the VerilogBM is the behavioral model code and the VerilogDM is the data flow model code. 
The Verilog.vcd file is the generated wave form.

