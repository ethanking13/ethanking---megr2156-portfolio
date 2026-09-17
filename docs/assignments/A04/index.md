# Motor Mount Design

## Objective

The objective of this project is to design a PLA motor mount that can safely support the applied load while satisfying the required bending stress and deflection limits. The mount's cross-sectional geometry will be determined using beam bending equations for both maximum stress and maximum deflection. The final design will be evaluated to ensure that it meets the specified safety factor and performance requirements.

<img width="272" height="165" alt="Screenshot 2026-09-17 001846" src="https://github.com/user-attachments/assets/de78c5c5-7139-4eb0-9ecc-8a81e56c6ea2" />


## Knowns

- **Material:** PLA
- **Elastic Modulus:** 2350 MPa
- **Yield Strength:** 77.4 MPa
- **Maximum Deflection:** 0.30 mm
- **Safety Factor:** 3
- **Applied Force:** 300 N
- **Beam Length:** 27 mm
- **Cross-Section Height:** 22 mm
- **Shaft Diameter:** 6 mm
- **Shaft Length:** 18 mm

## Unknowns

- **Cross-Sectional Area:** A = ?
- **Minimum b Based on Deflection:** b = ?
- **Minimum b Based on Stress:** b = ?

## Feature 1

Before I could start designing the mount, I had to draw a Free-Body Diagram so I can determine forces. Which I could then determine many things

<img width="1963" height="844" alt="IMG_0375" src="https://github.com/user-attachments/assets/a0d88d89-2843-4778-b2ae-ef619dc6351e" />

Once I was able to determine the external forces and Moment I am then able to plug these values into my Stress and Deflection equations

<img width="1332" height="723" alt="IMG_0376" src="https://github.com/user-attachments/assets/aa9835bd-6096-46c0-93d2-cb21ead2e7da" />


## Feature 2

The second feature of the motor mount was designed using the same beam bending analysis approach as Feature 1. The new dimensions and loading conditions were used to determine the required cross-sectional area and evaluate the resulting stress and deflection.

### Knowns

- **Material:** PLA
- **Elastic Modulus:** 2350 MPa
- **Yield Strength:** 77.4 MPa
- **Maximum Deflection:** 0.30 mm
- **Applied Force:** 300 N
- **Beam Length:** 36 mm
- **Cross-Section Height:** 22 mm

### Unknowns

- **Cross-Sectional Area:** A = ?
- **Stress:** ?
- **Deflection:** ?

### Free Body Diagram and Stress and Deflection Calculations

The free body diagram and stress and deflection calculations were used to evaluate the second feature of the motor mount. The full calculations are shown in the image below.


<img width="1305" height="1016" alt="IMG_0377" src="https://github.com/user-attachments/assets/89a4c261-969a-4e9c-86e4-b96dad4d5af6" />


## Final Sketch

The final sketch shows the complete motor mount design with all dimensions included.


<img width="1582" height="956" alt="IMG_0378" src="https://github.com/user-attachments/assets/9805f8d7-238b-497a-92a6-75d53edca4c8" />


## Generated 3D CAD Model

### Figure 1

I first input all of the calculated data and dimensions into the CAD model to ensure that each dimension matched the required values. 

<img width="932" height="416" alt="Screenshot 2026-09-16 232816" src="https://github.com/user-attachments/assets/5f552be6-9fb5-4113-9952-19236353d239" />

Once I got all my data input I was then decided to start the model from the side that touches the wall because building from that orientation was the easiest, Also due to user error I was unable to make the summation symbol be shown for the dimension which shows its what the dimension is.

<img width="570" height="567" alt="Screenshot 2026-09-16 233007" src="https://github.com/user-attachments/assets/f3bc491c-87c2-4ff5-9889-cf31a2e9071d" />

I then extruded to model to the calculated thickness.

<img width="595" height="757" alt="Screenshot 2026-09-16 233014" src="https://github.com/user-attachments/assets/6e0b98c9-fa97-445f-9943-eea47109a591" />

I then created the base that the mount sits on and extruded it to the proper thickness.

<img width="846" height="868" alt="Screenshot 2026-09-16 235834" src="https://github.com/user-attachments/assets/4b1a39db-cd16-40a0-ab34-e090a4b41bd7" />

I then moved into extruding the screw holes and the hole that the mount rest in.

<img width="645" height="583" alt="Screenshot 2026-09-17 001038" src="https://github.com/user-attachments/assets/271a51a1-da4f-4924-8cdc-be27a085f856" />



