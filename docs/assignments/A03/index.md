# A3 – [Parametric and FEA]

## Outline
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

# Beam Calculations

The cross-sectional area of the rectangular bar was calculated using:

$$
A = wh
$$

<img width="1590" height="785" alt="IMG_0358" src="https://github.com/user-attachments/assets/d4e877e8-193c-480a-ac2e-231847a601b2" />



Therefore, the calculated maximum length of the bar is:

**207 inches**

---

## 1.4 Parametric CAD Model

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

The relationship used to determine the bar length was:

$$
L = \frac{\delta AE}{F}
$$

Since the cross-sectional area is:

$$
A = wh
$$

the length can also be represented as:

$$
L = \frac{\delta(wh)E}{F}
$$

This allows the length of the bar to change when the applied load, material properties, cross-sectional dimensions, or allowable deflection are changed.

### SOLIDWORKS Parametric Model

<!-- Add your SOLIDWORKS parameter screenshot below -->

![SOLIDWORKS Parametric Parameters](images/parametric_parameters.png)

*Figure 1. Parametric variables and equations used to control the aluminum bar.*

<!-- Add your CAD model screenshot below -->

![SOLIDWORKS Aluminum Bar](images/aluminum_bar.png)

*Figure 2. Final parametric aluminum bar model.*















## Design Reflection
