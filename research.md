---
layout: page
title: Research
permalink: /research/
---

### Optimal Transportation methods in nonlinear filtering:       {#FPF}

Complex (many-body) quantum system is an umbrella term for models of physical systems that comprise of a large number interacting smaller subsystems, each of which is described by a quantum theory. While the individual subsystems might be easy to analyze, their collective behavior is challenging to capture. My interest here lies in developing classical and quantum algorithms, with rigorous guarantees, for simulating dynamics and equilibrium properties of many-body quantum systems. In particular, I am interested in focussing on many-body open quantum systems, which remain unexplored compared to their closed counterparts. I am also interested in exploring algorithms for dynamics and equilibrium properties of disordered quantum systems (quantum spin-glasses).

- [Description and Complexity of non-Markovian open quantum dynamics.](https://arxiv.org/abs/2204.06936)     

- [Transitions in Computational Complexity of Continuous-Time Local Open Quantum Dynamics](https://arxiv.org/abs/2110.10638v2)
  
- [Convergence Guarantees for Discrete Mode Approximations to Non-Markovian Quantum Baths](https://arxiv.org/abs/2107.07196)    





----------
### Interplay between optimization and sampling:   {#SM}
<p align="center">
<img src="../images/sampling-optimization.png" width="350"/>
<img src="../files/mnist-traj.png" width="300"/>
</p>

Optimization and sampling algorithms share remarkable similarities in general, as highlighted by the similarity between stochastic gradient descent and Langevin sampling. In fact, sampling can be viewed as an optimization problem on the space of probability distributions. The goal of this research is to bridge the gap between optimization and sampling by employing optimization algorithms specifically for the purpose of sampling, using the Riemannian geometry, as provided by optimal mass transport. 

- [Variational Wasserstein gradient flow](https://arxiv.org/abs/2112.02424)  
    
- [Accelerated flow for probability distributions](http://proceedings.mlr.press/v97/taghvaei19a.html) ([arXiv](https://arxiv.org/abs/1901.03317))        



----------
### Computational methodology for optimal mass transportation:      {#OT}
<p align="center">
<img src="../images/OT-drawing.png" width="350"/>
</p>

There is a growing interest in application of the optimal transportation theory in machine learning and control related problems. The main reason is that the optimal transportation theory provides powerful and elegant geometrical tools to view and manipulate probability distributions. The objective of this  ressearch is to develop efficient data-driven computational algorithms that provide reliable approximations to these geometrical tools in high dimensions.


- [Scalable computations of Wasserstein barycenter via input convex neural networks](https://arxiv.org/abs/2007.04462)  


- [Optimal transport mapping via input-convex neural networks](http://proceedings.mlr.press/v119/makkuva20a.html) ([arXiv](https://arxiv.org/abs/1908.10962))              


----------
### Fundamental limitations in stochastic thermodynamics:  {#Thermo}
<p align="center">
<img src="../files/engine.jpg" width="400"/>
</p>

Classical thermodynamics is inherently static and can not capture non-equilibrium transitions and the power that can be extracted from an engine in finite time.
To this end, the framework of stochastic thermodynamics was developed in recent years to allow quantifying thermodynamic quantities in finite time transitions. The objective of this project is to study fundamental limits in dissipation and in power generation by thermodynamic processes. Remarkabley, these problems can be viewed as optimal control problems for probabibility distributions where optimal mass transport plays a central role.

- [Energy harvesting from anisotropic fluctuations](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.104.044101)([arXiv](https://arxiv.org/abs/2108.00334))        
   
- [On the relation between information and power in stochastic thermodynamic engines](https://ieeexplore.ieee.org/document/9426929)([arXiv](https://arxiv.org/abs/2103.03986)) 

- [Maximal power output of a stochastic thermodynamic engine](https://doi.org/10.1016/j.automatica.2020.109366) ([arXiv ](https://arxiv.org/abs/2001.00979))  

<!--

layout: page
title: Mentorship
permalink: /mentorship/

### Ph.D. students (current)

- Mohammad Al-Jarrah, University of Washington, Seattle
- Olga Movilla, University of California, Irvine
- Anqi Dong, University of California, Irvine

### Undergraduates (former)
- Ayano Hiraka, Kumar Gandhi, Peter Ivanov, Ulzee An, University of Illinois at Urbana-Champaign  

-->
