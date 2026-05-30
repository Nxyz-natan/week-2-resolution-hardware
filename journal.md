# LED Chaser

[Preface] I'm building a LED chaser that powers either LED and blinks 
automatically using a transistor-based astable multivibrator.

## May 26 - Circuit and PCB Design

Today I worked on the circuit in Falstad and then moved on to KiCad 
for the schematic and PCB.

I found inspiration from a 3-LED chaser circuit online and simplified 
it down to 2 transistors and 2 LEDs. The circuit works by using two 
NPN transistors that alternate switching on and off, controlled by RC 
timing components  resistors and capacitors that charge and discharge 
to control the timing of each blink.

My browser crashed mid-way through building the circuit in Falstad and 
I lost my progress, so I had to redo it from scratch. The second time 
went faster since I already understood the circuit.

Moving to KiCad was the hardest part. Converting the Falstad circuit 
into a proper schematic was tricky since I wasn't used to the process. 
I had to look over the connections multiple times and cross-check with 
the original circuit to make sure everything was wired correctly.

For the PCB I used a Kirby wearing a hat as the board outline shape and 
added silkscreen art to give it personality. I placed the components 
inside the outline and routed all the traces.

Resources I used:
- [ElecCircuit 3 LED Chaser](https://www.eleccircuit.com/3-led-chaser-circuit-using-transistor/)
- [Pinterest inspiration](https://ca.pinterest.com/pin/4855512095654085/)

### Time Spent: 2 Hours
