---
#categories: ["Documentation"]
#tags: ["contribute"] 
title: "Overview"
linkTitle: "Overview"
weight: 1
description: >
---

{{% pageinfo %}}
AMR-H is under a rapid development. The detailed documentation will be released soon.
{{% /pageinfo %}}


## What is it?
AMR-H is a high performance computational infrastructure for simulations of compressible turbulent flows with adaptive mesh refinement (AMR) based on finite difference discretization.
It is designed as a computational fluid dynamics (CFD) tookit to address the needs of high performance solvers in scientific research in academia and industry.
AMR-H project is supported by the U.S. National Science Foundation.
The software is open source relased under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0) and completely free for all users. 



## Why do I want it?
AMR-H provides a compressible Navier-Stokes (or Euler) solver with flexibility in the choice of numerical schemes and closure models.
It supports both CPU-only and GPU-accelerated computations.
It automatically configures the compile-time and runtime parallelism for large scale simulations, and guarantees a portable performance on different types of high performance computing platforms.

Additionally, AMR-H provides many state-of-the-art high-order numerical schemes, computational algorithms, and physical models.
AMR-H has flexible extensibility.
The user can add or change the existing models, modify the built-in governing equations, or even configure a new solver using the built-in numerical schemes.
The numerical schemes provided in AMR-H can be also used in data processing.
As the result, user can better focus on the investigation of the physical or engineering problem of interest.



## Basic structure and available modules
<img class="img-fluid" src="img_software_stack.png" width="600">
<br>
<br>
The first release will focus on the modules in solid boxes. Collaborations are desired for development of the modules in dotted boxes.
