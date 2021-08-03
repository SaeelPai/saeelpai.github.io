---
permalink: /research/
layout: page
title: ""

---

## Current Work
I work on the thermal management of electronic devices. For my PhD, I am working on designing highly optimal cold plate geometries. Cold plates are single-phase liquid cooling solutions used in high heat flux applications such as in data centers, electric vehicles, radar systems, etc. Although cold plates can be used in various applications, I am more focussed on the design of optimal cold plates for data center applications. This work leverages machine-learning methods to supplant traditional intuition-based design methods that require manual searching through a complex design space (boundary conditions and available surface morphologies), thereby enabling more optimal cold plate performance.

Till now, I have 
- Compiled an extensive database of fully developed Nusselt number and friction factor values of different constant cross section flow geometries (~800 distinct geometries).
- Developed machine learning based surrogate correlation for predicting the fully developed Nusselt number and friction factor of different constant cross section flow geometries.
- Used the surrogate correlations to find novel cross sections with desired properties.

Currently I am generating training data for heat transfer and pressure drop characteristics of three dimensionally varying flow geometries using automated numerical simulations.

## Publications
- **S.S. Pai**, D. Visaria, J.A. Weibel, “A machine-learning-based surrogate model for internal flow Nusselt number and friction factor in various channel cross sections” The IEEE Intersociety Conference on Thermal and Thermomechanical Phenomena in Electronic Systems (ITherm), June 2021.
- S. Ozguc, **S.S. Pai**, J.A. Weibel, L. Pan, “Experimental Demonstration of an Additively Manufactured Vapor Chamber Heat Spreader”, The IEEE Intersociety Conference on Thermal
and Thermomechanical Phenomena in Electronic Systems (ITherm), Las Vegas, USA, May 2019

## Past Work
### Undergrad Thesis
- **Towards Efficient Computation of Rarefied Flows using Field Inversion and Machine Learning Techniques** [[pdf](/BTP_report.pdf){:target="_blank"}]
  Advisor: Prof. Balaji Srinivasan, Department of Mechanical Engineering, IIT Madras
  
  This work used machine learning methods to bypass the need for expensive high-fidelity computations which are needed for accurate flow description of rarefied flows.
  - Successfully implemented the technique of ‘Field Inversion and Machine Learning’ on different cases of heat transfer and used it to model the structure of an acoustic shock wave.
  - The Maximum Likelihood Estimation approach was used to develop an Artificial Neural Network model to predict the flow of rarefied gas around a spherical body.

