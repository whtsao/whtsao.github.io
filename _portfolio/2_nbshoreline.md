---
title: "Natural Shoreline Design"
excerpt: "Studying shoreline protection and ecosystem design through high-performance modeling of mangrove forests in waves."
header:
  image: /assets/images/mangrove_sim.png
  teaser: /assets/images/mangrove_sim.png
share: false
---

<p style="text-align: justify;">
We present the implementation of a high-order phase-resolving Cut Finite Element Method (CutFEM) to simulate the hydrodynamic features within an artificial mangrove forest caused by wave and current based on the incompressible two-phase Navier-Stokes model. The key advantage of CutFEM is that the fluid phase is fully resolved around the solid phase. This enables precise replication of the free-surface deformation and hydrodynamic drag, particularly for waves strongly interacting with the intricate prop roots of mangrove trees. Additionally, the present method employs the equivalent polynomial to compute the integration on the embedded surface with Heaviside and Dirac distributions. No explicit generation of cut cell meshes, adaptive quadrature, or local refinement is required. Hence, it uses the same number of degrees of freedom as the underlying conforming Galerkin method on the fixed background mesh. The classical FEM can be upgraded since the same element assembly structures are used. This paper characterizes different components of the hydrodynamic drag induced by the mangrove forest. The reduced-order model accounts for the equivalent wave damping is further established to replicate the wave attenuation. The numerical results and experimental measurements are compared. The results show that CutFEM is robust, accurate, and efficient for solving complex fluid-structure interactions. This research not only offers a convenient method for upgrading existing finite element codes but also benefits practical design applications.
</p>

![Diagram of PMTLD](/assets/images/mangrove_lidar.png)

![Diagram of PMTLD](/assets/images/mangrove_image.png)