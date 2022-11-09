+++
title = "NCI-DOE Drug response modeling"
date = "2020-05-26T11:04:20+02:00"
stage = "current"
image = "/img/partners/nih-logo.png"
text = "Improving ECP-CANDLE’s drug response prediction models: Bioinformatics and Machine Learning"
+++

### Capabilities implementation and testing on normal and tumor tissue cells

**PI:** Sunita Chandrasekaran  

**Students:** Vineeth Gutta & Alex You

**Collaborators:** National Cancer Institute at Frederick National Lab: Satish Ranganathan & Matthew Beyers

**Funding agent:** National Cancer Institute, National Institute of Health, Leidos

**Duration:** 11/21 - Present

**Project Summary:** ECP-CANDLE (Cancer Distributed Learning Environment) is a collection of models and libraries that include 3 Pilots where each tackles a separate problem. Pilot 1 focuses on the drug response problem, pilot 2 on RAS pathway problem, and pilot 3 on high level treatment strategy problem. This work only involved pilot 1. The fundamental challenge drug response modeling faces is the lack of data for drug response on patients because human trials given the number of possible drugs makes it impossible to test them all. Therefore drug response models are trained on cancer cell-lines (grown in the lab) and these models do not perform well on patient tissue data. Some example models include single drug response model and Combo model with the difference being the latter using a combination of drugs to predict growth of cancer cell line. Both use multilayer perceptron with convolution like layers for the model architecture. The current work focuses on modeling drug response for gene expression data from CCLE (Cancer cell line encyclopedia) and drug sensitivity data from GDSC (Genomics of drug sensitivity in cancer). Existing CNN models from Single drug response and Combo models performed worse on the CCLE/GDSC data compared to the original NCI60 datasets. So we needed to improve the model itself. The XGBoost model improved the performance for CCLE/GDSC data when evaluated using R squared error metric. For future work we are exploring the use of Autoencoders to encode features such as drug descriptors or gene expressions to improve the performance of CNN models.

**GitHub:** The software is open source and available on GitHub: <a href="https://github.com/ECP-CANDLE/Benchmarks">https://github.com/ECP-CANDLE/Benchmarks</a>.  