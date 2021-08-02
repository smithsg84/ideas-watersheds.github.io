---
layout: page
title: Amanzi
show_sidebar: false
menubar: softwares
hero_image: /../img/black.jpg
hero_height: is_fullheight
---

#### Amanzi [<i class="fas fa-book"></i>](https://amanzi.github.io/) [<i class="fab fa-github"></i>](https://github.com/amanzi/amanzi) 
A flexible and extensible flow and reactive transport simulation capability for environmental applications.  It includes general polyhedral mesh infrastructure, provides advanced nonlinear solvers, such as Nonlinear Krylov Acceleration (NKA) and Anderson Acceleration, and leverages Trilinos-ML and Hypre Algebraic Multigrid for scalable solvers.  The multiphysics framework, Arcos, provides a flexibility for hierarchical weak and strong coupling of processes with subcycling.  Geochemistry support is provided through the Alquimia interface library and can use the geochemistry engine from PFLOTRAN or CrunchFlow. The code is parallel and  leverages Trilinos and PETSc.   Amanzi is used to model contaminant migration at various DOE waste sites (e.g., Hanford, and Savannah River), and is generally applicable to groundwater contaminant migration under partially saturated, nonisothermal conditions and its interaction with surface water.   Amanzi is jointly developed by LANL, LBNL, and PNNL, and ORNL as an open source project under the three-clause BSD license

#### Performance Runs

These performance runs were conducted utilizing LANL's Darwin HPC cluster, enfasizing on Intel CPUs Haswell, Skylake and Icelake. The same Amanzi tutorial problem was ran nine times on each CPU, each time with an increasing amount of cores, starting at two cores and ending at twenty. The end result were two graphs, a Speed Up graph and the average times graph. The Speed Up graph shows the speed at which each CPU does the tutorial problem, keeping in context the perfect speed up line. The average times graph displays a simple comparison between the average times each CPU took to complete the problem.


This was done to showcase and compare the speed at which each CPU completed the tutorial problem. The problem utilized for these performance runs was the second tutorial problem featured in Amanzi's website, named "Transient vadose zone flow and Tc-99 transport tutorial problem". The problem itself is about how low-level radioactive waste containing Tc-99 was dumped into two unlined cribs, and how the goal is to predict the concentration of Tc-99 at the water table in 2100. Amanzi then simulates the evolution of the Tc-99 plume over time.

![SpeedUp Graph](/img/amanzi speed up.png)

![Average Time Graph](/img/amanzi average times.png)