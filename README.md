# Machine-Learning-for-Ensemble-Modelling-in-Systems-Biology
Deep Mixture Density Networks for the prediction of enzyme kinetic parameter distributions to be used in Ensemble Modelling in Systems Biology

This project explores the prediction of enzyme kinetic parameter distributions to be used in Ensemble Modelling in Systems Biology. Systems Biology is the computational analysis and modelling of complex biological reactions. Systems Biology uses a system of differential equations to model the behaviour of biological systems. These differential equations need precise kinetic parameters, that are experimentally obtained and often sparsely available. Ensemble modelling in systems biology aims to solve this by sampling from a distribution of possible parameter values and using a number of models and aggregating the results. The aim of this project is to use machine learning and an enzyme database to provide accurate prior distributions to be used for ensemble modelling. This project is implemented using a dataset obtained through querying the BRENDA database. The main focus of the project is on the Mixture Density Network, that is a neural network that produces a Gaussian Mixture Model as its output. The Mixture Density Model produced is able to model a unique prior distribution for every input to the system.
