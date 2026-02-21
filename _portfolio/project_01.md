---
title: "Harnessing Heterogeneous Statistical Strength for Personalized Federated Learning (PFL) via Hierarchical Bayesian Inference"
excerpt: "a hierarchical Bayesian inference framework for PFL by deriving a personalized posterior distribution over the parameters of each client’s local model <br/><img align='center' width='800' src='/images/BayesPFL.png'>"
collection: portfolio
---

Personalized federated learning (PFL) based on Bayesian approach tackle the challenges from statistical heterogeneity 
of client data by computing a personalized posterior distribution over the parameters of each client’s local model and 
constructing a global distribution by aggregating the parameters of these personalized posteriors. However, the heuristic 
aggregation methods introduce strong biases and result in global models with poor generalization. 

The project propose a novel hierarchical Bayesian inference framework for PFL by specifying a conjugate hyper-prior over 
the parameters of the personalized posteriors to jointly compute a global posterior distribution for aggregation and the 
personalized ones at local level. This hierarchical Bayesian inference framework achieves elegant balance between local 
personalization and global model robustness. 
