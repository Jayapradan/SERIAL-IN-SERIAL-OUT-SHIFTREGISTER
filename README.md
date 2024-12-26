## NAME: JAYAPRADAN

## REG NO: 24900886

## EX NO 10 : SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO SHIFT REGISTER**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**PROCEDURE**

/* write all the steps invloved */

**PROGRAM**

![WhatsApp Image 2024-12-26 at 11 47 30_f0dc382e](https://github.com/user-attachments/assets/ae944d26-9e1e-43b8-b33d-62583aeeccc4)


**RTL LOGIC FOR SISO**

![WhatsApp Image 2024-12-26 at 11 47 30_2090b7fb](https://github.com/user-attachments/assets/89fb1d6d-4dab-480f-8ece-5f95de2db8e4)



**TIMING DIGRAMS FOR SISO**

![WhatsApp Image 2024-12-26 at 11 47 31_fc5b7f8f](https://github.com/user-attachments/assets/32499cc7-fdba-47dc-9b96-a56d68c15d69)

**RESULTS:**

Thus to implement SISO Shift Register using verilog and validating their functionality using their functional tables done successfully.
