---
title: "Group contribution and machine learning approaches to predict Abraham solute parameters, solvation free energy, and solvation enthalpy"
collection: publications
permalink: /publication/2022-01-19-group-contribution-and-machine-learning-approaches
excerpt: 'We present a group contribution method (SoluteGC) and a machine learning model (SoluteML) to predict the Abraham solute parameters, as well as a machine learning model (DirectML) to predict solvation free energy and enthalpy at 298 K. Extensive data sets containing 8366 solute parameters, 20,253 solvation free energies, and 6322 solvation enthalpies are compiled in this work to train the models. Data sets and tools to make solvation predictions are made open-access.<br/><img src="/images/abraham_ml_solv.png" width="500" height="300">'
date: 2022-01-19
venue: 'Journal of Chemical Information and Modeling'
paperurl: 'https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01103'
citation: 'Chung, Yunsie; Vermeire, Florence H; Wu, Haoyang; Walker, Pierre J; Abraham, Michael H; Green, William H. (2022). &quot;Group contribution and machine learning approaches to predict Abraham solute parameters, solvation free energy, and solvation enthalpy.&quot; <i>Journal of Chemical Information and Modeling</i>. 62(3). 433-446.'
---
Abstract

We present a group contribution method (SoluteGC) and a machine learning model (SoluteML) to predict the Abraham solute parameters, as well as a machine learning model (DirectML) to predict solvation free energy and enthalpy at 298 K. The proposed group contribution method uses atom-centered functional groups with corrections for ring and polycyclic strain while the machine learning models adopt a directed message passing neural network. The solute parameters predicted from SoluteGC and SoluteML are used to calculate solvation energy and enthalpy via linear free energy relationships. Extensive data sets containing 8366 solute parameters, 20,253 solvation free energies, and 6322 solvation enthalpies are compiled in this work to train the models. The three models are each evaluated on the same test sets using both random and substructure-based solute splits for solvation energy and enthalpy predictions. The results show that the DirectML model is superior to the SoluteML and SoluteGC models for both predictions and can provide accuracy comparable to that of advanced quantum chemistry methods. Yet, even though the DirectML model performs better in general, all three models are useful for various purposes. Uncertain predicted values can be identified by comparing the three models, and when the 3 models are combined together, they can provide even more accurate predictions than any one of them individually. Finally, we present our compiled solute parameter, solvation energy, and solvation enthalpy databases (SoluteDB, dGsolvDBx, dHsolvDB) and provide public access to our final prediction models through a simple web-based tool, software packages, and source code.

![](/images/abraham_ml_solv.png)

[Download paper here](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01103)

[Download the dataset for free](https://zenodo.org/record/5792296)

[Have a molecule and want to estimate its solvation energy? Try here.](https://rmg.mit.edu/database/solvation/search/)
