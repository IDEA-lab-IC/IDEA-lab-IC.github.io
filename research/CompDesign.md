<h1> Computational Design </h1>
<div style="text-align: justify"> 
Our current researches in the area of optimisation and adoption of machine learning in DfAM mainly focus on the generation of function-graded materials (FGM) and MDO as well as the generation of support-free, topologically optimised structures with machine learning.
</div>




<h2> Machine Learning Aided Design </h2>
<h3> Machine learning based lattice generation method derived from topology optimisation </h3>
<div style="text-align:center">
<img src="/../_media/research/2023_08_Amber_inversedesign.gif" style="width:100%">
</div>

We propose a novel lattice generation method that designs graded lattice structures with the assistance of Machine Learning (ML). 
A Neural Network (NN)-based inverse lattice generator is trained to output lattice unit cells from the input of target mechanical properties.
The proposed method utilises information from fast low-resolution Topology Optimisation (TO) design to inform the trained inverse generator and map lattice cells.
The outcomes clearly show that the newly-proposed method can generate lattice designs closely approaching the behavior of high-resolution TO designs, and within a significantly shorter time frame. Additionally, the lattice structures designed using our new method exhibit superior performance when compared to density-based lattice mapping.

<b> Relevant Publication(s): </b>

J. Plocher, A. Panesar, <i> Effect of density and unit cell size grading on the stiffness and energy absorption of short fibre-reinforced functionally graded lattice structures</i>, Additive Manufacturing Journal, Volume 33, (2020), 101171. https://doi.org/10.1016/j.addma.2020.101171

<hr>

<h3> Support-free, topologically optimised 3D structure generation with Machine Learning</h3>
<div style="text-align:center">
<img src="/../_media/research/supportFree.gif" style="width:100%">
</div>
<div style="text-align: justify"> 
This research answers the question of 'How can we generate topologically optimised structures that are support-free efficiently'. 

Many additive manufacturing processes require support structures for features with overhang angles beyond certain limits. Topologically optimised parts usually involve such features. However, the excess use of support implies increased amount of waste and the more uncertainties for successful prints, especially with delicate features which are prominent after topology optimisation. Hence, it is natural to incorporate the overhang angle constraints in the topology optimisation. The current state-of-the-art _AMfilter_ is a successful attempt but is computationally prohibiting to generate parts of practical sizes.

Hence, we propose the use of a Generative Adversarial Network (GANs) to replace the need for the many iterations and therefore reduce the computing time significantly. More specifically, the GANs model that we adopted is a conditional, deeply convoluting GANs. It takes in the strain field of the part after the first "topology optimisation + AM filter" iteration as the input and generate the topologically optimised and support-free structure within seconds. Our train models works with both 2D and 3D structures.
</div>

<b> Relevant Publication(s): </b>

B. Peng, A. Panesar, <i> Application of Machine Learning in Rapid Generation of Support-free, Topologically-optimised Structures</i>, AIAA SCITECH 2023 Forum, 2023, https://doi.org/10.2514/6.2023-0950


<h2> Topology Optimisation for Multi-physics Problems </h2>

<h3> Discovery of next-generation battery electrodes using topology optimization </h3>
<div style="text-align:center">
<img src="/../_media/research/2023_08_CK_battery.gif" style="width:100%">
</div>

<div style="text-align: justify"> 
Efficient storage and deployment of renewable energy sources such as solar and wind energy are critical processes towards meeting the world’s CO2 reduction targets amidst rising energy demand. Energy demand is expected to rise by 25% by the year 2030 and Insertion-electrode batteries such as sodium-ion (Na-ion) and Lithium-ion (Li-ion) batteries represent notable advancements in the design of energy storage systems that can meet rising demands. Today, strategies for enhancing battery performance – capacity, rate capability, cycle efficiency and cycle life – constitute vibrant fields of inquiry. For example, the performance of a typical Li-ion battery is limited by its ion and electron transport mechanism due to the tortuous ion pathways in its electrode. There also exists a limitation on the batteries cycle life due to mechanical effects causing damage to its electrode. One way to improve the batteries performance is to control its electrode nanoarchitecture to mitigate inefficient ion transport and electrode damage. However, the conflicting requirements for generating efficient electrode morphology for optimal performance and lifetime presents a non-trivial multidisciplinary design engineering problem spanning electrochemistry, solid mechanics, material science and mathematical optimization. 

This collaborative work leverages expertise across the departments of aeronautics, materials, chemical and chemistry at Imperial College London to derive strategies for the optimal design of battery electrodes. Preliminary research suggests that electrode nanoarchitecture is critical to improving battery performance. By numerically modelling the underlying battery transport mechanisms, we derive a robust mathematical optimisation formulation that guides the search for optimal battery electrode designs. Our work seeks to present a gradient-driven approach to derive optimal electrode architecture, constrained only by the underlying multiphysics system defining transport mechanisms across solid and liquid phases. The derived framework will challenge the traditional manufacturing techniques for electrodes, and will inspire novel strategies for deriving new high-performance electrodes such as proffered by additive manufacturing. 

<b> Key collaborators </b>: 

Members from Imeprial: <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.p.ryan" target = "_blank">Mary Ryan</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.shaffer" target = "_blank">Milo Shaffer</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/m.titirici" target = "_blank">Magda Titirici</a>, <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/i.stephens" target = "_blank">Ifan Stephens</a>;

Industry sponsor: <a style = " white-space:nowrap; " href="https://www.linkedin.com/in/peterklusener/" target = "_blank">Peter Klusener</a> (Shell). 

<b> Relevant Publication(s): </b>

C. Imediegwu, M. Shaffer, M. Ryan, A. Panesar, <i> Discovery of next-generation battery electrodes using topology optimization</i>, Solid Freeform Fabrication Symposium – An Additive Manufacturing Conference, USA, 14-16 Aug, 2023.

</div>


<h3> Structural Power Composites </h3>
<div style="text-align:center">
<img src="/../_media/research/strucComp.gif" style="width:100%">
</div>

<!-- Our current research in MFMM attempts to answer the questions on what MFMM looks like for structural batteries and the development of high-energy-absorbing meta-materials. It is part of the group effort of Imperial College London's <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/structural-power-composites/team/" target = "_blank">Structural Power Composites team</a> in the Department of Aeronautics. It is also co-supervised by <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/e.greenhalgh" target = "_blank">Professor Emile S Greenhalgh</a> from the Department of Aeronautics at Imperial College London. -->

We have been collaborating with <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/people/e.greenhalgh" target = "_blank">Prof. Emile S Greenhalgh</a> on progressing <a style = " white-space:nowrap; " href="https://www.imperial.ac.uk/structural-power-composites/team/" target = "_blank">structural power composites</a>, particulalrly on the modelling and optimisation front. Our work has unravelled novel topologies for structual electrolyte materials which are considered pivotal for the development of structual batteries/supercapacitors. 


<b> Relevant Publication(s): </b>

C. Lee, E. S. Greenhalgh, M. S. P. Shaffer, A. Panesar, <i> Optimized microstructures for multifunctional structural electrolytes</i>, Multifunct. Mater., Volume 2, (2019), 045001, https://dx.doi.org/10.1088/2399-7532/ab47ed

<h2> Numerical Computational Design </h2>

<h3> Review on Design and Structural Optimisation </h3>
<img src="/../_media/optiReview.jpg" style="width:100%">
<div style="text-align: justify"> 
As the application of additive manufacturing (AM) reaches an unprecedented scale in both academia and industry, a reflection upon the state-of-the-art developments in the design for additive manufacturing (DfAM) and structural optimisation, becomes vital for successfully shaping the future AM-landscape. A framework, highlighting both the interdependencies between these two central aspects in AM and the necessity for a holistic approach to structural optimization, using lightweight strategies such as topology optimization and/or latticing, was established to summarize the reviewed content. Primarily focusing on isotropic material considerations and basic stiffness-optimal problems, these concepts have already found wide application, bridging the gaps between design and manufacturing as well as academia and industry. In pursuit of streamlining the AM-workflow towards digitally print-ready designs, studies are increasingly investigating mathematically-based structural optimization approaches in conjunction with DfAM-specific constraints, providing a portfolio of solutions like generative design, which is gaining traction in industry. Besides an overview on economically-driven to performance-driven design optimizations, insight into commercial AM-specific software is provided, elucidating potentials and challenges for the community. Despite the abundance of AM design methods to-date, computationally inexpensive solutions for common engineering problems are still scarce, which is constituting one of many key challenges for the future.
</div>

<b> Relevant Publication(s): </b>

J. Plocher, A. Panesar, <i> Review on design and structural optimisation in additive manufacturing: Towards next-generation lightweight structures</i>, Mater. Des. 183 (2019), 108164. https://doi.org/10.1016/j.matdes.2019.108164