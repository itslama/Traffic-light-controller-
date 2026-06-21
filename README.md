# Traffic-light-controller-
Tools: Verilog HDL · Active-HDL
A digital logic design project implementing a traffic light controller in Verilog HDL. The system manages traffic flow at an intersection with a main road, side road, and turning lane using four traffic lights (Main1, Main2, Side, Turn), each represented by a 3-bit signal for red, yellow, and green states.
The controller is built around a Finite State Machine with six states: Green_Main, Yellow_Main, Green_Turn, Yellow_Turn, Green_Side, and Yellow_Side. A timer module controls how long each state stays active before transitioning, and a reset signal initializes the system to Green_Main.
Built with: Verilog HDL
Modules: State Transition · Timer · Traffic Light Output
Features: FSM-based state control · Clock-driven transitions · Reset functionality · Multi-lane intersection logic · Simulation-verified with rst/clk test cases
