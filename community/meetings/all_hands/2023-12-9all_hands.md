---
layout: page_community
title: IDEAS-Watersheds Phase 2 All Hands 2023
permalink: /community/meetings/all_hands
hero_image: /img/black.jpg
hero_height: is_fullheight

---

<style>
    .wrapper {
        display:grid;
        grid-template-columns: 50% 50%;
        grid-gap: 1em;
        text-align:left;
        vertical-align:middle;
    }
    .wrapper > div{
        padding: 1em;
    }
    .wrapper > div:nth-child(odd){
    }
</style>

<body>
    <div class = "wrapper">

    	<div><left><br><br>
        <h4>Date: December 9-10, 2023<br>
        Location: Stanford University, Green Earth Sciences Building
        <br>Address: 367 Panama Mall Stanford Room: 365
        <br><a href="https://campus-map.stanford.edu">Campus Map</a> 
        </h4></left></div>

        <div><right>
        <img src="/img/photos/all_hands_group_photo.png" align="right"><br>
        </right></div>

    </div>
</body>

# Meeting Agenda:

#### Day 1: Saturday Noon-5PM (PST)

|Wall Clock (PT) |  Elapsed Time (min)    | Talks/Activity
|:---------------|:-----------------------|:-----------------------------------------------------|
|12:00|15|Introductions and Project Overview|
|12:15|??|Icebreaker Activities|
||**SFA Partnership Updates**||
|1:00|8+2|LBNL Watershed Function SFA: Sergi Molins|
|1:10|8+2|ORNL Watershed Dynamics and Evolution SFA: Scott Painter|
|1:20|8+2|PNNL River Corridor SFA: Xingyuan Chen|
|1:30|8+2|Shared Infrastructure: David Moulton|
|1:40|20|Group discussion and activities|
||**Break (2:00 - 2:30)**||
||| **Hands - On:** Integrated Hydrology + RTM (Lead: Sergi Molins)<br>**Duration:** 2 - 2.5 hours <br>**Details:** Including objectives and instructions are in available in the [README.md](https://github.com/IDEAS-Watersheds/integrated-reactive-transport-hands-on/blob/main/README.md)|
|2:30||Set up an integrated tracer transport problem in a column building on ATS integrated hydrology inputs (Sergi)|
|||Set up and test a geochemical problem in PFLOTRAN (Glenn) docker run -p 8888:8888 pflotran/jupyter:ideas-dec23-all-hands|
|||Set up a reactive transport problem building on the column simulation and PFLOTRAN inputs, LIVE! debugging (Sergi and Glenn)|
|||Set up more complex simulations: the hillslope example (Sergi)|
||**Break**||
||**Adjourn**||

<br><br>
#### Day 2: Sunday 9:00 AM -- 5PM (PST)

|Wall Clock (PT) |  Elapsed Time (min)    | Talks/Activity
|:---------------|:-----------------------|:-----------------------------------------------------|
||**Flash Talks**|**(Note: the order of the talks will be adjusted once we have all the titles and a natural sequence of topics can be ascertained).**|
|9:00|4+1|Phong Le (ORNL) A Multiscale Integrated Model for Transport in River Basins|
|||Saubhagya Rathore (ORNL) Spatially Resolved Integrated Hydrology Modeling for Managed Watersheds|
|||Jesus Gomez Velez (ORNL) Nitrate uptake in the benthic biolayer of streams and rivers across Conterminous US|
|||Zhi Li (PNNL) Modeling the fates of pyrogenic carbon in the wildfire-impacted watersheds using ATS-PFLOTRAN|
|||Tasneem Ahmadullah (PNNL) Organic Carbon Speciation in Microbial Respiration Using Lambda-PFLOTRAN Pipeline|
|||Mingjie Shi (PNNL) Ecosystem responses to wildfires in the Columbia River basin|
|||Lijing Wang (LBNL) Understanding Hydrologic Variability in Mountainous Hillslopes: From Intensive Monitoring to Scaling Up.|
|||Dipankar Dwivedi (LBNL) Reactive Transport Benchmarks for Problems Involving Gaseous Species.|
|||Andrew Graus (LBNL) Status update on coupling a fine-scale process-based ecosystem model (EcoSIM) with the Advanced Terrestrial Simulator (ATS).|
|||Luwen Wan (Stanford) Quantifying beaver-induced water storage across scales.|
|||Discussion|
|**10:00-10:30**| **Break: 10 minutes**||
|||**Hands-On:** WW and Mixed-Polyhedral meshing (Lead: Saubhagya Rathore) <br>**Duration:** 2 - 2.5 hours <br>**Details:**  Including objectives and docker setup is [here](https://github.com/environmental-modeling-workflows/workshop-watershed-workflow/blob/main/README.md).|
|10:30||Introduction to Watershed Workflow|
|||Exploring Key Conceptual Objects|
|11:15||**Hands-On Session:** Generating Stream-Aligned Mixed-Polyhedral Mesh|
|||Defining Regions and Labeled Sets|
|12:15||Debugging and Manipulating Key Objects|
|||Discussion and Feedbacks|
|**Lunch**| **1-2**||
|||**Hands-On:**  IHSI subsetting CONUS 2.0 data and simulation output <br> **Duration:** 2 - 2.5 hours <br> **Details:** Including objectives and docker instructions are in available in the [README.md](https://github.com/gartavanis/IDEAS-watersheds/blob/main/README.md)|
|2:00||Overview of new datasets, CONUS2|
|||Presentation of the new tools, the HydroFrame and HydroData and SubsetTools frameworks|
|||Hands-on subset tools/hf_hydrodata sessions with Docker|
|||Discussion/Feedback|
||**Group discussion:**| **What’s next, what do you need, what’s slowing you down? (~1 hour)**|
|4:00|||
|**Adjourn**|||

<br><br>
### Notes and Instructions:
#### Proposal

The proposal (without detailed budget justifications) is available to the team 
[(IDEAS-Watersheds Phase 2 proposal)](https://drive.google.com/file/d/11Gz84BGBhUAIVJ73RDJrYMDro7IyUbs9/view?usp=share_link)

#### Team Flash Slide Introductions:  
Each team member is asked to develop a single slide as a fun, high-level work/life introduction following the template [Flash-Slide-Example](https://docs.google.com/presentation/d/1CWrVkBb3Fd-Xzlnb1W3zj_a_oCZXprCS/edit?usp=share_link&ouid=107331554827372386937&rtpof=true&sd=true).  It may also be helpful to review examples from the leads [Flash-Slide-Folder](https://drive.google.com/drive/folders/1B7HwQop3_QFDiVTTceTpZtJmWxorXT5x?usp=share_link).  We’ll combine these into a single slide show on Sunday prior to the meeting,  and you’ll have 30 seconds to present as part of this icebreaker.  
Everyone will have access to the slides for future reference.

#### Discussion and Group Activities:
Google docs will be provided to help collect feedback and questions and record the discussion.
Link for online polling:  [pollev.com/nicolejeffery580](https://pollev.com/nicolejeffery580) (Note: polling no longer active)

<br><br>
### IDEAS-Watersheds Team 2024 <Update>

|Name |Email |In Person |Partnership/Research Activity
|:---------------|:-----------------------|:-------------------------|:---------------------------|
|David Moulton|moulton@lanl.gov|yes / yes|Leadership / Software Ecosystems|
|Scott Painter|paintersl@ornl.gov|yes / yes|Leadership / ORNL SFA|
|Sergi Molins|smolins@lbl.gov|yes / yes|Leadership / LBNL SFA / Software Ecosystems|
|Kate Maher|kmaher@stanford.edu|yes/yes|Leadership / SLAC SFA|
|Xingyuan Chen|xingyuan.chen@pnnl.gov|yes/yes|Leadership / PNNL SFA|
|Reed Maxwell|reedmaxwell@princeton.edu|no / yes|Leadership / IHSI|
|Laura Condon|lecondon@email.arizona.edu|no / yes|Leadership / IHSI|
|Steve Smith|smith84@llnl.gov|virt / yes|Leadership / Software Ecosystems|
|Ethan Coon|coonet@ornl.gov|virt / virt|Leadership / ORNL SFA / Software Ecosystems/IDEAS Watersheds|
|Glenn Hammond|glenn.hammond@pnnl.gov|yes/yes|Leadership / PNNL SFA / Software Ecosystems|
|Nicole Jeffery|njeffery@lanl.gov|no / no|Leadership|
|Zexuan Xu|zexuanxu@lbl.gov|yes/yes|LBNL SFA|
|Erica Siirila-Woodburn|ERWoodburn@lbl.gov|virt/virt|LBNL SFA/IDEAS-Watersheds |
|Dipankar Dwivedi|ddwivedi@lbl.gov|yes/yes-virt|LBNL SFA|
|Andrew Graus|agraus@lbl.gov|yes/yes|LBNL SFA|
|Jinyun Tang|JinyunTang@lbl.gov|yes/no|LBNL SFA/IDEAS-W?|
|Saubhagya Rathore|rathoress@ornl.gov|yes/yes|ORNL SFA|
|Jesus Gomez Velez|gomezvelezjd@ornl.gov|yes/yes|ORNL SFA|
|Phong Le|lepv@ornl.gov|yes/yes|ORNL SFA|
|Zhi Li|zhi.li@pnnl.gov|virt/virt|PNNL SFA|
|Katie Muller|katherine.muller@pnnl.gov|no/no|PNNL SFA|
|Tasneem Ahmadullah|tasneem.ahmadullah@pnnl.gov|yes/yes|PNNL SFA|
|Mingjie Shi|mingjie.shi@pnnl.gov|yes/yes|PNNL SFA|
|Hyun-Seob Song|hsong5@unl.edu|no/no|PNNL SFA|
|Zach Perzan|zperzan@stanford.edu|yes/yes|SLAC SFA|
|Luwen Wan|luwenwan@stanford.edu|yes/yes|SLAC SFA|
|Lijing Wang|Lijing.Wang@lbl.gov|yes/yes|SFA / IDEAS-W team|
|Adam Atchley| aatchley@lanl.gov|yes/yes|IDEAS Watersheds|
|Svetlana Tokareva|tokareva@lanl.gov|virt/virt|IDEAS Watersheds/InteRFACE|
|Erica Hinrichs|new RSE|yes/yes|IDEAS-Watersheds|
|Rich Fiorella|rfiorella@lanl.gov|yes/yes|IDEAS-Watersheds/COMPASS-GLM|
|Daniil Svyatsky|dasvyat@lanl.gov|yes/yes|IDEAS-Watersheds/COMPASS-GLM|
|Chen Yang|chen_yang@princeton.edu|no/no| IHSI|
|George Artavanis|ga6@princeton.edu|no/yes|IHSI|

