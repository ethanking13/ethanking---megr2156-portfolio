# A10 – Lead Screw Translating System

## Objective

Design and build a mechanically driven tensile tester capable of applying up to 2 kN of tensile force with a controllable crosshead speed of 1–50 mm/min. The design will use a lead screw mechanism to provide consistent loading, proper alignment, and safe operation while maintaining a safety factor of 4.

## Leadscrew Diameter: Ethan King
Here is my selected [Leadscrew](https://www.mcmaster.com/99030a073/) Below you can find the information on how I decided on which one to choose.
## 1. Minimum Lead Screw Diameter

### 1.1 Knowns and Unknowns
- **Knowns:**
  - Maximum tensile load: 2 kN
  - Number of lead screws: 2
  - Safety factor: 4
- **Unknown:**
  - Minimum lead screw diameter (d)

<img width="3024" height="4032" alt="IMG_6865" src="https://github.com/user-attachments/assets/028bfd51-0413-4e10-8f0b-6a39570d1630" />

---

## 2. Lead Screw Rotational Speed

### 2.1 Knowns and Unknowns
- **Knowns:**
  - Minimum crosshead speed: 1 mm/min
  - Maximum crosshead speed: 50 mm/min
- **Unknown:**
  - Minimum and maximum rotational speed (RPM)

<img width="3024" height="4032" alt="IMG_6866" src="https://github.com/user-attachments/assets/09f75228-9621-43c8-8068-a3c5c4e03e0c" />


---

## 3. Maximum Lead Screw Torque: 

### 3.1 Knowns and Unknowns
- **Knowns:**
  - Maximum tensile load: 2 kN
  - Number of lead screws: 2
  - Lead screw lead: (Insert value)
  - Thread friction coefficient: (Insert value)
- **Unknown:**
  - Maximum torque required per lead screw

<img width="3024" height="4032" alt="IMG_6867" src="https://github.com/user-attachments/assets/fcb66f69-be4f-41a8-a6cd-6487b37f7d45" />

---

## 4. Lead Screw Selection

Based on the calculated minimum diameter, rotational speed range, and maximum required torque, a suitable lead screw was selected.
Total Max Load:                         2 kN
Split Load (2 Screws):                 1 kN
Safety Factor:     	                4
Height:                                 36 Inches
Crosshead Speed:                0.03937–1.9685 in/min
Friction Coefficient:                 0.15 static
Minimum Diameter:                 0.19777 Inches
Range of Rotational Speed:         0.1575–7.874 RPM
Maximum Torque:                  2.93 N·m = 2.161 lb-ft

 Based on the work above here is my selected [Leadscrew.](https://www.mcmaster.com/99030a073/)

 ## 5. Nut and Flange Selection: Josef Chalala

### 5.1 Knowns and Unknowns

**Knowns:**
- Total tensile load: 2,000 N
- Number of lead screws: 2
- Load per lead screw/nut: 1,000 N
- Safety factor: 4
- Design load per nut: 4,000 N


**Unknowns:**
- Thread bending stress
- Required number of engaged threads (if being verified)

## Solve
<img width="658" height="790" alt="Screenshot 2026-11-12 013631" src="https://github.com/user-attachments/assets/a0ba83b7-2fa3-4a43-8276-ebd5e397b8a5" />


### 5.5 Nut and Flange Selection

Based on the thread bending stress analysis, a C93200 bronze nut/flange was selected. The design uses a 0.500-inch thread engagement length with four engaged threads to support the required tensile load while maintaining a safety factor of 4.

**Selected Nut/Flange:** 
[Carbon Steel Flange](https://www.mcmaster.com/95082a643/)
[Lead Screw Nut](https://www.mcmaster.com/95072a331/)

## 6. Crosshead Design: Juan Martinez

### 6.1 Beam Stress and Strength Analysis

#### 6.1.1 Knowns and Unknowns

**Knowns:**
- Maximum tensile load: 2,000 N
- Number of lead screws: 2
- Load per lead screw: 1,000 N
- Safety factor: 4
- Maximum allowable deflection: 0.1 mm


**Unknowns:**
- Required crosshead dimensions
- Maximum bending stress
- Minimum required cross-section

## Solved
<img width="624" height="696" alt="Screenshot 2026-11-12 015923" src="https://github.com/user-attachments/assets/d4897bf7-8a03-41b9-b0b4-a411025b4c86" />


---

### 6.2 Beam Deflection Analysis

#### 6.2.1 Knowns and Unknowns

**Knowns:**
- Applied load: 2,000 N
- Maximum allowable deflection: 0.1 mm

**Unknowns:**
- Maximum crosshead deflection
- Required moment of inertia
- Whether the selected crosshead meets the deflection requirement

## Solved
<img width="623" height="703" alt="Screenshot 2026-11-12 020134" src="https://github.com/user-attachments/assets/8d7ac121-1768-470b-a201-b73d913de221" />


---

### 6.3 Crosshead Multiview Sketch

A multiview sketch was created to communicate the overall geometry and mounting features of the crosshead.

<img width="557" height="737" alt="Screenshot 2026-11-12 020155" src="https://github.com/user-attachments/assets/abdd395b-8c3e-490d-b483-59ac59451555" />

---

### Tabulating Cost
| Name | Quantity | Item Number | Cost Per | Total Cost |
|---|---|---|---|---|
|Leadscrew |2 |1 |$51.44 |$102.88 |
| Nut|2 |2 |$61.99 |$123.98 |
|Flange |2 |3 |$94.44 |$188.88 |
|Framing | 1|4 |$150 |$150 |

### Parametric Model
<img width="634" height="406" alt="Screenshot 2026-11-12 021024" src="https://github.com/user-attachments/assets/2e26cfeb-44f9-47a1-ba7e-a6112ec55081" />
<img width="486" height="441" alt="Screenshot 2026-11-12 021034" src="https://github.com/user-attachments/assets/befcca79-4889-4582-850c-294f3d8bdd21" />

### Lesson Learned

I learned the importance of considering both strength and deflection when designing a mechanical system. Selecting components requires more than ensuring they can withstand the applied load; their dimensions, material properties, and safety factors must also be considered. Through this project, I gained a better understanding of how lead screw diameter, rotational speed, torque, and crosshead geometry affect the overall performance and reliability of a tensile testing machine. Spent about 4 Hours.

# Model
