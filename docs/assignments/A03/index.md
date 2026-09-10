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

## 1.2 Cross-Sectional Area

The cross-sectional area of the rectangular bar was calculated using:

$$
A = wh
$$

Substituting the selected dimensions:

$$
A = (1)(1)
$$

$$
\boxed{A = 1\text{ in}^2}
$$

The 1 in × 1 in cross section was selected because it provides a simple, uniform geometry that can easily be controlled using parametric dimensions in SOLIDWORKS.

---

## 1.3 Direct Tension Calculation

The length of the bar was determined using the direct tension elongation equation:

$$
\delta = \frac{FL}{AE}
$$

Solving for the length:

$$
L = \frac{\delta AE}{F}
$$

Substituting the selected design parameters:

$$
L =
\frac{(0.009)(1)(11,500,000)}
{500}
$$

$$
L = \frac{103,500}{500}
$$

$$
\boxed{L = 207\text{ in}}
$$

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
