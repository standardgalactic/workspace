# Technical Report: A Formal Framework of Constraint Geometry and Self-Modifying Propagation Kernels in Biological Organization

## 1. Introduction: From Blueprints to Constraint Geometry

The prevailing “blueprint” model of biological development—the intuition that genetic sequences directly specify macroscopic structures—fails to account for the emergent complexity of systems such as the neocortex or reticulate vascular networks. We propose a paradigm shift toward Constraint Geometry, where development is defined not as the execution of a fixed program, but as the continuous modulation of the conditions under which future interactions remain possible. In this framework, biological organization is the result of a system reshaping its own medium to gate specific trajectories.

To formalize this, we define four levels of biological description:

- **𝓧 (State Manifold):** The space of all representable configurations (e.g., the set of possible gene expression states or neural activity patterns).
- **Γ_adm (Admissibility Structure):** The dynamically evolving operator C(t) that determines which trajectories through the state manifold are geometrically possible. Admissibility is defined by the condition C(t)γ(t) = 0.
- **μ_t (Stochastic Dynamics):** The probability measure over the admissible trajectory set, induced by fluctuations, noise, and environmental inputs.
- **⟨γ⟩ (Realized Macroscopic Structure):** The observable outcome; the typical path measured by anatomy or physiology.

The fundamental relationship follows the sequence:

𝓧 → Γ_adm → μ_t → ⟨γ⟩

Crucially, evolution acts primarily on the Admissibility Structure (Γ_adm) rather than the realized structure. By altering the topology of what is possible (Level 2), evolution steers biological systems toward specific outcomes without requiring a point-by-point blueprint. We now explore this through the lens of spatial partitioning.

---

## 2. Spatial Partition Operators: Voronoi Dynamics in Reticulate Venation

Reticulate venation (closed-loop architecture) challenges standard canalization models that rely on source-to-sink transport. To understand these architectures, we must identify global geometric descriptors. In *Pilea peperomioides*, the major vein network is organized around hydathodes (secretory pores) acting as organizing centers.

Quantitative analysis demonstrates that the vascular network is better described by Voronoi geometry than by hierarchical subdivision models.

| Model Feature | Jaccard Index | Generative Principle | Biological Basis |
|---|---|---|---|
| Hydathode-Voronoi | 0.72 | Spatial balance / Equidistance | Auxin wave interference |
| Centroid-based | 0.67 | Geometric center of polygons | Mathematical abstraction |
| Random Point | 0.47 | Baseline stochasticity | Stochastic noise |
| k-d Tree Tessellation | 0.40 | Recursive hierarchical bisection | Hierarchical canalization |

This structure arises through Emergent Equilibrium Partitioning. Hydathodes act as generator points, broadcasting auxin concentration waves. The mechanism is driven by polar transport dynamics. The unidirectional flux J_A→B is defined as:

J_A→B = c_A(k_d + k_p[PIN]_A→B)

where wave collisions define the locus of vascular differentiation. These collisions create a concentration maximum at the equidistant line between sources, stabilized by PIN transport.

## Mathematical Definition of Voronoi Partitioning

Let:

𝓗 = {h₁, h₂, …, hₙ}

be the set of hydathode positions. The Voronoi cell V_i is defined as:

V_i = {x ∈ ℝ² | d(x, h_i) ≤ d(x, h_j) ∀ j ≠ i}

The partition boundary condition ∂V_i ∩ ∂V_j arises at the collision locus where the effective developmental potential fields ℰ_i satisfy:

∂V_i ∩ ∂V_j = {x : ‖∂_t ℰ_i(x, t)‖ = ‖∂_t ℰ_j(x, t)‖}

This transition from static spatial maps leads us to the dynamic material transitions of embryonic development.

---

## 3. Material Constraint Geometry: Rigidity Percolation and Signal Regulation

Tissue is an active regulatory medium. In the zebrafish blastoderm, the Nodal morphogen gradient is shaped by a tissue-scale Rigidity Phase Transition. This transition is governed by rigidity percolation theory, where the tissue shifts from a fluid-like to a solid-like state once it acquires a “giant rigid cluster.”

The transition occurs at a critical connectivity threshold ⟨k_c⟩ ≈ 4 and is sensitive to the relative surface tension α, with a critical value α_c ≈ 0.866.

A causal feedback loop exists: Nodal signaling drives Wnt11f2-mediated adhesion, triggering a “porosity collapse” (Φ_min ≈ 0). This collapse restricts Nodal diffusivity D_N according to the relationship:

D_N = D₀ · φ(Φ)

where diffusivity scales with porosity.

This terminates the signaling event that initiated the rigidity. Optogenetic rescue experiments using the Opto-RhoGEF system have proven that manually restoring the tissue’s physical geometry (rigidity/adhesion) is sufficient to restore the Smad2 spatial distribution and signaling kinetics, even in Wnt11f2 mutants. Thus, material constraints dictate signaling range.

---

## 4. Regulatory Accessibility: Evolutionary Manifolds and Heterochrony

Neocortex evolution illustrates that species differences are driven by “accessibility modulation” of conserved programs. Mouse and human corticogenesis traverse similar state manifolds, but they differ in which trajectories are “open” via the accessibility function χ(x, t).

### Contrast the JUNB Gene and its Regulator IRF1

1. **Poised but Inaccessible:** In mice, the molecular machinery for early JUNB expression is present but “poised” and inaccessible.
2. **Unlocking Latency:** Activating the upstream regulator IRF1 in mouse tissue unlocks the early JUNB program, causing progenitors to adopt human-like behaviors (extended persistence).
3. **Intermediate Progenitors:** These act as evolutionary amplifiers, existing in “soft” constraint regions where accessibility is easily modified.

Heterochrony (developmental pacing) functions as a temporal dilation in the accessibility function:

χ_human(x, t) = χ_mouse(x, t / τ), τ > 1

Building a human cortex is not about new genes, but about re-timing the accessibility of an existing genetic toolkit.

---

## 5. Communication Geometry: Subspace Rotation and Information Routing

Beyond anatomy, inter-regional information flow is governed by low-dimensional Communication Subspaces (identified via pCCA). In the CA3–CA1–RSC axis, CA1 rotates its activity patterns—measured by principal angles—to route information selectively.

| Dimension | CA1–CA3 (Intrahippocampal) | CA1–RSC (Hippocampal-Cortical) |
|---|---|---|
| Plasticity | High (Enhanced during NREM sleep) | Low (Stable across brain states) |
| Sparsity | High Gini Coefficient (Sparse) | Low Gini Coefficient (Distributed) |
| Function | Rapid encoding / sequence replay | Context maintenance / Stability |

RNN learning experiments demonstrate the Computational Necessity of Subspace Rotation: if subspaces are fixed, the network fails to adapt the input-output mapping to the task. Rotation is a “load-bearing” geometric mechanism for selective routing and interference prevention.

---

## 6. Synthesis: Biological Systems as Self-Modifying Propagation Media

Biological organization is the study of active media—environments where signals change the medium through which future signals propagate. We define the Propagation Kernel K_t(x, y) as the operator describing how a state at y influences a state at x.

The core thesis is that development is the process of modifying K_t, expressed by the “smoking gun” condition:

δK / δS ≠ 0

We unify the four types of geometry under the operator C(t):

- **Spatial Partition Geometry (C_V):** Local competitive dynamics setting physical boundaries.
- **Material Constraint Geometry (C_R):** Mechanical phase structures gating diffusion (porosity collapse).
- **Regulatory Accessibility Geometry (C_A):** State-space expressibility gating developmental fates (poised programs).
- **Dynamical Projection Geometry (C_S):** Subspace orientation gating information flow (rotation).

---

## 7. Conclusion: Predictive Consequences of the Framework

Direct specification fails at scale. Instead, biological systems use controlled constraint reorganization to build complexity. By establishing a sequence of admissibility structures C(t), the system builds itself.

This framework yields four falsifiable predictions:

1. **Priority of Geometry:** Interventions targeting the propagation medium (e.g., tissue rigidity) will outperform direct manipulation of signal concentrations.
2. **Ubiquity of Latency:** Shifting accessibility regulators (like IRF1) will reveal latent, “human-like” trajectories in simpler model organisms.
3. **Source of Robustness:** Robustness arises from distributed constraint dynamics; systems are more sensitive to upstream geometric regulators than to individual downstream signals.
4. **Mechanism of Flexibility:** Rapid cognitive task-switching relies on subspace rotation within a fixed anatomical substrate, occurring faster than synaptic rewiring.

The evolution of the constraint operator C(t) is the primary determinant of biological organization, shifting our focus from the product of development to the evolving geometry of the process.
