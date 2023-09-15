---
title: "Predicting Critical Properties and Acentric Factors of Fluids Using Multitask Machine Learning"
collection: publications
permalink: /publication/2023-07-24-predicting-critical-properties-and-acentric-factors
excerpt: 'Understanding critical properties like temperature, pressure, density, and acentric factors is crucial for evaluating the thermo-physical properties of chemical compounds. Given the high costs and time involved in experiments, we developed a machine learning model to predict these properties using the SMILES representation of chemicals. We examined directed message passing neural network (D-MPNN) and graph attention network for model architecture and improved performance using added features, multitask training, and pretraining. Our optimized D-MPNN model, enriched by Abraham parameters, predicts multiple properties, showcasing top-tier accuracies in various evaluations. We have made the dataset, containing details for 1144 compounds, publicly available along with the source code for further research.<br/><img src="/images/critical.png" width="550" height="350">'
date: 2023-07-24
venue: 'Journal of Chemical Information and Modeling'
paperurl: 'https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00546'
citation: 'Biswas, Sayandeep; Chung, Yunsie; Ramirez, Josephine; Wu, Haoyang; Green, William H. (2023). &quot;Predicting Critical Properties and Acentric Factors of Fluids Using Multitask Machine Learning.&quot; <i>Journal of Chemical Information and Modeling</i>, 63(15), 4574-4588.'
---
Abstract

Deep learning has become a powerful and frequently employed tool for the prediction of molecular properties, thus creating a need for open-source and versatile software solutions that can be operated by non-experts. Among current approaches, directed message-passing neural networks (D-MPNNs) have proven to perform well on a variety of property prediction tasks. The software package Chemprop implements the D-MPNN architecture, and offers simple, easy, and fast access to machine-learned molecular properties. Compared to its initial version, we present a multitude of new Chemprop functionalities such as the support of multi-molecule properties, reactions, atom/bond-level properties, and spectra. Further, we incorporate various uncertainty quantification and calibration methods along with related metrics, as well as pretraining and transfer learning workflows, improved hyperparameter optimization, and other customization options concerning loss functions or atom/bond features. We benchmark D-MPNN models trained using Chemprop with the new reaction, atom-level and spectra functionality on a variety of property prediction datasets, including MoleculeNet and SAMPL, and observe state-of-the-art performance on the prediction of water-octanol partition coefficients, reaction barrier heights, atomic partial charges, and absorption spectra. Chemprop enables out-of-the-box training of D-MPNN models for a variety of problem settings in a fast, user-friendly, and open-source software.

![](/images/critical.png) -->

[Download paper here](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00546) 

[Download the dataset for free](https://zenodo.org/record/8072892)
