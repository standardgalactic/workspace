# Entropic Bifurcation: A Non-Expansionary Paradigm for Cosmological Structure Formation

---

## 1. The Crisis of Metric Expansion and the Plenum Alternative

The prevailing cosmological consensus, grounded in metric expansion and vacuum symmetry breaking, invites reconsideration under the non-expanding plenum model. This framework replaces geometric dilation in the Friedmann–Lemaître–Robertson–Walker setting with internal reorganizational dynamics. Within a static-metric plenum, cosmic structure emerges from non-equilibrium instabilities governed by entropic smoothing and transport on a Riemannian manifold (𝓜, g).

| Feature           | Metric Expansion Model                 | Non-Expanding Plenum                    |
| ----------------- | -------------------------------------- | --------------------------------------- |
| Geometry          | Dynamic manifold; metric dilation      | Static Riemannian manifold (𝓜, g)      |
| Scale factor a(t) | Primary driver of cooling and dilution | Absent; global volume constant          |
| Structure driver  | Gravitational instability              | Entropic smoothing and transport        |
| Growth mechanism  | Inflation / vacuum symmetry breaking   | Entropic bifurcation (scalar irruption) |
| Density evolution | Metric dilution                        | Internal redistribution                 |

The shift from expansion-driven cooling to internal redistribution reframes cosmological architecture. Structure arises from interaction between the scalar density field φ and vector flow v across a variational landscape.

---

## 2. Variational Formulation of the Scalar–Vector–Entropy System

We begin with the action functional:

𝓐[φ, v] = ∫_ℝ ∫_𝓜 [ ½(∂ₜφ)² − ½c² |∇φ|² + v · ∇φ − U(φ, S) ] dμ_g dt

Here, the gradient term encodes spatial smoothing, the advection term represents transport by the flow field, and the entropy density is

S[φ] = −φ log φ

Assume an effective potential

U(φ, S) = (α/2) φ² + β φ Δ_g S

Applying the Euler–Lagrange equation and passing to a dissipative regime yields

∂ₜφ = c² Δ_g φ − ∇·(φ v) + α φ + β φ Δ_g S

### Definition: The Entropic Differential

The term

β φ Δ_g S

is the entropic differential. It measures the feedback of entropy curvature into scalar growth. When this term dominates smoothing, scalar irruption occurs.

---

## 3. The Scalar Irruption Criterion: Sign Inversion of Effective Diffusion

Consider a perturbation

φ = φ₀ + ε ψ

Entropy derivative at equilibrium:

S′[φ₀] = −(1 + log φ₀)

For a Laplacian eigenmode ψ_k with eigenvalue −λ_k, the growth rate is

γ_k = −(c² − β φ₀ (1 + log φ₀)) λ_k + α

### Theorem 1 (Scalar Irruption Criterion)

If

D_eff = c² − β φ₀ (1 + log φ₀) < 0

then sufficiently large λ_k induce a supercritical pitchfork-type bifurcation. The Laplacian switches from smoothing to amplification.

### Anatomy of a Crack Point

1. Entropy vaults: κ_S = −Δ_g S > 0
2. Crack-point threshold: κ_c = c² / (β φ₀)
3. Effective mass shift: transition from parabolic to backward-parabolic operator

Nonlinear saturation stabilizes growth.

---

## 4. The Five-Engine Plenum Architecture

The architecture consists of five coupled operators.

### Gradient Anisotropic Smoothing (GAS)

𝓖 = c² Δ_g φ

Baseline diffusive stabilization.

### Deferred Thermodynamic Reservoirs (DTR)

𝓡[φ](t) = ∫_{−∞}^{t} K(t − τ) φ(τ) dτ

Temporal entropy memory.

### Poincaré-Triggered Lattice Recrystallization (PTLR)

Π_Λ(φ)

Lattice projection inducing entropy curvature spikes.

### Scalar Irruption via Entropic Differential (SIED)

𝓘 = β φ Δ_g S

Primary amplification engine.

### Neutrino Fossil Registry (NFR)

𝓝 = ε ∫_𝓜 η(x, y) φ(y) dy

Weak residual memory operator.

PTLR concentrates entropy deviations, SIED amplifies them, and NFR preserves historical structure.

---

## 5. Lamphron vs. Lamphrodyne States

Define the vacuum response field

χ = −β Δ_g S

| Lamphron State             | Lamphrodyne State           |
| -------------------------- | --------------------------- |
| χ < 0                      | χ > 0                       |
| Entropy enhances smoothing | Entropy drives growth       |
| Parabolic operator         | Backward-parabolic operator |
| Suppresses fluctuations    | Induces irruption           |

Because λ_k → ∞ while χ_k remains bounded, instability is band-limited:

c² λ_k < α + χ_k

Only finitely many modes destabilize. This prevents ultraviolet divergence and yields quasi-periodic scalar condensates analogous to baryon acoustic oscillations without requiring expansion.

---

## 6. Scalar Irruption as a Derived Geometric Phase Transition

Scalar irruption unifies several complementary descriptions.

**PDE:**
D_eff < 0

**Spectral:**
Band-limited Laplacian mode growth.

**Thermodynamic:**
Entropy curvature release at crack points.

**Quantum:**
φ̈_k = ω_k² φ_k
Mode occupation grows as e^(2 ω_k t).

---

## BV/AKSZ Consistency

The BV-extended action S_BV satisfies

{S_BV, S_BV} = 0

Scalar irruption corresponds to a change in the homotopy type of the critical locus of the action functional, reflecting a structural shift in the derived stack of classical solutions.

---

## Conclusion

Structure formation is an internally reorganizational phenomenon of a static-metric plenum. Entropy differentials, rather than metric expansion, drive cosmic structure. These results remain robust under crystallographic discretization within the Crystal Plenum framework.
