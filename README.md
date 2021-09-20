# Transistor-Curve-Tracer
Design of a transistor curve tracer consisting of a custom voltage step generator and voltage ramp generator

Full circuit:

![image](https://user-images.githubusercontent.com/45322860/133713383-8a0b94c3-d343-4988-be49-845a4c71da94.png)

To create a trace, a stair-step waveform was applied to the gate of the MOSFET. Drain current was obtained from the voltage ramp using a current mirror. The fall time of the voltage ramp was increased to prevent drain current overshoot. It ended up being essentially a triangle function.

Stair-Step             |  Triangle
:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/45322860/133946902-f68c712c-5c36-4af9-bd27-5132580839f1.png)  |  ![image](https://user-images.githubusercontent.com/45322860/133946925-b38dcd3f-8895-4e0d-ba61-cd76fad2f543.png)

Trace:

![image](https://user-images.githubusercontent.com/45322860/133713415-2346186a-376f-41bc-808d-cc6a0ce96f06.png)
