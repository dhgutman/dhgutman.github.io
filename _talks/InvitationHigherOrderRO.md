---
title: "An Invitation to Higher-Order Riemannian Optimization"
collection: talks
type: "Talk"
permalink: /talks/HigherOrderRiemannianOptimization/
venue: "Multiple Venues"
date: 2026-06-02
location: "Multiple Locations"
---
Locations:
* SIAM Conference on Optimization (SIOPT 2026), Edinburgh, UK — June 2, 2026
* INFORMS Optimization Society Conference (IOS 2026), Atlanta, GA — March 21, 2026

In this talk, we propose a class of implementable, optimal-rate methods for nonconvex optimization over Riemannian manifolds when derivative oracles up to order p are available. Our analysis proves that, under this regime, Riemannian optimization is no harder than Euclidean optimization: the Riemannian convergence rates match the optimal Euclidean rates. Furthermore, we comprehensively characterize how the regularity of the retraction and objective function jointly impacts that of the pullback functions. The engine driving this characterization is a novel Faà di Bruno–type formula for pullback derivatives, constructed using the rarely applied higher-order covariant differential calculus. Moreover, we show that the entire class of efficient retractions of Gawlik et al. can be applied within these methods.

Our theoretical framework yields implementable third-order methods when equipped with suitable subproblem solvers. The mechanism enabling implementation is a symmetric Krylov tensor subspace method. Building on the Savas–Eldén approach, it can hybridize with recent techniques for minimizing quartically regularized third-order polynomials.
