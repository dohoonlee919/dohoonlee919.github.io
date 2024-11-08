---
title: "Multidimensional Trajectory Optimization for Flow and Diffusion"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-1
excerpt: 'We introduce Multidimensional Coefficient and Multidimensional Trajectory Optimization within the flow and diffusion framework, achieving state-of-the-art results in CIFAR-10 conditional generation.'
date: 2024-04-22
venue: 'Under review for ICLR 2025'
# paperurl: 'https://arxiv.org/pdf/2404.14161v2'
---

In flow and diffusion-based generative modeling, conventional methods rely on unidimensional coefficients for the trajectory of differential equations. In this work, we first introduce a multidimensional coefficient that generalizes the conventional unidimensional coefficient into multiple dimensions. We also propose a new problem called multidimensional trajectory optimization, which suggests a novel trajectory optimality determined by the final transportation quality rather than predefined properties like straightness. Our approach employs simulation dynamics and adversarial training to optimize these inference trajectories. To empirically validate our method, we conduct experiments on various generative models, including EDM and Stochastic Interpolant, across multiple datasets such as 2D synthetic datasets, CIFAR-10, FFHQ, and AFHQv2. Remarkably, inference using our optimized multidimensional trajectory achieves significant performance improvements with low NFE (e.g., 5), achieving state-of-the-art results in CIFAR-10 conditional generation. The introduction of multidimensional trajectory optimization enhances model efficiency and opens new avenues for exploration in flow and diffusion-based generative modeling.
