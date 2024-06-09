Design goals:  

LDO:  [lt3041](https://www.analog.com/en/products/lt3041.html)
   1. High PSRR as to reduce powerpack boost converter noise
   2. Low dropout to extend powerpack life (current 310mv)
   3. Low RMS noise
   4. 1A output capability
   5. DC 6.2 volt


Power Delivery: [stusb4500](https://www.st.com/en/interfaces-and-transceivers/stusb4500.html)
   1. Power delivery 3 capability to reduce power consumption.
   2. PD2 will be set to 9 volt, loss ~50%
   3. PD3 will be set to 6.6v volt, loss <10%.    

PCB Design:

![board image](assets/bio-power-2.png?raw=true "Board Image")

Schematics:

![schematics](assets/schematic.png?raw=true "Schematic")
