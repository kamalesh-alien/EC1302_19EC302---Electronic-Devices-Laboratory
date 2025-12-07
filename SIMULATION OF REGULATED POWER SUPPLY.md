# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:


## AC INPUT WAVEFORM:
![WhatsApp Image 2025-12-07 at 15 57 33_5cdd6ebb](https://github.com/user-attachments/assets/2996343b-6709-4361-ad8b-15455d1f5417)



## OUTPUT GRAPH:
![WhatsApp Image 2025-12-07 at 15 57 33_05d42272](https://github.com/user-attachments/assets/a1f56c6d-438b-41a9-82fa-43bb5728a8e2)

## SIGNAL OUTPUT(WITHOUT FILTER)
![WhatsApp Image 2025-12-07 at 15 57 33_83438632](https://github.com/user-attachments/assets/a4b4a1ef-be3d-4408-9b22-01034eed5521)


## SIGNAL OUTPUT(WITH FILTER)
![WhatsApp Image 2025-12-07 at 15 57 34_183f9b90](https://github.com/user-attachments/assets/6695032b-45a8-4323-97d4-ddd4a322360b)




## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
