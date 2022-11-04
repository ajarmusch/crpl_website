+++
title = "Acceleration of Next Generation Sequence (NGS) Alignment"
date = "2020-05-26T11:04:20+02:00"
stage = "current"
image = "/img/partners/AiDupont.png"
text = "Building a portable and fast DNA sequence alignment tool"
+++

### Acceleration of Next Generation Sequence (NGS) Alignment

**PI:** Sunita Chandrasekaran  
**Students:** Sanhu Li  
**Collaborators:** Nemours/Alfred I. duPont Hospital for Children: Erin Crowgey, Karl Franke

**Duration:** 06/30/2016 - work in progress

**Project Summary:**  
The goal of this project is to design a scalable and portable sequence alignment tool that is both performance and memory efficient while not compromising on the accuracy, specificity or the sensitivity of the alignment. Such a tool is direly needed as it is evident from the COVID19 pandemic, that we are not ready to tackle the breakout of a novel virus. It has been 7 months since the breakout (at the time of writing this research statement, May 2020) and yet there is no vaccination. The purpose of this tool is to create a faster alignment tool than the current state-of-the-art gold-standard BWA-MEM that takes about 72 hours to finish a Whole Genome Sequence (WGS) alignment. My project has been scanning through several past and near-past literature to understand the complexities of creating a fast alignment tool. To that end for our tool, we have developed 3 novel algorithms: seeding, back-tracking and aligning. We are currently in the phase of integrating all steps and running several tests for accuracy, specificity and sensitivity. For benchmarking purposes, we use the NA12878 50X WGS sample from Illumina’s Genome in a Bottle along with the HG38 reference genomes.

The impact are several folds. (1) Our proposed accelerated techniques could be applied to aggressive tumors such as Glioblastoma where the cells mutate at such a fast pace that by the time the patient is being treated for a particular mutation, the cells have already mutated again very rapidly thus rending anti-cancer therapies ineffective and causing earlier deaths. (2) Understand the evolution of novel viruses and their mutations faster to help with quicker vaccinations. (3) Also applicable to genomes other than human, such as plant genome as our technique aims to handle both short and long read; the latter more common in plant genome. In summary, this project has the potential to propel the area of biology in different ways. This work is of interest to Nemours in Delaware and St. Jude’s Children’s Hospital in Tennessee.

**GitHub:** The software is open source and available on GitHub: <a href="https://github.com/lisanhu/AccSeqV9/tree/0.9.2">https://github.com/lisanhu/AccSeqV9/tree/0.9.2</a>.  
