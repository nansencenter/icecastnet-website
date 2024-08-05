---
layout: minimal
title: Super-resolution of sea ice thickness using diffusion models
subtitle: Julien Brajard, Anton Korosov, Richard Davy, Fabio Mangini, Adrien Perrin, Yiguo Wang
---

This work presents a simulator of high-resolution sea ice thickness in the Arctic based on diffusion models, which is a type of artificial intelligence (AI) generative model. 
Diffusion models have already shown impressive skill in generating realistic high-resolution images (e.g., DALL-E, Midjourney, Stable Diffusion).

Current satellite-based observations or climate model simulations of sea ice thickness provide valuable data but are limited by their coarse spatial resolution. 
High-resolution information is crucial for useful predictions and understanding small-scale features such as leads and thin ice, 
which significantly impact seasonal forecasting and heat flux calculations.

To increase the resolution of sea ice thickness products, we propose the following. 
First, a physically-based sea ice model, neXtSIM, is employed to generate a synthetic but realistic high-resolution sea ice thickness dataset. 
This synthetic dataset is filtered to mimic the resolution of present satellite products or climate model outputs. 
An AI-based diffusion model is then trained to enhance the low-resolution SIT data. 

By comparing the field produced by the simulator and high-resolution test images we will demonstrate that the simulator is able to produce 
accurate and realistic high-resolution sea ice thickness fields. Accuracy is demonstrated by assessing the error of the reconstruction, 
while realism is assessed by visual inspection and by computing the power density spectra. 
For both criteria, accuracy, and realism, our simulator outperforms a linear interpolation of the low-resolution field, which is used as a baseline. 
We will also demonstrate the impact of the new high-resolution sea ice thickness product on climate simulation and prediction.
