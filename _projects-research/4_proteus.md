---
title: "R&D High-Fidelity Computational Tools for Simulating Wave-Streucture Interaction"
share: false
---

<p style="text-align: justify;">
This research project focuses on developing high-fidelity computational tools to simulate wave-structure interactions, specifically addressing the dynamic response of floating structures under wave excitations. It introduces significant advancements in high-order numerical methods and specialized computational techniques to model complex water wave phenomena in coastal and ocean engineering. Key models utilized in this study include two-phase Navier-Stokes (TpNS) flow, fully nonlinear potential flow, and the Serre-Green-Naghdi (SGN) model for nonlinear dispersive shallow-water flows.

For the viscous approach, the finite element (FE) method is employed to spatially discretize the TpNS equations, while a hybrid LS-VOF (Level Set coupled with Volume of Fluid) method effectively manages the free surface. This includes the reformulation of a phase-conservative LS equation with a semi-implicit high-order projection scheme, ensuring accurate interface tracking and preventing mass loss. The potential-flow model transforms the Laplace equation into a boundary integral equation (BIE), which is solved using boundary element methods (BEM) with regularized BIEs, enabling the direct use of high-order quadrature.

An explicit hyperbolic relaxation technique is also applied to the SGN equations to model dispersive shallow-water flows, capturing the nonlinearity and complex wave interactions influenced by varying topography. A critical part of this research is investigating how floating structures respond dynamically to wave forces, including the analysis of wave-induced motions, structural deformations, and resonance effects. By correlating numerical results with experimental measurements, the project offers valuable insights into the interplay between wave forces and structural responses, highlighting the trade-offs between physical fidelity and computational effort in modeling these interactions.
</p>

Funding source: LSU Department of Civil & Environmental Engineering