# DECODER2TO4
# AIM:
To simulate and synthesis decoder using vivado.
# APPARATUS REQUIRED:
vivado 2023.2 software.
# PROCEDURE:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)
# VERILOG CODE:
module decoder(a,b,d);

input a,b;

output [3:0]d;

and g1(d[0],~a,~b);

and g2(d[1],~a,b);

and g3(d[2],a,~b);

and g4(d[3],a,b);

endmodule
![image](https://github.com/vandana9676/DECODER2TO4/assets/165563035/2e07ccaf-9529-46a9-9edb-4ef63011f77f)
# RESULT:
Thus the verilog program for decoder has been simulated and verified successfully.






