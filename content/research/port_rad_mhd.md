+++
title = "Porting Radiative MHD Models to GPUs"
date = "2020-05-26T11:04:20+02:00"
tags = [
    "current",
]
image = "/img/research/NCAR.png"
+++

### Porting the MPS/University of Chicago Radiative MHD Models to GPUs Using OpenACC

**PI:** Sunita Chandrasekaran  
**Student:** Eric Wright  
**Collaborators:** NCAR, USA: Rich Loft, Shiquan Su, Cena Miller, Supreeth Suresh, Matthias Rempel  
Max Planck Institute of Solar Society, Germany: Damien Przybylski

**Funding Agency:** National Center for Atmospheric Research (NCAR)/UCAR

**Duration:** 06/01/2018 – 09/30/2020

**Project Summary:**  
The MURaM (Max Planck University of Chicago Radiative MHD) code is the primary solar model used in HAO for simulations of the upper convection zone, photosphere (visible surface of the sun) and corona. Originally based on a magnetohydrodynamics (MHD) module from the University of Chicago, MURaM is jointly developed and used by HAO, the Max Planck Institute for Solar System Research (MPS) and the Lockheed Martin Solar and Astrophysics Laboratory (LMSAL).

MURaM simulations contribute substantially to our understanding of solar phenomena ranging from the origins of quiet sun magnetism, the structure and evolution of sunspots and active regions, to solar flares and the initiation of coronal mass ejections. MURaM also plays a key role in interpreting high resolution solar observations. With the construction of the Daniel K. Inouye Solar Telescope (DKIST), an NSF investment http://dkist.nso.edu) exceeding $300 million, resolution of ground based observational solar physics is poised to take an order of magnitude leap forward.

MURaM’s standard configuration (MURaM-std) is the focus of the project. It is written in the C programming language, demonstrates a 2D wavefront pattern and has approximately 10,000 source lines of code. The project’s overarching goal is to create clear, efficient, and maintainable MURaM modeling software capable of being run on both traditional multi-core Central Processing Units (CPUs) and Graphics Processing Units (GPUs). To that end, we have been creating an OpenACC code base of MURaM that can run both on CPUs and GPUs without any changes to the code base. The ability to abstract computations and data movement is opening up to better scientific capabilities and we are able to quickly adapt algorithmic changes as we speak.

**Talks:**

* Porting MURaM (Max Planck University of Chicago Radiative MHD) to GPUs Using OpenACC, GPU Technology Conference (GTC), Invited speaker, CA, USA, March 2019

* Accelerating MURaM on GPUs using OpenACC, NCAR, September 2019

* Applying directives to port MURaM code to heterogeneous systems, ASTRONUM, Paris, France, July, 2019
