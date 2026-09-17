---
title: "Stronger cuts for Benders’ decomposition for stochastic Unit Commitment Problems based on interval variables"
authors: 'M. Azéma, V. Leclère, W. van Ackooij'
collection: publications
category: published
permalink: /publication/2026-BDSUC
excerpt: 'Stronger cuts for Benders’ decomposition for stochastic Unit Commitment Problems based on interval variables.'
date: 2026-06-01
venue: 'Mathematical Programming Computation'
slidesurl: 'http://mathisazema.github.io/files/2025-PGMO.pdf'
paperurl: 'https://doi.org/10.1007/s12532-026-00334-1'
citation: 'Azéma, M., Leclère, V., van Ackooij, W. (2026). Stronger cuts for Benders’ decomposition for stochastic Unit Commitment Problems based on interval variables. Mathematical Programming Computation. https://doi.org/10.1007/s12532-026-00334-1.'
---
The Stochastic Unit Commitment (SUC) problem models the scheduling of power generation units under uncertainty, typically using a two-stage stochastic program with integer first-stage and continuous second-stage variables. We propose a new Benders' decomposition approach that leverages an extended formulation based on interval variables, enabling decomposition by both unit and time interval under mild technical assumptions. This formulation leads to provably stronger Benders' cuts than those derived from the standard 3-bin representation.
To improve computational efficiency, we introduce a heuristic based on weak duality to rapidly approximate the cut coefficients for units subject to ramping and capacity constraints. This allows us to retain cut strength while significantly reducing per-iteration cost.
Extensive computational experiments on large-scale risk-neutral and risk-averse instances — including the IEEE 118-bus system and SMS++ benchmarks — demonstrate that our method consistently outperforms the baseline approaches considered. 
On the most challenging test cases, it is up to five times faster than the best alternative and solves instances where no baseline closes the optimality gap within one hour.
