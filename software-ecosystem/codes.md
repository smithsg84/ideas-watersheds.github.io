---
layout: page
title: IDEAS Watersheds Codes
hero_image: /../img/black.jpg
hero_height: is_fullheight

---
<style>
    .wrapper {
        display:grid;
        grid-template-columns: 25% 25% 25% 25%;
        grid-gap: 1em;
    }
    .wrapper > div{
        background:#eee;
        padding: 1em;
    }
    .wrapper > div:nth-child(odd){
        background:#ddd;
    }
</style>
<body>
    <div class = "wrapper">
        
        <div><center>
        <h3><a href="/software-ecosystem/codes/alquimia"> Alquimia </a></h3>
        <img src="../../img/code_alquimia.png" align="center"><br>
        A biogeochemistry Application Program Interface and wrapper library. 
        </center></div>

        <div><center>
        <h3><a href="/software-ecosystem/codes/amanzi"> Amanzi  </a></h3>
        <img src="../../img/code_amanzi.png" align="center"><br>
        A flexible and extensible flow and reactive transport simulation capability for environmental applications.
        </center></div>

        <div><center>
        <h3><a href="/software-ecosystem/codes/ats">Amanzi-ATS  </a></h3>
        <img src="../../img/code_ats.png" align="center"><br>
        Advanced Terrestrial Simulator (ATS) - for solving ecosystem-based, integrated, distributed hydrology.
        </center></div>

        <div><center>
        <h3><a href="/software-ecosystem/codes/crunchflow"> CrunchFlow   </a></h3>
        <img src="../../img/code_crunchflow.png" align="center"><br>
        An open-source software package for simulating reactive flow and transport.
        </center></div>

        <div><center>
        <h3><a href="/software-ecosystem/codes/ecoslim"> EcoSLIM  </a></h3>
        <img src="../../img/code_ecoslim.png" align="center"><br>
        A Lagrangian particle-tracking model designed to operate with integrated hydrologic models.
        </center></div>

        <div><center>
        <h3><a href="/software-ecosystem/codes/parflow"> ParFlow </a></h3>
        <img src="../../img/code_parflow.png" align="center"><br>
        The integrated watershed model, solves saturated and variably saturated flow in three dimensions.
        </center></div>

        <!-- <div><center>
        <h3><a href=""> ParFlow-CLM </a></h3>
        ParFlow coupled to the land-surface model CLM.
        </center></div> -->
        
        <div><center>
        <h3><a href="/software-ecosystem/codes/pflotran"> PFLOTRAN </a></h3>
        <img src="../../img/code_pflotran.png" align="center"><br>
        An open-source, state-of-the-art massively parallel subsurface flow and reactive transport code.
        </center></div>
    </div>
</body>



<!--#### LaGriT ([Github](https://github.com/lanl/LaGriT))
A software tool for generating, editing and optimizing multi-material unstructured finite element grids; it also maintains the geometric integrity of complex input volumes, surfaces, and geologic data and produces an optimal grid (Delaunay, Voronoi) elements. The data structures used in the code are compact and powerful and expandable to include hybrid meshes (tet, hex, prism, pyramid, quadrilateral, triangle, line), however the main algorithms are for triangle and tetrahedral meshes. The LaGriT tools are used in many projects including ASCEM meshing for Amanzi, Discrete Fracture Networks (DFN), Arctic Permafrost, and Subsurface Flow and Transport models using FEHM and PFLOTRAN. [PyLaGriT](https://lanl.github.io/LaGriT/pylagrit/original/index.html) provides a python interface to LaGriT capabilities, making it easier to incorporate mesh generation in modeling workflows.

#### OpenFOAM ([URL](https://www.openfoam.com/))
Open source Computational Fluid Dynamics (CFD) software. It has an extensive range of capabilities to solve complex fluid flows involving turbulence, heat transfer and chemical reactions. It has established a large user community across most areas of engineering and Science.

#### ParFlow-CLM
ParFlow coupled to the land-surface model CLM (Ferguson et al., 2016; Jefferson & Maxwell, 2015; Jefferson et al., 2017; Reed M. Maxwell & Miller, 2005), provides a comprehensive representation of vegetation, snow, and land-atmosphere water and energy fluxes.  CLM is unique in the land surface modeling community because it is a module that is called from within ParFlow.  This modeling framework has been shown to represent the observed range of temporal scales and non-stationary behavior (R. M. Maxwell et al., 2015) making it appropriate for the proposed work. A 1 km lateral resolution ParFlow-CLM model of CONUS has been developed and used to evaluate large-scale controls on groundwater configuration and connections between lateral groundwater flow and land-surface partitioning (Laura E. Condon & Maxwell, 2015; L. E. Condon & Maxwell, 2017; Reed M. Maxwell & Condon, 2016; R. M. Maxwell et al., 2015). ParFlow-CLM is currently distributed with ParFlow through the GitHub repo. In the IDEAS project the CLM land model interface will be generalized and also be made available as a separate library that other codes in the eco-system can connect use still within the ParFlow GitHub repo.

#### Soil & Water Assessment Tool (SWAT) ([URL](https://swat.tamu.edu/))
A watershed model developed for the USDA Agricultural Research Service. SWAT can be used to predict the impact of land management practices on water, sediment and agricultural chemical yields in large complex watersheds. It can deal with varying soils, land use and management conditions over long periods of time.-->


