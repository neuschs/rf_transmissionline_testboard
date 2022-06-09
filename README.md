# rf_transmissionline_testboard
A simple PCB designed according to JLC23313 layer stackup 

There are many different impedance controlled transmission lines, with the most common Zo = 50 Ohm / Zdiff = 100 Ohm

- Coplanar Waveguide (Single / Differential)

- Microstrip (Single / Differential)

- Stripline (Single / Differential):

  A impedance controlled Via and a set of differential vias gets the stripline up to a coplanar waveguide to the sma connectors
  For a future version vertical SMA mounts would be better to avoid vias where the goal was to proof impedance control calculations.
 
- 90° track (as Coplanar Waveguide)

  I put this track on the pcb to measure the effects of 90° bends on transmission lines.

- 50% top 50% bottom track connected by 50 ohm via:
 to verify impedance of via if the coplanar waveguide calculations are all correct.

# Parameters @ production:

Base Material: FR-4\
Layers: 4\
Dimension: 100 mm* 100 mm\
PCB Qty: 5\
Product Type: Industrial/Consumer electronics\
Different Design: 1\
Delivery Fomat: Single PCB\
PCB Thickness: 1.6\
Impedance: yes JLC2313\
PCB Color: Green\
Silkscreen: White\
Surface Finish: HASL(with lead)\
Deburring/Edge rounding: No\
Outer Copper Weight: 1\
Inner Copper Weight: 0.5\
Gold Fingers: No\
Flying Probe Test: Fully Test\
Castellated Holes: no\
Remove Order Number: Yes\
Min hole size/diameter:0.2/0.45mm\
4-Wire Kelvin Test:No\
Material Type:FR4-Standard Tg 130-140C\
Paper between PCBs:No\
Appearance Quality:IPC Class 2 Standard\
Confirm Production file:Yes

# Credits
I mostly calculated the values with https://www.maartenbaert.be/alterpcb/tlinesim/ which has quite accurate interpretation of all different parts of the pcb.
After comparison, this tool was nearly exactly the same to the manufacturer (JLCPCB) regarding a 50 Ohm transmission line with JLC2313 stackup.

