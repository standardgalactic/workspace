# Entropic Bifurcation: A Non-Expansionary Paradigm for Cosmological Structure Formation

---

## 1. The Crisis of Metric Expansion and the Plenum Alternative

The prevailing cosmological consensus, predicated upon metric expansion and vacuum symmetry breaking, necessitates re-evaluation in light of the non-expanding plenum model. This paradigm shifts away from geometric dilation in the Friedmann–Lemaître–Robertson–Walker (FLRW) framework, which relies on the scale factor \( a(t) \) and inflationary potentials, toward a model of internal reorganizational dynamics. Within a static-metric plenum, cosmic structure emerges from non-equilibrium instabilities—specifically entropic smoothing and transport on a Riemannian manifold \( (\mathcal{M}, g) \).

| Feature | Metric Expansion Model | Non-Expanding Plenum |
|----------|------------------------|----------------------|
| Geometry | Dynamic manifold; metric dilation | Static Riemannian manifold \( (\mathcal{M}, g) \) |
| Scale Factor \( a(t) \) | Primary driver of cooling and dilution | Absent; global volume constant |
| Structure Driver | Gravitational instability | Entropic smoothing and transport |
| Growth Mechanism | Inflation / vacuum symmetry breaking | Entropic bifurcation (Scalar Irruption) |
| Density Evolution | Metric dilution | Internal redistribution |

The shift from expansion-driven cooling to internal redistribution redefines cosmological architecture. Structure arises from interaction between the scalar density field \( \phi \) and vector flow \( v \) across a variational landscape.

---

## 2. Variational Formulation of the Scalar–Vector–Entropy System

We begin with the action functional:

\[
\mathcal{A}[\phi, v] =
\int_{\mathbb{R}} \int_{\mathcal{M}}
\left(
\frac{1}{2}(\partial_t \phi)^2
-
\frac{c^2}{2} |\nabla \phi|^2
+
v \cdot \nabla \phi
-
U(\phi, S)
\right)
d\mu_g \, dt
\]

Here:

- \( \frac{c^2}{2} |\nabla \phi|^2 \) encodes spatial smoothing.
- \( v \cdot \nabla \phi \) represents advection.
- \( S[\phi] = -\phi \log \phi \) defines pointwise entropy density.

Assume effective potential:

\[
U(\phi, S) = \frac{\alpha}{2} \phi^2 + \beta \phi \Delta_g S
\]

Applying the Euler–Lagrange equation and passing to a dissipative regime yields:

\[
\partial_t \phi =
c^2 \Delta_g \phi
-
\nabla \cdot (\phi v)
+
\alpha \phi
+
\beta \phi \Delta_g S
\]

### Definition: The Entropic Differential

The term

\[
\beta \phi \Delta_g S
\]

is the **entropic differential**. It measures the feedback of entropy curvature into scalar growth. When this term dominates smoothing, scalar irruption occurs.

---

## 3. The Scalar Irruption Criterion: Sign Inversion of Effective Diffusion

Consider perturbation:

\[
\phi = \phi_0 + \epsilon \psi
\]

Entropy derivative:

\[
S'[\phi_0] = -(1 + \log \phi_0)
\]

Growth rate for Laplacian eigenmode \( \psi_k \) with eigenvalue \( -\lambda_k \):

\[
\gamma_k =
-
\left(
c^2 - \beta \phi_0 (1 + \log \phi_0)
\right)
\lambda_k
+
\alpha
\]

### Theorem 1 (Scalar Irruption Criterion)

If

\[
D_{\text{eff}} =
c^2 - \beta \phi_0 (1 + \log \phi_0) < 0
\]

then sufficiently large \( \lambda_k \) induce a supercritical pitchfork-type bifurcation. The Laplacian switches from smoothing to amplification.

### Anatomy of a Crack Point

1. **Entropy Vaults:** \( \kappa_S = -\Delta_g S > 0 \)
2. **Crack Point Threshold:** \( \kappa_c = \frac{c^2}{\beta \phi_0} \)
3. **Effective Mass Shift:** Transition from parabolic to backward-parabolic operator

Nonlinear saturation stabilizes growth.

---

## 4. The Five-Engine Plenum Architecture

The architecture consists of five coupled operators:

### 1. Gradient Anisotropic Smoothing (GAS)
\[
\mathcal{G} = c^2 \Delta_g \phi
\]

Baseline diffusive stabilization.

### 2. Deferred Thermodynamic Reservoirs (DTR)
\[
\mathcal{R}[\phi](t) =
\int_{-\infty}^{t}
K(t-\tau)\phi(\tau)\, d\tau
\]

Temporal entropy memory.

### 3. Poincaré-Triggered Lattice Recrystallization (PTLR)
\[
\Pi_\Lambda(\phi)
\]

Lattice projection inducing entropy curvature spikes.

### 4. Scalar Irruption via Entropic Differential (SIED)
\[
\mathcal{I} = \beta \phi \Delta_g S
\]

Primary amplification engine.

### 5. Neutrino Fossil Registry (NFR)
\[
\mathcal{N} =
\epsilon
\int_{\mathcal{M}}
\eta(x,y)\phi(y)\, dy
\]

Weak residual memory operator.

PTLR concentrates entropy deviations; SIED amplifies them; NFR preserves historical structure.

---

## 5. Lamphron vs. Lamphrodyne States

Define vacuum response field:

\[
\chi = -\beta \Delta_g S
\]

| Lamphron State | Lamphrodyne State |
|----------------|------------------|
| \( \chi < 0 \) | \( \chi > 0 \) |
| Entropy enhances smoothing | Entropy drives growth |
| Parabolic operator | Backward-parabolic operator |
| Suppresses fluctuations | Induces irruption |

Because \( \lambda_k \to \infty \) but \( \chi_k \) bounded, instability is band-limited:

\[
c^2 \lambda_k < \alpha + \chi_k
\]

Only finitely many modes destabilize. This prevents ultraviolet divergence and yields quasi-periodic scalar condensates analogous to BAO, but without expansion.

---

## 6. Scalar Irruption as a Derived Geometric Phase Transition

Scalar irruption unifies four regimes:

**PDE:**  
\[
D_{\text{eff}} < 0
\]

**Spectral:**  
Band-limited Laplacian mode growth.

**Thermodynamic:**  
Entropy curvature release at crack points.

**Quantum:**  
Inverted harmonic oscillator instability:

\[
\ddot{\hat{\phi}}_k = \omega_k^2 \hat{\phi}_k
\]

Mode occupation grows:

\[
e^{2 \omega_k t}
\]

---

## BV/AKSZ Consistency

The BV-extended action \( S_{BV} \) satisfies:

\[
\{S_{BV}, S_{BV}\} = 0
\]

Scalar irruption corresponds to a change in the homotopy type of the critical locus of the action functional. The instability reflects a structural shift in the derived stack of classical solutions.

---

## Conclusion

Structure formation is an internally reorganizational phenomenon of a static-metric plenum. Entropy differentials—not metric expansion—drive cosmic structure. These results remain robust under crystallographic discretization within the Crystal Plenum framework.

