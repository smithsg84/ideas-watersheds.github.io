---
layout: page_research
title: Research Activities
permalink: /research/
hero_image: /img/hero_research.jpg
hero_height: is_fullheight

---

<style>
    .wrapper {
        display:grid;
        grid-template-columns: 60% 40%;
        grid-gap: 1em;
        text-align:left;
        vertical-align:middle;
    }
    .wrapper > div{
        padding: 1em;
    }
    .wrapper > div:nth-child(odd){
    }
    .wrapper2 {
        display:grid;
        grid-template-columns: 30% 70%;
        grid-gap: 1em;
        text-align:left;
        vertical-align:middle;
    }
    .wrapper2 > div{
        padding: 1em;
    }
    .wrapper2 > div:nth-child(odd){
    }
</style>

# Watersheds are central to the U.S. Department of Energy’s Environmental Systems Science (ESS) mission
<p>
Water resources are critically important for energy production, drinking water, agriculture, and ecosystem health, but they are under increasing pressure from growing demand, land-use change, and Earth system change. Watershed-focused Science Focus Area (SFA) projects within the U.S. Department of Energy’s Environmental Systems Science (ESS) program are advancing a robust, predictive understanding of how watersheds function and respond to perturbations as integrated hydro-biogeochemical systems. 
</p><p>
By tightly integrating observations, experiments, and modeling, ESS advances systems-level understanding of how watersheds function and translates that understanding into advanced science-based models of watershed systems. The <strong>IDEAS–Watersheds</strong> project enables scientific software development by building new applications from reusable, robust, and scalable software components and libraries, using the best available software development practices and tools.
</p>

<div class = "wrapper2">


      <div><left><br><br>
      <strong><em>Unique Capabilities</em></strong>
      <ul>
        <li> Biogeochemistry</li>
        <li> Microbial processes</li>
        <li> Integrated flow and reactive transport modeling</li>
        <li> Model/data integration</li>
        <li> High-performance computing</li>
        </ul></left></div>

      <div><right>
        <img src="/img/EBSD0412_partnerships2023v2.png">
        </right></div>
</div><br>

# Three Partnership Activities with ESS’s interdisciplinary SFAs 
IDEAS–Watersheds is organized around three partnership activities and four shared infrastructure activities to address important scientific challenges and advance software development methodologies and engagement in the growing community-driven software ecosystem. Each partnership activity is undertaken jointly with one of ESS’s interdisciplinary Science Focus Area (SFA) projects at Lawrence Berkeley National Laboratory (LBNL), Oak Ridge National Laboratory (ORNL), and Pacific Northwest National Laboratory (PNNL). These activities address hydro-biogeochemical function of watersheds across a wide range of scales and over disparate climate and land-use conditions. The Shared Infrastructure activities address the sustainability of the software ecosystem through the Software Stewards’ activity, developing nationally consistent data sets in the Integrated Hydrologic Simulation Infrastructure (IHSI) activity, addressing land surface model integration with Integrated Hydrology in the Land Model Interface (LMI) activity, and training.

- [**LBNL Watershed Function SFA: East River Use Case**](/research/lbnl-sfa.md) –  The Watershed Function SFA seeks to understand how mountainous watersheds retain and release water, carbon and nutrients. The IDEAS-Watersheds Partnership with the Watershed Function SFA aims to extend existing watershed-scale modeling capabilities to incorporate process models for multicomponent reactive transport and plant-microbe-soil interactions, including the associated feedback processes on water (e.g. evapotranspiration) carbon and nutrient fluxes. These capabilities include both the software tools and workflows required to enable this framework.
- [**ORNL Watershed Dynamics and Evolution (WaDE)  SFA**](/research/ornl-sfa.md) – The IDEAS-Watersheds Partnership with ORNL’s WaDE SFA is advancing multiscale modeling approaches for understanding watershed hydro-biogeochemical dynamics under a range of hydrologic regimes, focusing on oxygen dynamics and metabolism in stream networks that drain heterogeneous land covers. The partnership is implementing multiscale models for stream metabolism and comparing those models to oxygen dynamics from sensor networks, and it is adding the capability to model burial, resuspension, and transport of sediment-associated solutes to the Advanced Terrestrial Simulator (ATS). This capability is of interest across the watershed-focused projects of ESS because significant transport of carbon, nutrients and trace elements occurs as suspended sediment or sorbed to suspended sediment.
- [**PNNL River Corridor SFA: Columbia River Use Case**](/research/pnnl-sfa.md) – River corridor science is conducted in the context of larger watershed processes that define boundary fluxes and exert other controls on hydrological exchange. These controls include interactions among variable river surface elevation (“stage”), hydromorphic setting, and hydrogeological heterogeneity. To determine how these processes and interactions influence river corridor hydro-biogeochemical function, models must include land-surface and groundwater processes over domains much larger than the river corridor itself. The partnership activity with the PNNL SFA aims to enable fundamental understanding of the hydro-biogeochemical function of dynamic river corridor ecosystems and translate that understanding into predictive, interoperable models across watersheds.

The three regional SFAs share a long-term objective of elucidating how surface water/groundwater exchanges across a range of temporal and spatial scales control watershed-scale biogeochemical cycling.

**Common near-term modeling activities for the interdisciplinary SFAs focus on**

- surface water and groundwater exchange in watershed headwaters and stream/river corridors,
- how biogeochemical processes in spatially limited metabolically active zones interact with steady and unsteady hyporheic exchange flows to control reach-to-watershed-scale export of nutrients and inorganic contaminants, and
- developing multiscale strategies that allow coupled hydrologic and biogeochemical processes to be represented at their native scales but expressed at watershed scale, rather than the current status of hydrologic modeling at large scale and biogeochemical modeling at smaller scales.

# Shared Infrastructure Activities

#### Software Stewards Activity

Software Stewards are responsible for coordinating software development, maintenance, testing, and deployment activities for the primary simulation codes and workflow tools. This activity is critical to the sustainability of the software ecosystem, and its effective use by the broader watershed modeling community.

<div class = "wrapper">

      <div><left><ul>
        <li> New capabilities are integrated, tested, and included in regular releases.</li>
        <li> Code reviews are integrated into the development workflow.</li>
        <li> Regular releases of  the software are made with persistent versioning (e.g., DOI)</li>
        <li> Documentation and tutorials are maintained and improved.</li>
        <li> Deployments of the entire software ecosystem that make it easier to access and use.</li>
        </ul></left></div>

      <div><right>
        <img src="/img/software_steward.png">
        </right></div>
</div><br>

#### Land Model Interfaces (LMI) Activity

The need for integrated hydro-terrestrial models that combine coupled surface/subsurface flow (Integrated Hydrology Models - IHMs) with the vegetative and ecosystem processes found in Land Surface Models (LMs) has exploded creating an array of incomplete solutions and fragmentation that is challenging for users. 

<div class = "wrapper">

      <div><left><img src="/img/int_hydro.png"></left></div>

      <div><right><br><br>
        A key deliverable is a workshop that brings the Integrated Hydrology and Land Surface modeling communities together to chart an effective path forward.
        </right></div>
</div><br>

#### Integrated Hydrologic Simulation Infrastructure (IHSI) Activity 

To accelerate development and evaluation of watershed and regional models we address the need for consistent datasets and tools that can be used across watersheds for modeling water, energy fluxes and transport. A key deliverable is spatially consistent subsurface hydrogeology datasets designed for hydrologic modeling up to the continental scale available through ESS-DIVE.

<div class = "wrapper2">

      <div><left><br><br><ul>
        <li> Extensive testing at the watershed scale across diverse hydrogeologic settings. </li>
        <li> Building workflow tools to subset national simulations and support watershed scale simulations </li>
        </ul></left></div>

      <div><right>
        <img src="/img/IHSI.png">
        </right></div>
</div><br>

# Training Activity

The cohort of early career scientists jointly funded by IDEAS-Watersheds and the SFA Partnerships, as well as early career scientists involved in IHSI and LMI, participate in a variety of collaborative activities, including:

- Monthly meetings on Software Development Best Practices cover topics relevant to both workflow tools and simulation codes including, version control, continuous integration and testing, parallel debugging and visualization.

- Monthly meetings on Modeling Case Studies raise awareness of the challenges and approaches to process-based modeling, sharing our experiences and stimulating new collaborations on synergistic topics across the project.

- Short courses for the primary codes are increasingly available online and are expanding to include more material on workflows and coupled simulations, such as ATS-PFLOTRAN.

[Learn More](/resources/outreach.md)
<br><br>

#### Community Building and Broader Outreach

IDEAS-Watersheds supports a wide range of activities, including a leadership role in the ESS Cyberinfrastructure Working groups, community benchmarking and model-intercomparison studies, and interagency collaboration.

<br>

[IDEAS-Classic](https://ideas-productivity.org/ideas-classic)<br>
[IDEAS](https://ideas-productivity.org)


