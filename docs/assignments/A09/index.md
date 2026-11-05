# A9 – Pulleys

## Objective
The objective of this project is to design a pulley system capable of transferring power between two parallel shafts with a center distance of 4–6 inches. The system will feature two 3-inch diameter pulleys operating at 1,000–2,000 RPM with a static belt tension of 4–6 lbf. The pulleys will be manufactured using aluminum, ABS, or steel, with appropriate groove geometry and shaft diameters selected to meet design and manufacturing requirements. The final design must achieve a minimum factor of safety of 3 to ensure sufficient strength, durability, and reliable operation.


<img width="500" height="141" alt="Screenshot 2026-11-04 164215" src="https://github.com/user-attachments/assets/5bb2a93a-db6b-4340-a1f7-0c699775a710" />


## Belt:
### Knowns
- **Pulley Center Distance:** 4 in
- **Static Belt Tension:** 4 lbf
- **Pulley Diameter:** 3 in
- **Rotational Speed:** 1000 RPM
- **Factor of Safety:** 3
- **Pulley Material:** Steel
- **Belt Yield Strength:** 3.25 MPa
- **Strain:** 20%
### Unknowns
- **Belt Forces:** F1 and F2
- **Belt Diameter:** 
- **Belt Circumference:** 
- **Belt Selection:** 
### Freebody Diagram

<img width="1959" height="889" alt="IMG_0432" src="https://github.com/user-attachments/assets/8ec6b2f5-aff8-4b1b-afa2-7e5474e87cbe" />
### Symbolic Solutions

<img width="745" height="1031" alt="IMG_0433" src="https://github.com/user-attachments/assets/c0e56759-1af4-466f-91aa-0d14e66338ae" />

### Numerically Solved
<img width="917" height="1138" alt="IMG_0434" src="https://github.com/user-attachments/assets/1996ec75-398c-4a5c-b89e-fff5b6d705ba" />

### Suitable Belt
This belt was chosen from McMaster which met all the criteria that I solved for
<img width="822" height="458" alt="Screenshot 2026-11-05 003117" src="https://github.com/user-attachments/assets/2e186325-eb21-4ae4-8b8b-d241dda87fd3" />


[Link to belt here!](https://www.mcmaster.com/3044K606-3044K193/)

## Shaft:
### Knowns

- **Pulley Center Distance:** 4 in
- **Static Belt Tension:** 4 lbf
- **Pulley Diameter:** 3 in
- **Rotational Speed:** 1000 RPM
- **Factor of Safety:** 3
- **Pulley Material:** Steel
- **Belt Yield Strength:** 3.25 MPa
- **Strain:** 20%
- **Belt Force (F1):** 7.668 lbf
- **Belt Force (F2):** 0.332 lbf
- **Belt Diameter (Db):** 0.249 in
- **Belt Cross-Sectional Area (Ab):** 0.0488 in²
- **Belt Circumference:** 20.414 in
- **Shaft Material:** 1060 Steel
- **Shaft Yield Strength (Sy):** 98,200 psi
### Unknowns
- **Shaft Tension:** 
- **Shaft Torque:** 
- **Minimum Shaft Diameter:** 
### Freebody Diagram
<img width="857" height="602" alt="IMG_0435" src="https://github.com/user-attachments/assets/6b7b87b8-70ac-46e6-a9f6-e7f1104081b1" />

### Symbolic Solutions
<img width="987" height="766" alt="IMG_0436" src="https://github.com/user-attachments/assets/c580f1ab-d264-43e9-bf91-52987513114f" />

### Numerically Solved
<img width="775" height="1030" alt="IMG_0437" src="https://github.com/user-attachments/assets/42c9f80f-3294-404c-89d3-80cfe2769d0f" />

## Journal Bearing:
### Knowns

- **Pulley Center Distance:** 4 in
- **Static Belt Tension:** 4 lbf
- **Pulley Diameter:** 3 in
- **Rotational Speed:** 1000 RPM
- **Factor of Safety:** 3
- **Pulley Material:** Steel
- **Belt Yield Strength:** 3.25 MPa
- **Strain:** 20%
- **Belt Force (F1):** 7.668 lbf
- **Belt Force (F2):** 0.332 lbf
- **Belt Diameter (Db):** 0.249 in
- **Belt Cross-Sectional Area (Ab):** 0.049 in²
- **Belt Circumference:** 20.414 in
- **Shaft Material:** 1060 Steel
- **Shaft Yield Strength (Ssy):** 98,200 psi
- **Power:** 0.175 hp
- **Shaft Torque:** 11.004 in·lbf
- **Shaft Diameter:** 0.1196 in
- **Bearing Clearance:** 0.005 in
- **Bearing Length:** 1 in

### Unknowns

- **Bearing Thickness:** 
- **Bearing Pressure:** 
- **Linear Velocity:** 
- **PV Rating:** 
- **Bearing Material:** 

### Freebody Diagram
<img width="710" height="468" alt="IMG_0440" src="https://github.com/user-attachments/assets/2b087858-f58e-46fc-800a-e45b374acc45" />

### Symbolic Solution
<img width="856" height="923" alt="IMG_0439" src="https://github.com/user-attachments/assets/ad2ca721-058c-44a5-87ee-a231e0147f97" />

### Numerically Solved
<img width="1136" height="1063" alt="IMG_0438" src="https://github.com/user-attachments/assets/a1fcbdd3-799d-47f3-b73c-82899bfa066d" />

## Frame:
For the frame design, I wanted something similar to the appendix that was listed in the assignment. And it was a very cheap and conventional design that wouldn't interfere with the pulleys or the belt.
<img width="1527" height="925" alt="IMG_0441" src="https://github.com/user-attachments/assets/9aa77c95-97bd-4f09-9994-e6baeb4f7987" />

## Lessons Learned:
I learned that bearing selection involves more than simply matching the bearing to the shaft diameter. Factors such as bearing pressure, linear velocity, clearance, and PV rating must also be considered to ensure the bearing can support the applied loads while minimizing friction and wear during operation.
