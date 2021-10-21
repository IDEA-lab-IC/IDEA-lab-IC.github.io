<h1> Optimisation & Machine Learning in Design for Additive Manufacturing</h1>
<div style="text-align: justify"> 
Our current researches in the area of optimisation and adoption of machine learning in DfAM mainly focus on the generation of function-graded materials (FGM) and MDO as well as the generation of support-free, topologically optimised structures with machine learning.
</div>

<hr>
<h3> Support-free, topologically optimised 3D structure generation with Machine Learning</h3>

<div style="text-align: justify"> 
This research answers the question of 'How can we generate topologically optimised structures that are support-free efficiently'. 

Many additive manufacturing processes require support structures for features with overhang angles beyond certain limits. Topologically optimised parts usually involve such features. However, the excess use of support implies increased amount of waste and the more uncertainties for successful prints, especially with delicate features which are prominent after topology optimisation. Hence, it is natural to incorporate the overhang angle constraints in the topology optimisation. The current state-of-the-art _AMfilter_ is a successful attempt but is computationally prohibiting to generate parts of practical sizes.

Hence, we propose the use of a Generative Adversarial Network (GANs) to replace the need for the many iterations and therefore reduce the computing time significantly. More specifically, the GANs model that we adopted is a conditional, deeply convoluting GANs. It takes in the strain field of the part after the first "topology optimisation + AM filter" iteration as the input and generate the topologically optimised and support-free structure within seconds. Our train models works with both 2D and 3D structures.
</div>

