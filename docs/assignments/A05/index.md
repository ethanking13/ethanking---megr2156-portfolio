# A5 – [Bracket Design]


## Objective

The objective of this assignment is to design a structural component using principles of statics and solids. Normal stress, bending stress, and stiffness equations will be used to calculate the required dimensions of the component. Free body diagrams, calculations, sketches, and multiview drawings will be used to document the design process. The process will also include documenting mistakes, revisions, and lessons learned throughout the assignment.

## Initial Design

<img width="817" height="377" alt="Screenshot 2026-09-23 213235" src="https://github.com/user-attachments/assets/f8f0fcf5-966a-40a2-9118-88862ea1ec16" />

## Bracket Concept

<img width="812" height="486" alt="Screenshot 2026-09-23 233535" src="https://github.com/user-attachments/assets/38d79270-7a4c-4f89-894f-bd3789b71f16" />


---

For this assignment, I was given specific parameters and requirements that I had to follow. I was also provided with data to help guide me in determining the necessary dimensions and solving for the required lengths. I decided to use an applied force of **800 lbf** and a **safety factor of 4** for my design. And since the strap is represented by 2F we must do 800 divided by 2 = 400 which will be used later.

## Material

For this assignment, I was given the choice of Aluminum 6061-T6, Steel (ASTM A36), or Titanium (Ti-6Al-4V). I decided to use **Aluminum 6061-T6** because it is widely available and generally more economical and accessible compared to titanium. Its availability also makes it a practical choice for a component that may need to be manufactured or replaced easily.

**Material: Aluminum 6061-T6**

Elastic Modulus:
E= 68.9Gpa or 9,992,000 psi

Yield Strength:
Sy = 276Mpa or 40,023 psi

## Feature Analysis

For each feature, I will create a free body diagram and perform a strength analysis to determine the required dimensions. The reaction forces from one feature will be used as the applied loads for the following feature until reaching the feature that connects to the T-beam. Each analysis will include the known values, unknowns, assumptions, free body diagram, algebraic solution, and numerical solution. The design process and results will be documented below with the corresponding calculations, diagrams, and images.

## Feature A
<img width="191" height="97" alt="Screenshot 2026-09-24 014057" src="https://github.com/user-attachments/assets/cd7211f5-aea1-4a4e-9675-759be3902f69" />
<img width="1689" height="1140" alt="IMG_0386" src="https://github.com/user-attachments/assets/fe465ef5-d5f5-421a-8a69-6904f7671af9" />


## Feature B
<img width="78" height="80" alt="Screenshot 2026-09-24 014101" src="https://github.com/user-attachments/assets/1bd7287e-56d6-4eb6-8547-a617d168f245" />
<img width="1409" height="1014" alt="IMG_0387" src="https://github.com/user-attachments/assets/5596ac75-61fa-4e55-a729-9a85ce6b21a2" />


## Feature C
<img width="120" height="64" alt="Screenshot 2026-09-24 014106" src="https://github.com/user-attachments/assets/026ee5f7-5beb-47e5-b74d-56b666a0faa2" />
<img width="1174" height="1096" alt="IMG_0388" src="https://github.com/user-attachments/assets/d07df98c-187e-4fd1-b086-c7d9ba69ed46" />



## Feature D
<img width="40" height="52" alt="Screenshot 2026-09-24 014109" src="https://github.com/user-attachments/assets/b242c84b-fe71-4fd9-b5c1-bd6c226fc1a5" />
<img width="1172" height="1060" alt="IMG_0389" src="https://github.com/user-attachments/assets/286dbbb2-4e4b-4a0c-810c-ac4751e45475" />



## Feature E
<img width="54" height="67" alt="Screenshot 2026-09-24 014113" src="https://github.com/user-attachments/assets/3681ff5a-6ed1-4d69-9948-090c468fe2d1" />
<img width="1330" height="1138" alt="IMG_0390" src="https://github.com/user-attachments/assets/3440b6c9-8018-4e62-ac42-d76635858fcd" />


## Stress Drawing

<img width="1644" height="1186" alt="IMG_0391" src="https://github.com/user-attachments/assets/affb0162-921c-41db-8b41-003d46c2b1c2" />


## Stiffness Drawing
<img width="1727" height="1194" alt="IMG_0392" src="https://github.com/user-attachments/assets/1eb58dd4-d9c0-43da-9227-1e3fc853c809" />


## Lesson Learned
### Governing Failure Mode
Each calculation either, stress or stiffness governed one another. Every value was higher than the other.

### Error propagation
One value that carried into a later feature was the applied force. The force diagram showed a rope with two forces, so I may have needed to use \(2F\) instead of \(F\). If I used the wrong value, it would affect the stress and deflection calculations later. I caught this when checking my force diagram and calculations.


### Assumption sensitivity
I assumed the part was made of aluminum. If a stronger material was used, the part could potentially be made smaller while still supporting the load because the stronger material could handle more stress due to its properties.
