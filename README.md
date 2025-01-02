# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**

Open Quartus Prime software and create a new project.

Write the Verilog code for the T flip-flop.

Compile the project to ensure there are no syntax errors.

Generate the RTL (Register Transfer Level) schematic to verify circuit connections.

Create a testbench to simulate the functionality of the T flip-flop.

Apply different test cases for T input.

Verify the state transitions based on the characteristic table.

Generate timing diagrams to observe state changes.

Validate the simulation results against the functional table.


**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:Thamizh.S RegisterNumber:24900483
*/
![code](https://github.com/user-attachments/assets/06b8c0cd-e55d-4267-a9be-3032b49cb6e7)

**RTL LOGIC FOR FLIPFLOPS**
![gate](https://github.com/user-attachments/assets/a6ffa4e3-2d77-4313-aace-5d3df1875f08)

**TIMING DIGRAMS FOR FLIP FLOPS**
![wave](https://github.com/user-attachments/assets/fb2de8b0-5fae-4433-9a5e-0f141782a31b)

**RESULTS**





The T flip-flop was successfully implemented in Verilog, and its functionality was validated using the characteristic table and timing diagrams. The results confirm correct toggling and holding behavior based on the input.

