---
title: "An Optimal Control View of Flow-based Models: Shortcut Diffusion Training With Cumulative Consistency Loss"
excerpt: "Formulating few-step generation as a controlled base generative proceses shows that self-consistency loss can be understood through the lens of optimal control. This perspective motivates its generalization to the proposed cumulative self-consistency loss that cumulatively penalizes misalignment along the entire trajectory (ICLR2026) <br/><img align='center' width='800' src='/images/CSL_flow.png'>"
collection: portfolio
---

We formulate few-step generation as a controlled base generative process, and show that self-consistency loss can be 
understood through the lens of optimal control. This perspective naturally motivates its generalization to the proposed 
cumulative self-consistency loss that cumulatively penalizes misalignment along the entire trajectory. This encourages 
larger step-sizes that not only align with the base model at the current time step but also support alignment in the 
subsequent steps, facilitating high-quality generation. Furthermore, we draw a connection between our approach and 
reinforcement learning, potentially opening the door to a new set of approaches for few-step generation. 
