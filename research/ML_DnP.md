<img width="891" height="34" alt="image" src="https://github.com/user-attachments/assets/f3a20857-1ad5-4596-9f4c-bf3bcb4a09c4" /><h1> ML in Design & Process</h1>

<h2 id="DATAML"> Scientific ML</h2>

<h3 id="PINN"> Multi-layer temperature history prediction during directed energy deposition using physics-informed neural network (PINN) </h3>
<div style="text-align:center">
<img src="/../_media/research/PINN_DED_gif.gif" style="width75%">
</div>

<details>
<summary>More details</summary>
<div style="text-align: justify"> 
This project implements a physics-informed neural network (PINN)-based solution framework that predicts the thermal history during a multi-layer Directed Energy Deposition (DED) process. 

* New opportunities for modelling the thermally induced distortion in metal AM with the meshless nature and the readily available derivative information from PINN solution.
* Overcomes the usual shortfall of neural networks (NNs) in dealing with discontinuities making multi-layer PINN-based simulation possible.
* Benchmark against ANSYS validates accuracy of the proposed framework to be comparable to numerical methods. Additionally, offering computational time-savings thereby making it amenable for use in design-optimisation algorithms.

The proposed framework sets the foundation for the subsequent exploration of applying scientific machine learning (SciML) techniques to real-life engineering applications. Furthermore, remarks on strategies to improve ease of training and prediction accuracy by PINN for the particular use case in DED temperature history prediction have been made.
</div>

<b> Relevant Publication(s): </b>

Peng B, Panesar A. <i> Multi-scan thermal simulation using physics-informed neural network </i> Additive Manufacturing. (2024) https://doi.org/10.1016/j.addma.2024.104498

Peng B, Panesar A. <i> Predicting temperature field for metal additive manufacturing using PINN </i> International Solid Freeform Fabrication Symposium. (2023) p. 881–96.

Peng B, Panesar A. <i> Multi-layer Thermal Simulation of Directed Energy Deposition using Physics Informed Neural Networks </i> Real-World Applications of AI and ML in Digital Engineering Seminar [Internet]. (2025) Coventry, United Kingdom: NAFEMS; 2025. Available from: https://www.nafems.org/downloads/dropbox/nologin/aiuk25/panesar_ext_abs.pdf

</details>

<h3 id="XPINN"> Extending multi-layer temperature history prediction to more complex DED configurations using eXtended PINNs (XPINNs) </h3> 
<div style="text-align:center">
<img src="/../_media/research/XPINN_DED.gif" style="width:90%">
</div>

<details>
<summary>More details</summary>
<div>
This work implements an eXtended PINNs (XPINNs)-based framework that utilises domain decomposition and demonstrates performance and capacity improvement over the PINN-based counterpart in multi-layer thermal history prediction of Directed Energy Deposition (DED) process.

* Significant improvement of prediction accuracy for multi-layer DED parts of simple geometry.
* Capability to account for complications such as dwell time and voids in design.
* Shares SciML-based framework’s meshless nature and immediate availability of derivative information.
* The scalable implementation of the framework allows a user defined number of sub-domains to be define. The code will be available shortly.

The proposed framework brings SciML-based framework for real-life DED applications one step closer with the expanded capability. Remarks on the appropriate level of domain decomposition are also made.  
</div>

<b> Relevant Publication(s): </b>

Peng B, Panesar A. <i> Multi-layer thermal history prediction framework for Directed Energy Deposition based on Extended physics-informed neural networks (XPINN) </i> Additive Manufacturing. (2025) Available from: https://doi.org/10.1016/j.addma.2025.104953

Peng B, Panesar A. Application of scientific machine learning techniques to metal additive manufacturing simulation: a comparison between PINN and XPINN. In: International Solid Freeform Fabrication Symposium (SFF). Austin, Texas; (2025)


</details>
<!-- NEXT SECTION -->
<h2 id="DDD"> Data Driven Design</h2>

<h3 id="TO_ML_FGMM">TO and ML-based optimisation to design FGMM</h3> 
<div style="text-align:center">
<img src="/../_media/research/ML_DnP-TO_ML_FGMM.png" style="width:90%">
</div>

<details>
<summary>More details</summary>
<div>
We propose a novel lattice generation method that designs Functionally Graded Matamaterials (FGMMs) with the assistance of Topology Optimisation (TO) and Machine Learning (ML).

* A Neural Network (NN)-based inverse lattice generator is trained to output lattice unit cells from the input of target mechanical properties.
* Utilises information from fast low-resolution Topology Optimisation (TO) design to inform the trained inverse generator and map lattice cells.
* The proposed method provides close to optimal performance whilst making the realisation of these solutions exceptionally quick.
</div>
</details>


<h3 id="benchmark"> Benchmark </h3>
<div style="text-align:center">
<img src="/../_media/research/Benchmarktable.png" style="width:95%">
</div>

<details>
<summary>More details</summary>
<div>We conducted a benchmark of our lattice generation approach by comparing with other approaches; dehomogenisation and inverse homogenisation

* Our approach has comparable optimal structure’s performance and the computational efficiency, compared to dehomogenisation.
* Ensure manufacturability of the obtained structure without overhang angle or grey scale region.
* Versatile for multiple manufacturable unit cells, opening possibility in wider application fields.

</div>

<b> Relevant Publication(s): </b>


</details>

<h3 id="ML_MM">ML-based inverse design of multi-material curved lattice structures</h3> 
<div style="text-align:center">
<img src="/../_media/research/ML_DnP-InvDesCurvLat.jpg" style="width:90%">
</div>

<details>
<summary>More details</summary>
<div>
In this work, we proposed a ML-based inverse design framework to realise multi-material curved lattice structures, enabling the optimisation of multifunctional FGMs.

* The proposed unit cell design parameterisation enables simultaneous optimisation of shape, size and material, offering vast property space beyond conventional VF grading.
* High accuracy and efficiency in property prediction and inverse design by ML models, capable in handling mixed-type design features and properties across different physics.
* The MDN enables one-to-many inverse design, allowing further filtering based on manufacturability or other criteria.
</div>
</details>

<h3 id="latentspace"> Smooth transition unit cell generation via latent-space arithmetic </h3> 
<div style="text-align:center">
<img src="/../_media/research/latent_space.gif" style="width:90%">
</div>

<details>
<summary>More details</summary>
<div>
A latent-space-arithmetic-based framework is proposed and developed in this project to generate smooth transition between dissimilar unit cells. It allows lattice structures with multiple unit cell types to be realised.
* Variational Autoencoder (VAE) is trained to map the unit cells to the latent space
* The proposed strategy ensures both smoothness in transition and connectivity with the target cells.
* Transitions between different types of triply periodic minimal surface (TPMS) and truss-based unit cells can be generated.
Benchmark comparisons against analytical morphing and existing ML-based solutions indicate that the proposed framework consistently achieves superior performance.

</div>
<b> Relevant Publication(s): </b>

Yu X, Peng B, Panesar A. <i> Smooth 3D transition cell generation based on latent space arithmetic </i> Additive Manufacturing. (2025) https://doi.org/10.1016/j.addma.2025.104714
</details>


<h3 id="inverse-design_AW"> Machine learning based lattice generation method derived from topology optimisation </h3>
<div style="text-align:center">
<img src="/../_media/research/Amber_inversedesign.gif" style="width:95%">
</div>

<details>
<summary>More details</summary>
<div>
We propose a novel lattice generation method that designs graded lattice structures with the assistance of Machine Learning (ML). 

* A Neural Network (NN)-based inverse lattice generator is trained to output lattice unit cells from the input of target mechanical properties. 
* Utilises information from fast low-resolution Topology Optimisation (TO) design to inform the trained inverse generator and map lattice cells. 
* The proposed method provides close to optimal performance whilst making the realisation of these solutions exceptionally quick. 
</div>

<b> Relevant Publication(s): </b>

Wang J, Panesar A, <i> Machine learning based lattice generation method derived from topology optimisation</i> Additive Manufacturing. (2022) https://doi.org/10.1016/j.addma.2022.103238

</details>


<!-- TEMPLATE FOR EACH PROJECT -->
<!-- 
<b id="add_id"> PROJECT TITLE </b> 
<div style="text-align:center">
<img src="/../_media/research/FIG_NAME.gif" style="width:50%">
</div>

<details>
<summary>More details</summary>
<div>
INSERT DESCRIPTION AND FIGURE(S)
</div>

<b> Relevant Publication(s): </b>

Author, <i> TITLE </i> (YEAR) https://doi.org/10.1016/j.addma.2024.104498
</details>-->

<h2 id="MLDnP_Publications"> Key Publications </h2>
<!-- COPY ALL PUBLICATIONS IN EACH PROJ HERE (SORTED BY LATEST-TO-OLDEST) -->
Peng B, Panesar A. <i> Multi-layer thermal history prediction framework for Directed Energy Deposition based on Extended physics-informed neural networks (XPINN) </i> Additive Manufacturing. (2025)  https://doi.org/10.1016/j.addma.2025.104953

Yu X, Peng B, Panesar A. <i> Smooth 3D transition cell generation based on latent space arithmetic </i> Additive Manufacturing. (2025) https://doi.org/10.1016/j.addma.2025.104714

Peng B, Panesar A. <i> Multi-scan thermal simulation using physics-informed neural network </i> Additive Manufacturing. (2024) https://doi.org/10.1016/j.addma.2024.104498

Wang J, Panesar A, <i> Machine learning based lattice generation method derived from topology optimisation </i> Additive Manufacturing. (2022) https://doi.org/10.1016/j.addma.2022.103238

<!-- Peng B, Panesar A. <i> Multi-layer Thermal Simulation of Directed Energy Deposition using Physics Informed Neural Networks </i> Real-World Applications of AI and ML in Digital Engineering Seminar [Internet]. (2025) https://www.nafems.org/downloads/dropbox/nologin/aiuk25/panesar_ext_abs.pdf

Peng B, Panesar A. <i> Predicting temperature field for mental additive manufacturing using PINN </i> International Solid Freeform Fabrication Symposium. (2023) -->



<style>
  summary {
    background-color: grey;
    color: white;
    padding: 2px 5px 2px 1px;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
    display: inline-block;
    text-decoration: none;
    list-style: none;
    position: relative;
    padding-left: 25px; /* space for arrow */
  }

  summary::before {
    content: "▶";
    position: absolute;
    left: 8px;
    transition: transform 0.2s ease;
  }

  details[open] summary::before {
    transform: rotate(90deg); /* arrow points down */
  }
</style>
