# 1. Parametric Design of Aluminum Bar

## 1.1 Design Requirements

The objective of this portion of the project was to parametrically design an aluminum bar subjected to a direct axial load.

The design requirements were:

- Applied force: **300–500 lbf**
- Maximum allowable axial deflection: **0.009 in**
- Young's Modulus: **8.5 × 10⁶–11.5 × 10⁶ psi**
- Material: **Aluminum**

For this design, the maximum applied load of **500 lbf** was selected. A Young's Modulus of **11,500,000 psi** was selected, which is within the required range.

The cross section of the bar was selected as **1 in × 1 in**, resulting in a cross-sectional area of **1 in²**.

### Selected Design Parameters

| Parameter | Symbol | Value |
|---|---|---:|
| Applied Load | `F` | 500 lbf |
| Maximum Deflection | `δmax` | 0.009 in |
| Young's Modulus | `E` | 11,500,000 psi |
| Width | `w` | 1 in |
| Height | `h` | 1 in |
| Cross-Sectional Area | `A` | 1 in² |
| Material | — | Aluminum |

---

## 1.2 Beam Calculations

The cross-sectional area of the rectangular bar and the length of the bar were determined using the required design parameters.

The direct tension equation was used to determine the maximum length of the bar based on the applied force, cross-sectional area, Young's Modulus, and maximum allowable deflection.

<img width="1590" height="785" alt="Beam Calculations" src="https://github.com/user-attachments/assets/d4e877e8-193c-480a-ac2e-231847a601b2" />

Therefore, the calculated cross-sectional area of the bar is **1 in²**, and the maximum calculated length of the bar is **207 inches**.

---

## 1.3 CAD Model

The calculated dimensions and design parameters were implemented in SOLIDWORKS. The model was created parametrically so that the dimensions and calculated length could be controlled using the selected engineering variables.

The parameters used in the CAD model include:

- Young's Modulus
- Maximum allowable deflection
- Applied force
- Width
- Height
- Thickness
- Cross-sectional area
- Bar length

First, I entered all of the known values into the **Equations** section of SOLIDWORKS. This allows the length of the bar to change when the applied load, material properties, cross-sectional dimensions, or allowable deflection are changed.

<img width="212" height="187" alt="SOLIDWORKS Equations" src="https://github.com/user-attachments/assets/aed905ca-aeb4-40ba-b673-f4fbb82650bd" />

*Figure 1. Parameters entered into the SOLIDWORKS Equations section.*

Next, I created the **1 in × 1 in** face of the bar using the specific Base (b) and Height (h) parameters. These parameters are controlled by the equations, as shown by the summation symbols.

<img width="352" height="296" alt="SOLIDWORKS Base and Height" src="https://github.com/user-attachments/assets/5296c86a-776b-453a-97fc-2de8dba05d15" />

*Figure 2. Base and height parameters used to create the 1 in × 1 in cross section.*

Next, I extruded the bar's face to the calculated length of **207 inches**.

<img width="268" height="228" alt="SOLIDWORKS Extrusion Length" src="https://github.com/user-attachments/assets/f1f08639-b106-4931-bcdd-c33253ff0b42" />

<img width="1497" height="842" alt="SOLIDWORKS Bar Model" src="https://github.com/user-attachments/assets/72ca8b5e-efdc-4ee4-93de-b01b013189a3" />

*Figure 3. Bar extruded to the calculated length of 207 inches.*

---

## 1.4 Material Selection

The required material for the bar was aluminum. In SOLIDWORKS, I selected **6061-T6 Aluminum** from the available material library.

<img width="945" height="776" alt="6061-T6 Aluminum Material" src="https://github.com/user-attachments/assets/fe034bc7-0a97-43c1-89f7-0ad511599694" />

*Figure 4. 6061-T6 Aluminum selected as the material for the bar.*

The material was assigned to the bar before setting up the FEA simulation. The material properties are important because they determine how the bar responds to the applied load, including its stress and deformation.

---

## 1.5 Adding a Fixed Geometry

After selecting the material, I added a **Fixed Geometry** fixture to one end of the bar. This prevents the selected end from moving during the simulation and represents the end of the bar being held in place.

The fixed geometry was applied to one end of the bar so that the opposite end could be subjected to the required axial force.


<img width="1282" height="887" alt="Screenshot 2026-09-09 223957" src="https://github.com/user-attachments/assets/9acabf89-ea36-40bf-8543-ae1d04e0913b" />


![Fixed Geometry](images/fixed_geometry.png)

*Figure 5. Fixed Geometry applied to one end of the aluminum bar.*

---

## 1.6 Applying the 500 lbf Force

After fixing one end of the bar, I applied a **500 lbf** force to the opposite end. The force was applied in the longitudinal direction of the bar to represent the direct tension loading condition used in the hand calculations.

The applied force was selected as **500 lbf**, which is the maximum value within the required loading range of 300–500 lbf.


<img width="1496" height="627" alt="Screenshot 2026-09-09 224242" src="https://github.com/user-attachments/assets/6eb10112-1aa6-4d93-be8a-40d9e289ca6e" />


![500 lbf Force](images/500_lbf_force.png)

*Figure 6. A 500 lbf axial force applied to the opposite end of the aluminum bar.*

---

## 1.7 Meshing the Part

After applying the fixed geometry and the **500 lbf** force, the next step was to create a mesh for the bar. Meshing divides the bar into many smaller elements that SOLIDWORKS uses to calculate the stress and displacement throughout the model.

I generated the mesh using the SOLIDWORKS Simulation mesh settings. The completed mesh was then used for the FEA calculations.

<img width="1652" height="425" alt="Screenshot 2026-09-09 224452" src="https://github.com/user-attachments/assets/158dc036-b407-440d-a156-be78d5127f41" />


![SOLIDWORKS Mesh](images/mesh.png)

*Figure 7. Mesh generated for the aluminum bar before running the FEA simulation.*

After the mesh was generated, the simulation was ready to be run. The FEA results were then used to determine the maximum deflection and von Mises stress of the bar.


## Finite Element Analysis (FEA)

A finite element analysis was performed on the aluminum bar using SOLIDWORKS Simulation. The same loading condition used to generate the bar geometry was applied to the FEA model.

The simulation was used to determine the maximum axial deflection and maximum von Mises stress. The results were then compared with the design requirements.

## 2.1 FEA Parameters

| Parameter | Value |
|---|---:|
| Applied Load | 500 lbf |
| Young's Modulus | 11,500,000 psi |
| Cross-Sectional Area | 1 in² |
| Bar Length | 207 in |
| Maximum Allowable Deflection | 0.009 in |
| Aluminum Yield Strength | 40 ksi |

---

## 2.2 Deflection Map

A resultant displacement plot was generated in SOLIDWORKS Simulation to determine the maximum deflection of the bar.

The FEA produced a maximum resultant displacement of:

$$
\boxed{\delta_{FEA} = 0.01034\text{ in}}
$$

The maximum allowable deflection specified for the design was:

$$
\boxed{\delta_{allowable} = 0.009\text{ in}}
$$

The FEA result is greater than the allowable deflection:

$$
0.01034\text{ in} > 0.009\text{ in}
$$

Therefore, based on the FEA result, the bar exceeds the specified maximum deflection by:

$$
0.01034-0.009=0.00134\text{ in}
$$

### SOLIDWORKS Deflection Map

![FEA Deflection Map](images/deflection_map.png)

*Figure 3. SOLIDWORKS FEA resultant displacement map showing a maximum displacement of 0.01034 in.*

---

## 2.3 von Mises Stress Map

A von Mises stress plot was generated to determine the maximum stress in the aluminum bar under the applied 500-lbf load.

The maximum von Mises stress obtained from the FEA was:

$$
\boxed{\sigma_{vM,max}=539.6\text{ psi}}
$$

Converting the stress to ksi:

$$
539.6\text{ psi}=0.5396\text{ ksi}
$$

### SOLIDWORKS von Mises Stress Map

![FEA von Mises Stress Map](images/von_mises_stress.png)

*Figure 4. SOLIDWORKS FEA von Mises stress map showing a maximum stress of 539.6 psi.*

---

## 2.4 Stress and Safety Factor

The specified yield strength of the aluminum was:

$$
S_y=40\text{ ksi}
$$

or:

$$
S_y=40,000\text{ psi}
$$

The safety factor was calculated using:

$$
SF=\frac{S_y}{\sigma_{max}}
$$

Substituting the FEA maximum von Mises stress:

$$
SF=\frac{40,000}{539.6}
$$

$$
\boxed{SF=74.1}
$$

The maximum von Mises stress is significantly below the 40-ksi yield strength of the aluminum. Therefore, the design **passes the strength requirement** with a safety factor of approximately **74**.

---

## 2.5 FEA Results Summary

| Result | Value | Requirement | Status |
|---|---:|---:|---|
| Maximum Deflection | 0.01034 in | ≤ 0.009 in | Does Not Meet |
| Maximum von Mises Stress | 539.6 psi | < 40,000 psi | Pass |
| Safety Factor | 74.1 | > 1 | Pass |

The FEA indicates that the bar is well within the allowable stress limit but slightly exceeds the maximum allowable deflection. This difference between the FEA and hand calculation will be discussed in the Design Reflection section.
