<h1> Computational Design </h1>
<div style="text-align: justify"> 
Our current researches in the area of optimisation and adoption of machine learning in DfAM mainly focus on the generation of function-graded materials (FGM) and MDO as well as the generation of support-free, topologically optimised structures with machine learning.
</div>


<h2> Machine Learning Aided Design </h2>
<h3 id="inverse-design_AW"> Machine learning based lattice generation method derived from topology optimisation </h3>
<div style="text-align:center">
<img src="/../_media/research/Amber_inversedesign.gif" style="width:95%">
</div>

<div style="text-align: justify"> 
We propose a novel lattice generation method that designs graded lattice structures with the assistance of Machine Learning (ML). 

* A Neural Network (NN)-based inverse lattice generator is trained to output lattice unit cells from the input of target mechanical properties. 
* Utilises information from fast low-resolution Topology Optimisation (TO) design to inform the trained inverse generator and map lattice cells. 
* The proposed method provides close to optimal performance whilst making the realisation of these solutions exceptionally quick. 
</div>

<b> Relevant Publication(s): </b>

J. Wang, A. Panesar, <i> Machine learning based lattice generation method derived from topology optimisation</i>, Additive Manufacturing Journal, Volume 60, (2022), 103238. https://doi.org/10.1016/j.addma.2022.103238

<hr>

<h3 id="batt-casing_AW"> Multidisciplinary design optimisation of lattice-based battery housing for electric vehicles </h3>
<div style="text-align:center">
<img src="/../_media/research/Amber_BatteryCase.jpg" style="width:95%">
</div>

<div style="text-align: justify"> 
In this study, a graded lattice design framework is developed based on Topology Optimisation (TO) to effectively tackle the multidisciplinary objectives associated with battery housing.

* Leverages the triply periodic minimal surfaces lattices, aiming for high mechanical stiffness and efficient heat dissipation considering heat conduction and convection. 
* Bridges the research gap by embedding thermal convection into the TO framework, while accounting for thermal conduction in thermal management.
* Demonstrated through the battery housing design, showcasing its ability to address multidisciplinary objectives as evidenced by the analysis of the Pareto front. 

This study identifies the potential of lattices in lightweight applications incorporating multiphysics and offers an efficient lattice design framework readily extended to other engineering challenges. 
</div>

<b> Key collaborators </b>: 

Members from Hamburg University of Applied Sciences (HAW): <a style = " white-space:nowrap; " href="https://www.haw-hamburg.de/en/university/employees/detail/person/person/show/thomas-kletschkowski/" target = "_blank">Thomas Kletschkowski</a>, <a style = " white-space:nowrap; " href="https://www.haw-hamburg.de/en/university/employees/detail/person/person/show/benedikt-plaumann/" target = "_blank">Benedikt Plaumann</a>, <a style = " white-space:nowrap; " href="https://www.haw-hamburg.de/en/university/employees/detail/person/person/show/maximilian-schutzeichel/" target = "_blank">Maximilian Schutzeichel</a>

<b> Relevant Publication(s): </b>

J. Wang, M. Schutzeichel , B. Plaumann, T. Kletschkowski, A. Panesar, <i>Multidisciplinary design optimisation of lattice-based battery housing for electric vehicles.</i> Scientific Report 14, 12265 (2024). https://doi.org/10.1038/s41598-024-60124-4 

<hr>

<h3 id="latent-space"> Smooth transition unit cell generation via latent-space arithmetic </h3>
<div style="text-align:center">
<img src="/../_media/research/latent_space.gif" style="width:100%">
</div>

<div style="text-align: justify"> 
A latent-space-arithmetic-based framework is proposed and developed in this project to generate smooth transition between dissimilar unit cells. It allows lattice structures with multiple unit cell types to be realised. 

* Variational Autoencoder (VAE) is trained to map the unit cells to the latent space
* The proposed strategy ensures both smoothness in transition and connectivity with the target cells.
* Transitions between different types of triply periodic minimal surface (TPMS) and truss-based unit cells can be generated.

Benchmark comparisons against analytical morphing and existing ML-based solutions indicate that the proposed framework consistently achieves superior performance.
</div>

<b> Relevant Publication(s): </b>

X. Yu, B. Peng, A. Panesar, <i> Smooth 3D transition cell generation based on latent space arithmetic</i>, (In preparation)

<hr>

<h3 id="PINN"> Multi-layer temperature history prediction during directed energy deposition using physics-informed neural network (PINN) </h3>
<div style="text-align:center">
<img src="/../_media/research/PINN_DED_gif.gif" style="width:95%">
</div>

<div style="text-align: justify"> 
This project implements a physics-informed neural network (PINN)-based solution framework that predicts the thermal history during a multi-layer Directed Energy Deposition (DED) process. 

* New opportunities for modelling the thermally induced distortion in metal AM with the meshless nature and the readily available derivative information from PINN solution.
* Overcomes the usual shortfall of neural networks (NNs) in dealing with discontinuities making multi-layer PINN-based simulation possible.
* Benchmark against ANSYS validates accuracy of the proposed framework to be comparable to numerical methods. Additionally, offering computational time-savings thereby making it amenable for use in design-optimisation algorithms.

The proposed framework sets the foundation for the subsequent exploration of applying scientific machine learning (SciML) techniques to real-life engineering applications. Furthermore, remarks on strategies to improve ease of training and prediction accuracy by PINN for the particular use case in DED temperature history prediction have been made. 
</div>

<b> Relevant Publication(s): </b>

B. Peng, A. Panesar, <i> Multi-scan thermal simulation using physics-informed neural network</i>, (Under review)



<h2> Topology Optimisation for Multi-physics Problems </h2>

<h3 id="battery_CK"> Discovery of next-generation battery electrodes using topology optimization </h3>
<div style="text-align:center">
<img src="/../_media/research/2023_08_CK_battery.gif" style="width:100%">
</div>

<div style="text-align: justify"> 
Efficient storage and deployment of renewable energy sources like solar and wind are essential for achieving global CO2 reduction targets as energy demand is projected to rise by 25% by 2030. Insertion-electrode batteries, such as sodium-ion and lithium-ion, are key advancements in energy storage systems, but their performance is often limited by ion and electron transport inefficiencies and mechanical damage to electrodes. Improving battery performance requires controlling electrode nanoarchitecture, which presents a complex design challenge across multiple disciplines, including electrochemistry, solid mechanics, materials science, and mathematical optimization. 

<b>Project at a glance:</b>

* Renewable energy storage is critical to meeting CO2 reduction targets amid rising energy demand.
* Insertion-electrode batteries like Na-ion and Li-ion are pivotal in advanced energy storage but face performance limitations. Optimising electrode nanoarchitecture is essential for enhancing battery capacity, rate capability, and cycle life.
* This research integrates electrochemistry, solid mechanics, materials science, and mathematical optimization for optimal design.


</div>

<b> Key collaborators </b>: 

Members from Imperial: <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.p.ryan" target = "_blank">Mary Ryan</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.shaffer" target = "_blank">Milo Shaffer</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.titirici" target = "_blank">Magda Titirici</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/i.stephens" target = "_blank">Ifan Stephens</a>;

Industry sponsor: Shell (contributor: <a style = " white-space:nowrap; " href="https://www.linkedin.com/in/peterklusener/" target = "_blank">Peter Klusener</a>) 

<b> Relevant Publication(s): </b>

C Imediegwu, MSP Shaffer, MP Ryan, A Panesar, <i>Modelling optimum thickness and architecture for lithium-ion battery cathodes</i>, Journal of Power Sources, 2024, 614, 235005 

<h3 id="bone_CK"> Topology optimisation of bespoke orthopaedic implants </h3>
<div style="text-align:center">
<img src="/../_media/research/ck_BoneImplantImage.png" style="width:90%">
</div>

<div style="text-align: justify"> 
Total Hip Arthroplasty (THA) is a surgical procedure to replace damaged hip joints, but a significant challenge is the need for costly revision surgeries due to implant failures, costing the UK's NHS over £60 million annually. The most common causes for revision are aseptic loosening and bone remodelling, both linked to inadequate implant design. This project aims to develop patient-specific implants using a multi-objective optimisation approach to minimize these risks by optimising implant topology. 

The collaboration between Imperial College London and the University of Birmingham integrates computational design, additive manufacturing, and experimental testing to create and validate functionally graded implants, potentially improving post-THA outcomes.

<b>Project at a glance:</b>

* THA revision surgeries are costly and often caused by risks of aseptic loosening and bone remodelling.
* The project aims to design patient-specific implants to reduce these revision risks. A multi-objective optimisation framework is proposed to find optimal implant topologies.
* Complementing computational design approach with additive manufacturing and experimental validation to test the optimised implants.

</div>

<b> Key collaborators </b>: 

Members from University of Birmingham: <a style = " white-space:nowrap; " href="https://www.birmingham.ac.uk/staff/profiles/metallurgy/attallah-moataz" target = "_blank">Moataz Attallah</a>, <a style = " white-space:nowrap; " href="https://www.birmingham.ac.uk/research/activity/metallurgy-materials/amplab/team" target = "_blank">Peter Ibrahim</a>

<b> Relevant Publication(s): </b>

<i>Topology Optimisation of bespoke lattice orthopaedic implants </i> (In preparation)


<!-- <h3 id="struc-power-comp"> Structural Power Composites </h3>
<div style="text-align:center">
<img src="/../_media/research/strucComp.gif" style="width:100%">
</div>

<div style="text-align: justify"> 
We have been collaborating with <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/e.greenhalgh" target = "_blank">Prof. Emile S Greenhalgh</a> on progressing <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/structural-power-composites/team/" target = "_blank">structural power composites</a>, particulalrly on the modelling and optimisation front. Our work has unravelled novel topologies for structual electrolyte materials which are considered pivotal for the development of structual batteries/supercapacitors. 
</div>

<b> Relevant Publication(s): </b>

C. Lee, E. S. Greenhalgh, M. S. P. Shaffer, A. Panesar, <i> Optimized microstructures for multifunctional structural electrolytes</i>, Multifunct. Mater., Volume 2, (2019), 045001, https://dx.doi.org/10.1088/2399-7532/ab47ed -->


<h2> Numerical Modelling </h2>

<h3 id="struc-power-comp"> Multiphysics Modelling for Structural Supercapacitors </h3>
<div style="text-align:center">
<img src="/../_media/research/shimeng_strucComp.png" style="width:100%">
</div>

<div style="text-align: justify"> 
We have been collaborating with <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/e.greenhalgh" target = "_blank">Prof. Emile S Greenhalgh</a> on progressing <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/structural-power-composites/team/" target = "_blank">structural power composites</a>, particulalrly on the modelling and optimisation front. Our work has unravelled novel topologies for structual electrolyte materials which are considered pivotal for the development of structual batteries/supercapacitors. 

A three-dimensional finite element model for structural supercapacitors (SSCs) was developed to understand the electrochemical behaviour of both SSC devices as well as different constituents. A range of factors for the design of SSCs were extensively studied, including the separator thickness and porosity, and electrode thickness and fibre volume fraction. A galvanostatic charge and discharging (GCD) test was performed on the proposed model to obtain the specific capacitance, specific energy and specific power of the SSC device. The simulation results were then validated with the experimental data from our previous work regarding the performance criteria mentioned above. In general, this electrochemical model sets the stepping stone for further electro-chemo-mechanical models for SSCs, as well as promotes the development of virtual certification of SSC devices. 
</div>

<b> Key collaborators </b>: 

Members from Imperial: <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/e.greenhalgh" target = "_blank">Emile S Greenhalgh</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.shaffer" target = "_blank">Milo Shaffer</a>, <a style = " white-space:nowrap; " href="https://profiles.imperial.ac.uk/anthony" target = "_blank">Anthony Kucernak</a>

<!-- <b> Relevant Publication(s): </b> -->
