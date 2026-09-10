# A3 – [Parametric and FEA]

## Outline
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

# Beam Calculations

The cross-sectional area of the rectangular bar and the Length of the bar



<img width="1590" height="785" alt="IMG_0358" src="https://github.com/user-attachments/assets/d4e877e8-193c-480a-ac2e-231847a601b2" />



Therefore, the calculated area of the Bar is **1 in²**. And maximum length of the bar is: **207 inches**

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

First I plugged every known into the Equations section, This allows the length of the bar to change when the applied load, material properties, cross-sectional dimensions, or allowable deflection are changed.

<img width="212" height="187" alt="Screenshot 2026-09-09 223311" src="https://github.com/user-attachments/assets/aed905ca-aeb4-40ba-b673-f4fbb82650bd" />


Then, I made the 1x1 face of the beam using my specific Base(b) and Height(h) parameters, Which can be seen that they are being used by the Summation Symbol

<img width="352" height="296" alt="Screenshot 2026-09-09 223242" src="https://github.com/user-attachments/assets/5296c86a-776b-453a-97fc-2de8dba05d15" />

Next, I extruded the Beams face to the correct length that was calculated of **207 inches**

<img width="268" height="228" alt="Screenshot 2026-09-09 223423" src="https://github.com/user-attachments/assets/f1f08639-b106-4931-bcdd-c33253ff0b42" />

<img width="1497" height="842" alt="Screenshot 2026-09-09 223537" src="https://github.com/user-attachments/assets/72ca8b5e-efdc-4ee4-93de-b01b013189a3" />


I then chose the required material which was **6061-T6 Aluminum**

<img width="945" height="776" alt="Screenshot 2026-09-09 223751" src="https://github.com/user-attachments/assets/fe034bc7-0a97-43c1-89f7-0ad511599694" />














## Design Reflection
