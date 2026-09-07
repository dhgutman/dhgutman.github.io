---
title: "Quantum-Enhanced Generalized Pattern Search Optimization"
collection: publications
category: journal
permalink: /publication/QuantumEnhancedGPS
excerpt: 'with Colton Mikes (Texas Tech University) and Victoria E. Howle (Texas Tech University)'
date: 2024-09-29
venue: 'Quantum Reports'
paperurl: 'https://doi.org/10.3390/quantum6040034'
---

We introduce quantum improved point search (QIPS), a hybrid classical–quantum algorithm that incorporates quantum search into generalized pattern search optimization while preserving its convergence guarantees. Standard quantum search can accelerate the discovery of an improving point, but failing to identify an existing improving point can violate the assumptions required for convergence.

QIPS combines quantum search with a classical search process. When an improving point exists among $N$ candidates, it retains the expected $O(\sqrt{N})$ oracle query complexity of quantum search. When no improving point exists, it certifies this with certainty using $O(N)$ oracle calls. This allows generalized pattern search to benefit from quantum search without compromising its convergence requirements.

Recommended citation: Mikes, C., Gutman, D. H., & Howle, V. E. (2024). Quantum-enhanced generalized pattern search optimization. *Quantum Reports*, 6(4), 509–521. https://doi.org/10.3390/quantum6040034
