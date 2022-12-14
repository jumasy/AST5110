# Home

This course covers essential numerical methods on PDEs through a set of exercises using **Python.** The exercises guide the students through developing their numerical code. In this wiki, we cover some of the theories behind these exercises. For this course, we collected information from the following:

* F. Moreno-Insertis (2018).<br>
Course on numerical simulation techniques for fluid dynamics.
<br>Universidad de La Laguna (Tenerife, Spain).
* V. H. Hansteen (2018).<br>
AST 5110 Numerical modeling.<br>
University of Oslo (Oslo, Norway).
* Å. Nordlund & K. Galsgaard (1995).<br>
A 3D MHD code for Parallel Computers.
* B. Gudiksen et al. (2011).<br>
The stellar atmosphere simulation code Bifrost: <br>
Code description and validation.<br>
[A&A 531, A154](https://www.aanda.org/articles/aa/pdf/2011/07/aa16520-11.pdf)
* W. H. Press et al..<br>
Numerical recipes.<br>
Cambridge University Press.<br>
[http://numerical.recipes](http://numerical.recipes)
* Culbert B. Laney <br>
Computational Gasdynamics<br>
Cambridge University Press.<br>
* K. W. Morton and D.F. Mayers <br>
Numerical Solution of Partial Differential Equations: An introduction<br>
Cambridge University Press.<br>

During this course, first, we describe how a function can be discretized and understand its convergence. Then, in the following, using Burger's equation, we will investigate the stability using 1st order upwind, downwind, and cell-center derivatives, as well as higher-order derivatives. During these steps, we will introduce how to advance in time, the problem of the boundaries, as well as perform the first validation tests. These tests will allow us to add the CI pipeline, which will check that at least this test works for each new commit of your _nm\_lib_ repository.

To move on, we will introduce the CFL condition and its constraints for different PDE equations on the time derivative. Diffusive terms may require implicit methods or different techniques. We will cover a few implicit methods and other numerical, analytical techniques to tackle the CFL constraints. The students will have the opportunity to implement one of them in their code.

We will continue to expand the terms/variables and equations to solve the hydrodynamic equations. Students will implement operator splitting during this process and understand when this can or cannot be applied.

Students will have the opportunity (optional) to expand their code (2D/3D) or adding new physics, run and analyze different numerical experiments of interest.
