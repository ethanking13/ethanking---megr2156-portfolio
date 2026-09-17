# Motor Mount Design

## Objective

The objective of this project is to design a PLA motor mount that can safely support the applied load while satisfying the required bending stress and deflection limits. The mount's cross-sectional geometry will be determined using beam bending equations for both maximum stress and maximum deflection. The final design will be evaluated to ensure that it meets the specified safety factor and performance requirements.

## Knowns

* **Material:** PLA
* **Elastic modulus:** \(E = 2.35\text{ GPa} = 2350\text{ MPa}\)
* **Yield strength:** \(S_y = 77.4\text{ MPa}\)
* **Maximum allowable deflection:** \(\delta_{\max} = 0.30\text{ mm}\)
* **Safety factor:** \(N = 3\)
* **Applied force:** \(P = 300\text{ N}\)
* **Beam length:** \(L = 27\text{ mm}\)
* **Cross-section height:** \(H = 22\text{ mm}\)

### Motor Dimensions

* **Shaft diameter:** \(d = 6\text{ mm}\)
* **Shaft length:** \(L_s = 18\text{ mm}\)

## Unknowns

* **Cross-sectional area:** \(A = ?\)
* **Minimum \(b\) based on deflection:** \(b_{\min,\delta} = ?\)
* **Minimum \(b\) based on stress:** \(b_{\min,\sigma} = ?\)

## Equations to be Used

### Maximum Deflection

$$
\boxed{\delta_{\max}=\frac{ML}{2EI}}
$$

### Bending Stress

$$
\boxed{b=\frac{6M}{\sigma_{\max}H^2}}
$$

### Allowable Stress

$$
\boxed{\sigma_{\max}=\frac{S_y}{N}}
$$

## Free-Body Diagram

The free-body diagram is used to determine the bending moment created by the applied force on the motor mount.

### Maximum Allowable Stress

$$
\sigma_{\max}=\frac{S_y}{N}
$$

Given:

$$
S_y=77.4\text{ MPa}
$$

$$
N=3
$$

Substitute:

$$
\sigma_{\max}=\frac{77.4\text{ MPa}}{3}
$$

$$
\boxed{\sigma_{\max}=25.8\text{ MPa}}
$$

### Bending Stress Calculation

Using:

$$
M=5400\text{ N·mm}
$$

$$
H=22\text{ mm}
$$

$$
\sigma_{\max}=25.8\text{ MPa}
$$

The bending stress equation is:

$$
b=\frac{6M}{\sigma_{\max}H^2}
$$

Substitute:

$$
b=\frac{6(5400)}
{(25.8)(22)^2}
$$

$$
b=\frac{32400}{12487.2}
$$

$$
\boxed{b_{\min,\sigma}=2.59\text{ mm}}
$$

### Deflection Calculation

For a rectangular cross section:

$$
I=\frac{bH^3}{12}
$$

Using the stress-based value:

$$
b=2.59\text{ mm}
$$

$$
H=22\text{ mm}
$$

$$
I=\frac{(2.59)(22)^3}{12}
$$

$$
\boxed{I\approx2299.8\text{ mm}^4}
$$

The deflection equation is:

$$
\delta_{\max}=\frac{ML}{2EI}
$$

Substitute:

$$
\delta_{\max}
=
\frac{(5400)(27)}
{2(2350)(2299.8)}
$$

$$
\boxed{\delta\approx0.0135\text{ mm}}
$$

Compare with the allowable deflection:

$$
0.0135\text{ mm}<0.30\text{ mm}
$$

$$
\boxed{\text{PASS}}
$$

### Minimum \(b\) Based on Deflection

Starting with:

$$
\delta_{\max}=\frac{ML}{2EI}
$$

Using:

$$
I=\frac{bH^3}{12}
$$

Therefore:

$$
\delta_{\max}=\frac{6ML}{EbH^3}
$$

Solving for \(b\):

$$
\boxed{b=\frac{6ML}{E\delta_{\max}H^3}}
$$

Substitute:

$$
b=
\frac{6(5400)(27)}
{(2350)(0.30)(22)^3}
$$

$$
b=\frac{874800}{7507380}
$$

$$
\boxed{b_{\min,\delta}=0.117\text{ mm}}
$$

### Cross-Sectional Area

The cross-sectional area of the rectangular section is:

$$
A=bH
$$

Using the stress-controlled value:

$$
A=(2.59)(22)
$$

$$
\boxed{A=56.98\text{ mm}^2}
$$

Rounded:

$$
\boxed{A\approx57.0\text{ mm}^2}
$$

### Final Required Dimension

The two calculated minimum widths are:

$$
b_{\min,\delta}=0.117\text{ mm}
$$

$$
b_{\min,\sigma}=2.59\text{ mm}
$$

Since the stress requirement is larger:

$$
\boxed{b_{\text{required}}=2.59\text{ mm}}
$$

Therefore, **bending stress controls the design**, while the deflection requirement is also satisfied.
