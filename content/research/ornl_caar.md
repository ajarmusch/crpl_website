+++
title = "ORNL CAAR"
date = "2020-05-26T11:04:20+02:00"
tags = [
    "current",
]
+++

### ORNL CAAR: Preparing PIConGPU, a plasma physics application for exascale systems - Frontier at ORNL

**PI** 

Sunita Chandrasekaran  

**UDEL PhD Student** 

Matt Leinhauser  

**Project Funded by**

CASUS – Center for Advanced Systems Understanding, Helmholtz-Zentrum Dresden-Rossendorf e.V. (HZDR)
Untermarkt 20, D-02826 Görlitz, Germany

**Project Duration** 

09/30/2019 - 09/30/2021

**Oak Ridge National Lab**   

CAAR Liaison: Dr. David Rodgers (Former CAAR Liaison: Ronnie Chatterjee)

Visualization Team: Dr. Benjamin Hernandez, Dr. Feiyi Wang, Dr. Arjun Shankar

**Helmholtz Zentrum Dresden Rossendorf (HZDR)/Center for Advanced System Understanding (CASUS), Germany**

Dr. Michael Bussmann, Dr. Alexander Debus, Dr. Guido Juckeland, Mr. Rene Widera, Dr. Sergei Bastrakov, Dr. Thomas Kluge, Dr. Klaus Steiniger, Dr. Jeff Kelling, Dr. Richard Pausch, Mr. Marco Garten, Mr. Felix Meyer, Mr. Matthias Werner.

**Georgia Institute of Technology**  

Dr. Jeff Young 

**Lawrence Berkeley National Lab**

Dr. Axel Huebl

**LogMeIn** 

Mr. Benjamin Worpitz

**Project Summary**  

This is a prestigious software project, called Center for Accelerated Application Readiness (CAAR), awarded by ORNL in September 2019. Only 8 CAAR teams have been selected by ORNL across the United States to work on software stacks for one of the upcoming Exascale systems, Frontier to be housed at ORNL by 2021 timeframe.

The CAAR project uses a Particle In Cell GPU (PIConGPU), an extremely scalable, heterogeneous, fully relativis- tic C++ code. PIConGPU is available as open-source project on GitHub, for plasma and laser-plasma physics used to develop advanced particle accelerators for radiation therapy of cancer, high energy physics and photon science. The code is suitable for production-quality runs on state-of-the-art supercomputers driven by manycore accelerators as well as traditional architectures with a single, maintainable code base.

With Frontier, we believe the complex plasma dynamics that govern the final particle beam properties can now be studied at an unprecedented temporal and spatial resolution. This will provide accelerator development with the high quality data needed to advance plasma accelerators towards application.

PIConGPU uses the ALPAKA software stack to target almost all many-core compute platforms currently on the market using a single source, redundant parallel hierarchy approach and the openPMD ecosystem for high performant I/O. Alpaka offers a template-based unified C++14 programming model for multicore and manycore architectures, namely CPUs (Intel, AMD, ARM, POWER) and GPUs (Nvidia, AMD) by leveraging the APIs OpenMP, TBB, Fibers, CUDA as well as an initial version of HIP.

The challenges in this project include creating a working and a stable OpenMP 4.5/5.x and an OpenACC backend for Alpaka in order to target Frontier that will comprise of AMD CPUs and GPUs. PIConGPU will be one of the 8 CAAR codes (amidst other ECP codes) that will will have early access to Frontier in order to study the software and hardware limitations before Frontier is made available for other real-world applications.


**Papers:**

* Kelling, J., Bastrakov, S., Debus, A., Kluge, T., Leinhauser, M., Pausch, R., Steiniger, K., Stephan, J., Widera, R., Young, J., Bussman, M., Chandrasekaran, S., & Juckeland, G. (2021). Challenges Porting a C++ Template-Metaprogramming Abstraction Layer to Directive-based Offloading. arXiv preprint arXiv:2110.08650.

* Leinhauser, M., Widera, R., Bastrakov, S., Debus, A., Bussmann, M., & Chandrasekaran, S. (2021). Metrics and Design of an Instruction Roofline Model for AMD GPUs. arXiv preprint arXiv:2110.08221.

**Talks:**

* Matthew Leinhauser, Designing an Instruction Roofline Model for AMD GPUs, Center for Accelerated Systems Understanding (CASUS), Görlitz, Germany, July 2021 (Virtual)

* Running PIConGPU on Summit. CAAR: Preparing PIConGPU for Frontier at ORNL, 4th OpenPOWER Academic and Research Workshop, Denver, USA,  Nov 2019

**Technical Reports**

* Leinhauser, M., Bastrakov, S., Widera, R., Debus, A., Bussmann, M., Juckeland, G., Arghya Chatterjee, & Chandrasekaran, S. (2020). CAAR for Frontier -An ORNL Project Jan 2020 TECHNICAL REPORT Analysis of PIConGPU’s Three Most Intensive Kernels from NVProf on Summit. University of Delaware. https://doi.org/10.13140/RG.2.2.30951.80802

* Leinhauser, M., Young, J., Bastrakov, S., Widera, R., Debus, A., Bussmann, M., Juckeland, G., Arghya Chatterjee, & Chandrasekaran, S. (2020). CAAR for Frontier -An ORNL Project Analysis of PIConGPU’s Three Most Intensive Kernels from NSight Systems and NSight Compute on Summit. Unpublished. https://doi.org/10.13140/RG.2.2.28095.33448

* Leinhauser, Matthew, Young, Jeffrey, Bastrakov, Sergei, Widera, Rene, Chatterjee, Ronnie, & Chandrasekaran, Sunita. _Performance Analysis of PIConGPU: Particle-in-Cell on GPUs using NVIDIA’s NSight Systems and NSight Compute_. United States. [Link to PDF on OSTI](https://info.ornl.gov/sites/publications/Files/Pub148652.pdf)


