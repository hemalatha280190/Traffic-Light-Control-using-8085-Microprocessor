# Traffic Light Control using 8085 Microprocessor
## Aim:
To simulate the operation of a simple traffic light controller using 8085.
## Apparatus Required:
1.	8085 Online Simulator	8085simulator.org or equivalent
2.	PC or Laptop with Internet	Any
3.	Virtual LEDs	Representing traffic lights
## Theory:
1. Traffic signals follow a sequence:
<br>Red (Stop)
<br>Yellow (Get Ready)
<br>Green (Go)
2. LEDs are connected to a port (e.g., Port 01H) to simulate Red, Yellow, Green.
3. Each LED is turned ON/OFF by sending specific bit patterns.
4. Delay is used to simulate real-world time between light transitions.
## Procedure:
1.	Open 8085simulator.org or any online simulator.
2.	Paste the above assembly code in the program window.
3.	Assign Port 01H as output for traffic light (LED display).
4.	Execute the program step-by-step or run in loop.
5.	Observe the LED pattern: RED → YELLOW → GREEN → repeat.
6.	Try changing delay to modify transition speed.
## Program:
## Result:
The traffic light controller was successfully simulated. The output port controlled three LEDs in the sequence Red → Yellow → Green with appropriate delays.


