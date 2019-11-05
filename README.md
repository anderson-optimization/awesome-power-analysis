# Awesome Power Analysis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/andersonopt/awesome-power-analysis)

Awesome Power Analysis is for collecting power analysis related sources, including power flow, production cost modeling, etc.

**Welcome to contribute. Let's make it better.** Please follow the [Contributing Guidelines](https://github.com/sshuair/awesome-gis/blob/master/ContributingGuidelines.md).

Inspired by [Awesome GIS](https://github.com/sshuair/awesome-gis).

**Table Of Contents:**

- [Power Flow](#power-flow)
- [Production Cost Modeling](#production-cost-modeling)
- [Simulation Tool](#simulation-tool)
- [Data](#data)
- [Modeling & Optimization](#modeling-and-optimization)
- [Solvers](#solvers)


----




## Power Flow
- [MatPower](http://www.pserc.cornell.edu/matpower/) - MATPOWER is a package of free, open-source Matlab-language M-files for solving steady-state power system simulation and optimization problems such as power flow (PF), continuation power flow (CPF), extensible optimal power flow (OPF), unit commitment (UC) and stochastic, secure multi-interval OPF/UC.
- [PyPSA](https://github.com/PyPSA/PyPSA) - PyPSA stands for "Python for Power System Analysis". It is pronounced "pipes-ah".
- [pandapower](https://github.com/e2nIEE/pandapower) - pandapower combines the data analysis library pandas and the power flow solver PYPOWER to create an easy to use network calculation program aimed at automation of analysis and optimization in power systems.
- [PYPOWER](https://github.com/rwl/PYPOWER) - _not actively maintained_ - PYPOWER is a power flow and Optimal Power Flow (OPF) solver. It is a port of MATPOWER to the Python programming language.
- [GAMS - PSOPT](https://www.gams.com/latest/psoptlib_ml/libhtml/index.html) - This is a listing of the models available in the on-line model library (PSOPTLIB) based on the book Power System Optimization Modelling in GAMS by Alireza Soroudi.
- [NEOS - Optimal Power Flow](https://neos-guide.org/content/optimal-power-flow) - The Optimal Power Flow (OPF) model represents the problem of determining the best operating levels for electric power plants in order to meet demands given throughout a transmission network, usually with the objective of minimizing operating cost.

## Production Cost Modeling
- [PyPSA](https://github.com/PyPSA/PyPSA) - PyPSA stands for "Python for Power System Analysis". It is pronounced "pipes-ah".
- [Plexos](https://energyexemplar.com/products/plexos-simulation-software/) - Plexos uses mathematical multi-commodity optimization to provide a high-performance, robust simulation system for electric power, water and gas.
- [AuroraXMP](https://energyexemplar.com/products/aurora-simulation-software/) - Aurora is a comprehensive and reliable electricity price forecasting and analysis tool. 
- [Enelytix](http://www.enelytix.com/) - Enelytix integrates a best-in-class power-system simulation engine with data services, scalable and on-demand compute resources and state-of-the-art business analytics tools.  Powered by PSO
- [PSO](http://psopt.com/pso/) - Polaris' PSO is a production cost market simulator that supports the modeling of multi-level, nested time intervals that simultaneously optimize energy and ancillary services dispatch, and can simulate uncertainties.
- [LCG Consulting](http://www.energyonline.com/) - Consulting and Software for competitive energy markets.

## Simulation Tool
- [OpenDSS](http://smartgrid.epri.com/SimulationTool.aspx) - The OpenDSS is a comprehensive electrical power system simulation tool primarly for electric utility power distribution systems. It supports nearly all frequency domain (sinusoidal steady‐state) analyses commonly performed on electric utility power distribution systems. In addition, it supports many new types of analyses that are designed to meet future needs related to smart grid, grid modernization, and renewable energy research. 
- [OpenDSSDirect](https://github.com/NREL/OpenDSSDirect.py) - OpenDSSDirect.py is a cross-platform Python package implements a "direct" library interface to OpenDSS. 
- [PowerWorld](https://www.powerworld.com/) - PowerWorld's wide range of products provide the tools needed by transmission planners, power marketers, system operators and trainers, educators, and anyone else desiring access to power system information and analysis in a user-friendly format.

## Microgrid
- [HOMER](https://www.homerenergy.com/) - HOMER is the global standard for microgrid and distributed energy system design.


## Data
- [Reliability Test System](https://github.com/GridMod/RTS-GMLC) - Reliability Test System - Grid Modernization Lab Consortium
- [RTS 2019 update](https://ieeexplore.ieee.org/document/8753693) - RTS Update
- [pyiso](https://github.com/WattTime/pyiso) - pyiso provides Python client libraries for ISO and other power grid data sources. It powers the WattTime API (https://api.watttime.org/), among other things.
- [dsgrid](https://www.nrel.gov/analysis/electrification-futures.html) - a new model developed for the EFS and in recognition of a general need for a more detailed understanding of electricity load. dsgrid utilizes a suite of bottom-up engineering models across all major sectors to develop hourly electricity consumption profiles for every county in the contiguous United States.

## Benchmarks
- [Power Grid Lib](https://power-grid-lib.github.io/) - Benchmarks for Validating Power System Algorithms
- [Benchmarks for OPF Problem](https://github.com/power-grid-lib/pglib-opf) - 
This benchmark library is curated and maintained by the IEEE PES Task Force on Benchmarks for Validation of Emerging Power System Algorithms and is designed to evaluate a well established version of the the AC Optimal Power Flow problem. 

## Visualization
- [MAGMA](https://github.com/NREL/MAGMA) - Multi-area Grid Metrics Analyzer
- [ac-powerflow-vis](https://github.com/ccoffrin/ac-powerflow-vis) - Visualizations of AC Power Flow over a Line

## Modeling & Optimization
- [JuMP](https://github.com/JuliaOpt/JuMP.jl) - Modeling language for Mathematical Optimization (linear, mixed-integer, conic, semidefinite, nonlinear)
- [StructJuMP](https://github.com/StructJuMP/StructJuMP.jl) - A block-structured optimization framework for JuMP
- [Pyomo](http://www.pyomo.org/) - Pyomo is a Python-based, open-source optimization modeling language with a diverse set of optimization capabilities.
- [Gams](https://www.gams.com/) - The General Algebraic Modeling System (GAMS) is a high-level modeling system for mathematical optimization. GAMS is designed for modeling and solving linear, nonlinear, and mixed-integer optimization problems.
- [AMPL](https://ampl.com/) - Build optimization into your large-scale applications — quickly and reliably — using AMPL’s powerful yet intuitive algebraic modeling system.
- [PowerSystems.jl](https://github.com/NREL/PowerSystems.jl) - Data structures in Julia to enable power systems analysis
- [PowerModels.jl](https://github.com/lanl-ansi/PowerModels.jl) - PowerModels.jl is a Julia/JuMP package for Steady-State Power Network Optimization. 
- [ThreePhasePowerModels.jl](https://github.com/lanl-ansi/ThreePhasePowerModels.jl) - A Julia/JuMP Package for Three Phase Power Network Optimization

## Solvers
- [DSP](https://github.com/Argonne-National-Laboratory/DSP) - An open-source parallel optimization solver for stochastic mixed-integer programming
- [Gurobi](http://www.gurobi.com/index) - The Gurobi Optimizer was designed from the ground up to be the fastest, most powerful solver available for your LP, QP, QCP, and MIP (MILP, MIQP, and MIQCP) problems. 
- [IBM CPLEX](https://www.ibm.com/analytics/cplex-optimizer) - IBM ILOG CPLEX Optimization Studio provides powerful modeling tools to convert business problems to optimization models and solve  the breadth of optimization problems.
- [FICO Xpress](http://www.fico.com/en/products/fico-xpress-optimization) - FICO’s deep portfolio of optimization options enables users to easily build, deploy and use optimization solutions that meet their needs. 


## Misc
- [NREL Data and Tools](https://www.nrel.gov/analysis/data-tools.html) - NREL energy analysis data and tools.

## Reference:
>1. [Power Flow Study](https://en.wikipedia.org/wiki/Power-flow_study)
>2. [Power Systems Analysis Software Wiki](https://wiki.openelectrical.org/index.php?title=Power_Systems_Analysis_Software)