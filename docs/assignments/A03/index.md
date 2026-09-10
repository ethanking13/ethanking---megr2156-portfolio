## A3: [Parametric and FEA]

# Parametric Design of Aluminum Bar

## Design Requirements

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

## Beam Calculations

The cross-sectional area of the rectangular bar and the length of the bar were determined using the required design parameters.

The direct tension equation was used to determine the maximum length of the bar based on the applied force, cross-sectional area, Young's Modulus, and maximum allowable deflection.

<img width="1590" height="785" alt="Beam Calculations" src="https://github.com/user-attachments/assets/d4e877e8-193c-480a-ac2e-231847a601b2" />

Therefore, the calculated cross-sectional area of the bar is **1 in²**, and the maximum calculated length of the bar is **207 inches**.

---

## CAD Model

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

## Material Selection

The required material for the bar was aluminum. In SOLIDWORKS, I selected **6061-T6 Aluminum** from the available material library.

<img width="945" height="776" alt="6061-T6 Aluminum Material" src="https://github.com/user-attachments/assets/fe034bc7-0a97-43c1-89f7-0ad511599694" />

*Figure 4. 6061-T6 Aluminum selected as the material for the bar.*

---

## Adding a Fixed Geometry

After selecting the material, I added a **Fixed Geometry** fixture to one end of the bar. This prevents the selected end from moving during the simulation and represents the end of the bar being held in place.

The fixed geometry was applied to one end of the bar so that the opposite end could be subjected to the required axial force.


<img width="1282" height="887" alt="Screenshot 2026-09-09 223957" src="https://github.com/user-attachments/assets/9acabf89-ea36-40bf-8543-ae1d04e0913b" />




*Figure 5. Fixed Geometry applied to one end of the aluminum bar.*

---

## Applying the 500 lbf Force

After fixing one end of the bar, I applied a **500 lbf** force to the opposite end. The force was applied to the opposite end of the Fixed Geometry to represent the direct tension loading condition used in the hand calculations.

The applied force was selected as **500 lbf**.


<img width="1496" height="627" alt="Screenshot 2026-09-09 224242" src="https://github.com/user-attachments/assets/6eb10112-1aa6-4d93-be8a-40d9e289ca6e" />



*Figure 6. A 500 lbf axial force applied to the opposite end of the aluminum bar.*

---

## Meshing the Part

After applying the fixed geometry and the **500 lbf** force, the next step was to create a mesh for the bar. The completed mesh was then used for the FEA calculations.

<img width="1652" height="425" alt="Screenshot 2026-09-09 224452" src="https://github.com/user-attachments/assets/158dc036-b407-440d-a156-be78d5127f41" />




*Figure 7. Mesh generated for the aluminum bar before running the FEA simulation.*

After the mesh was generated, the simulation was ready to be run. The FEA results were then used to determine the maximum deflection and von Mises stress of the bar.


## Finite Element Analysis (FEA)

A finite element analysis was performed on the aluminum bar using SOLIDWORKS Simulation. The same loading condition used to generate the bar geometry was applied to the FEA model.

The simulation was used to determine the maximum axial deflection and maximum von Mises stress. The results were then compared with the design requirements.

## FEA Parameters

| Parameter | Value |
|---|---:|
| Applied Load | 500 lbf |
| Young's Modulus | 11,500,000 psi |
| Cross-Sectional Area | 1 in² |
| Bar Length | 207 in |
| Maximum Allowable Deflection | 0.009 in |
| Aluminum Yield Strength | 40 ksi |

---

## Deflection Results

The FEA simulation was run to determine the maximum resultant displacement of the bar.

<img width="1615" height="875" alt="Screenshot 2026-09-09 224920" src="https://github.com/user-attachments/assets/e1257eee-9edb-4afe-b892-b9385c83d5ab" />

The maximum resultant displacement from the FEA was:

**0.01034 in**

The required maximum deflection was **0.009 in**.

---

## von Mises Stress Results

The von Mises stress result was used to determine the maximum stress experienced by the bar during the simulation.

<img width="1617" height="876" alt="Screenshot 2026-09-09 224841" src="https://github.com/user-attachments/assets/9efd5ece-2fc8-4888-8d53-af5ff1f1f243" />

The maximum von Mises stress from the FEA was:

**539.6 psi**

---

## Safety Factor

The yield strength of the 6061-T6 Aluminum used in the simulation was approximately **40,000 psi (40 ksi)**.

The safety factor was calculated using:

\[
SF = \frac{S_y}{\sigma_{max}}
\]

\[
SF = \frac{40,000}{539.6}
\]

\[
SF \approx 74.1
\]

Therefore, the bar passes the **strength requirement** because the maximum von Mises stress of **539.6 psi** is well below the aluminum yield strength of **40,000 psi**.

However, the FEA deflection of **0.01034 in** is greater than the required maximum deflection of **0.009 in**. Therefore, while the bar passes the **strength requirement**, it does **not meet the deflection requirement** based on the FEA results.

---

## FEA Results Summary

| Result | Value | Requirement | Status |
|---|---:|---:|---|
| Maximum Deflection | 0.01034 in | ≤ 0.009 in | Does Not Meet |
| Maximum von Mises Stress | 539.6 psi | < 40,000 psi | Pass |
| Safety Factor | 74.1 | > 1 | Pass |

The FEA indicates that the bar is well within the allowable stress limit but exceeds the maximum allowable deflection. This difference between the FEA and hand calculation will be discussed in the Design Reflection section.
