

Title: Geometrical deformation of brane matter field within f(R,Q,P) gravity

Authors: Fernando M. Belchior, Roberto V. Maluf, Albert Yu. Petrov, Paulo J. Porfírio

1. Introduction and Background:

1.1 Historical Context:
- Kaluza-Klein theory (1920s): First proposal of extra dimensions to unify gravity and electromagnetism
- Randall-Sundrum (RS) model (1999): Introduced warped extra dimensions to address hierarchy problem

1.2 Braneworld Scenarios:
- Our universe as a 3-brane embedded in higher-dimensional bulk
- Thick branes: Extension of RS model using scalar fields to give brane thickness
- Internal structure of branes: Kink-like configurations in (1+1) dimensions

1.3 Modified Gravity Theories:
- f(R) gravity: Action depends on a function of Ricci scalar
- f(R,T) gravity: Includes trace of energy-momentum tensor
- Other theories: Cubic gravity, mimetic gravity, bimetric gravity, Horndeski gravity, bumblebee gravity

1.4 Research Objectives:
- Study codimension-one thick brane in f(R,Q,P) gravity
- Investigate impact of geometric invariants on scalar field solutions and brane energy density
- Analyze localization of spin-1/2 fermions and gravitinos (spin-3/2)

2. Theoretical Framework:

2.1 f(R,Q,P) Gravity Action:
$$S = \int d^5x \sqrt{-g} \left[\frac{1}{4}f(R,Q,P) + L_m\right]$$
Where:
- R: Ricci scalar
- Q = R^μν R_μν: Square of Ricci tensor
- P = R^μναβ R_μναβ: Square of Riemann tensor
- L_m: Matter Lagrangian

2.2 Field Equations:
Variation of action with respect to metric g_MN yields:
$$R_{MN}f_R - \frac{1}{2}g_{MN}f + H_{MN} + K_{MN} = 2T_{MN}$$
Where:
$$H_{MN} = (g_{MN}\square - \nabla_M\nabla_N)f_R$$
$$K_{MN} = \square(f_QR_{MN}) + g_{MN}\nabla_A\nabla_B(f_QR^{AB}) + 2f_QR^A_{(M}R_{N)A} - 2\nabla_A\nabla_{(M}(f_QR^A_{N)}) + f_PR_{ABCM}R^{ABC}_N - 4\nabla_A\nabla_B(f_PR^A_{(MN)}B)$$

2.3 Braneworld Metric:
$$ds^2 = e^{2A(y)}\eta_{\mu\nu}dx^\mu dx^\nu + dy^2$$
Warp factor:
$$A(y) = \omega \ln[\text{sech}(y)]$$

Properties of warp factor:
- Reproduces RS warp factor far from brane: $$\lim_{y\to\infty} e^{2A(y)} \to 0$$
- Smooth profile near brane
- Z_2 symmetry: $$e^{2A(y)} = e^{2A(-y)}$$
- Ensures normalizable graviton zero-mode: $$\int_{-\infty}^{\infty} dy e^{8A(y)} < \infty$$

2.4 Geometric Invariants:
For the given metric:
$$R = -4(2A'' + 5A'^2)$$
$$Q = 20A''^2 + 80A'^4 + 64A'^2A''$$
$$P = 24A'^4 + 16(A'' + A'^2)^2$$

2.5 Matter Content:
Single scalar field Lagrangian:
$$L_m = -\frac{1}{2}\partial_M\phi\partial^M\phi - V(\phi)$$

Energy-momentum tensor:
$$T_{MN} = \partial_M\phi\partial_N\phi + g_{MN}L_m$$

Scalar field equation of motion:
$$\frac{1}{\sqrt{-g}}\partial_M(\sqrt{-g}\partial^M\phi) - V_\phi = 0$$

3. Analysis of Different f(R,Q,P) Models:

3.1 Quadratic Gravity:
$$f(R,Q,P) = R + k_1R^2 + k_2Q + k_3P$$

Scalar field solution:
$$\phi'(y)^2 = \frac{1}{2}\omega \text{sech}^2(y)[-4\tanh^2(y)(2k_1(\omega(5\omega+16)+8) + k_2(2\omega(\omega+5)+5) + k_3(\omega(\omega+8)+4)) + 2(4\omega+1)\text{sech}^2(y)(16k_1+5k_2+4k_3) + 3]$$

Energy density:
$$\rho(y) = \frac{1}{2}\omega \text{sech}^{2\omega}(y)[4\omega^3\tanh^4(y)(10k_1 + 2k_2 + k_3) + \text{sech}^2(y)(3 - 4\tanh^2(y))[\omega^2(74k_1 + 22k_2 + 17k_3) + 4\omega(16k_1 + 5k_2 + 4k_3) + 16k_1 + 5k_2 + 4k_3] + 2(3\omega + 1)\text{sech}^4(y)(16k_1 + 5k_2 + 4k_3) - 6\omega\tanh^2(y)]$$

3.2 Cubic Gravity:
$$f(R,Q,P) = R + k_1R^3 + k_2RQ + k_3RP$$

Scalar field solution (equation is very lengthy, see paper for full expression)

3.3 Quartic Gravity:
Three cases studied:

a) $$f(R,Q,P) = R + k_1R^4 + k_2Q^2 + k_3P^2$$
b) $$f(R,Q,P) = R + k_1R^4 + k_2QP$$
c) $$f(R,Q,P) = R + (k_1R^2 + k_2Q + k_3P)^2$$

(Equations for scalar field solutions are extremely lengthy for these cases)

4. Fermion Localization:

4.1 Dirac Fermions (Spin-1/2):

Action:
$$S_{1/2} = \int d^5x \sqrt{-g}(i\bar{\Psi}\Gamma^MD_M\Psi - \lambda\phi\bar{\Psi}\Psi)$$

Equation of motion:
$$[i\gamma^\mu\partial_\mu + \gamma^4(\partial_z + 2\dot{A}) + \lambda\phi e^A]\Psi(x,z) = 0$$

Kaluza-Klein decomposition:
$$\Psi(x,z) = \sum_n[\psi_{L,n}(x)\chi_{L,n}(z) + \psi_{R,n}(x)\chi_{R,n}(z)]e^{-2A}$$

Schrödinger-like equations:
$$(-\partial^2_z + V_L(z))\chi_L = m^2\chi_L$$
$$(-\partial^2_z + V_R(z))\chi_R = m^2\chi_R$$

Effective potentials:
$$V_L = (\lambda\phi e^A)^2 - \partial_z(\lambda\phi e^A)$$
$$V_R = (\lambda\phi e^A)^2 + \partial_z(\lambda\phi e^A)$$

Zero-mode solutions:
$$\chi_L = e^{-\lambda\int dz\phi(z)}$$
$$\chi_R = e^{\lambda\int dz\phi(z)}$$

4.2 Rarita-Schwinger Field (Spin-3/2, Gravitino):

Action:
$$S_{3/2} = \int d^5x \sqrt{-g}(i\bar{\Psi}_M\Gamma^{[M}\Gamma^N\Gamma^{R]}D_N\Psi_R - \lambda\phi\bar{\Psi}_M[\Gamma^M,\Gamma^N]\Psi_N)$$

Equation of motion:
$$[i\gamma^{[\mu}\gamma^\nu\gamma^{\rho]}\partial_\nu + \gamma^\mu\gamma^4(\partial_z + \dot{A}) + \lambda\phi e^A[\gamma^\mu,\gamma^4]]\Psi_\rho(x,z) = 0$$

Kaluza-Klein decomposition:
$$\Psi_\mu(x,z) = \sum_n[\psi_{\mu L,n}(x)\alpha_{L,n}(z) + \psi_{\mu R,n}(x)\alpha_{R,n}(z)]e^{-A}$$

Schrödinger-like equations (similar to Dirac case):
$$(-\partial^2_z + V_L(z))\alpha_L = m^2\alpha_L$$
$$(-\partial^2_z + V_R(z))\alpha_R = m^2\alpha_R$$

5. Key Findings and Discussions:

5.1 Quadratic Gravity:
- Produces two-kink solutions
- Brane splitting phenomenon observed
- Energy density shows tendency to split as k_1 increases

5.2 Cubic Gravity:
- Generates 3-kink solutions
- Richer internal brane structure compared to quadratic case
- Energy density shows slight modification in lateral regions

5.3 Quartic Gravity:
- Case (a) and (b): 3-kink solutions observed
- Case (c): 2-kink profile emerges
- Energy density shows deeper splitting compared to quadratic and cubic cases

5.4 Fermion Localization:
- Only left-handed zero-modes are localized on the brane for both spin-1/2 and spin-3/2 fermions
- Effective potentials for spin-1/2 and spin-3/2 fields are identical
- Zero-mode profiles are influenced by the deformed scalar field solutions
