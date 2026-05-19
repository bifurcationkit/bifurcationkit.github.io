---
layout: default
title: Home
permalink: /
---

# bifurcationkit: towards automatic bifurcation analysis of dynamic systems

The bifurcationkit organization is a collection of tools for computing bifurcation diagrams of dynamical systems developed in the Julia programming language. The organization provides well-maintained tools which compose together as a coherent ecosystem. 

## 🚀 Where to start?
- Want to get started running some code? Check out the [Getting Started tutorials](https://bifurcationkit.github.io/BifurcationKitDocs.jl/dev/gettingstarted/)
- Want to compute bifurcation diagrams of PDEs? check these [tutorials](https://bifurcationkit.github.io/BifurcationKitDocs.jl/dev/tutorials/tutorials/#PDEs:-bifurcations-of-equilibria)
- Want to compute bifurcation diagrams of GPU? check these [tutorials](https://bifurcationkit.github.io/BifurcationKitDocs.jl/dev/tutorials/tutorials2b/#sh2dgpu)

## 🧩 Which packages?
- for delay differential equations, check [DDEBifurcationKit.jl](https://github.com/bifurcationkit/DDEBifurcationKit.jl)
- for computing homoclinic orbits, check [HclinicBifurcationKit.jl](https://github.com/bifurcationkit/HclinicBifurcationKit.jl)
- for PDE solved with Gridap.jl, check [GridapBifurcationKit.jl](https://github.com/bifurcationkit/GridapBifurcationKit)
- for multi-parameter continuation, check [MultiParamContinuation.jl](https://github.com/bifurcationkit/MultiParamContinuation.jl)  

## SciML Integration

**BifurcationKit.jl** is listed in third party parameter analysis of [SciML Docs](https://docs.sciml.ai/DiffEqDocs/stable/#DifferentialEquations.jl:-Efficient-Differential-Equation-Solving-in-Julia) under the "Analysis" menu. [ModelingToolkit.jl](https://docs.sciml.ai/ModelingToolkit/stable/tutorials/bifurcation_diagram_computation/) and [Catalyst.jl](https://docs.sciml.ai/Catalyst/stable/steady_state_functionality/bifurcation_diagrams/) rely on **BifurcationKit.jl** as external dependency.
