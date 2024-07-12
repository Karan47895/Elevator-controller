# Elevator-controller
Design implemented on Altera DE2 FPGA Board using Verilog HDL and FSM architecture.
Considers four elevators, initializing to ground floor and upward direction.
Evaluates current state and elevator inputs on each clock rising edge.
Resets to ground floor on reset signal.
Determines and changes direction based on current state and inputs.
Outputs current floor as signal.
Repeats process on each clock rising edge or reset.
