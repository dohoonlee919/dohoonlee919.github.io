---
title: "Solving Blind Non-linear Forward and Inverse Problem for Audio Applications"
collection: papers
permalink: /papers/2024-09-26-paper-title-number-3
excerpt: 'The framework addresses blind forward and inverse problems by using a reference encoder to approximate the nonlinear forward operator in a diffusion model, combined with twisted particle filtering for enhanced signal reconstruction.'
# date: 2024-9-26
# status: 'Under review for ICLR 2025'
# venue: 'Under review for ICLR 2025'
# paperurl: 'https://openreview.net/forum?id=mlPTNEIsgb'
---

Under review for ICLR 2025

https://openreview.net/forum?id=mlPTNEIsgb

We propose a novel framework to address the blind forward and inverse problems, where the goal is to infer either the function or the input signal solely from the output signal without access to the other. These problems are challenging due to the highly nonlinear and complex nature of the forward operator—the function mapping between the input and output signals. To tackle the blind forward problem, we introduce a reference encoder that analyzes the reference output (wet signal) to approximate an arbitrary forward operator. For the blind inverse problem, the approximated forward operator is leveraged to guide both the training and inference stages of a diffusion model, enabling a more accurate reconstruction of the input signal. Furthermore, we propose a twisted particle filtering method to enhance the model's performance in solving the inverse problem. Our framework significantly advances signal-processing tasks in complex, non-linear systems, with experimental results demonstrating its effectiveness in both audio effect modeling and speech enhancement applications. Codes are available at "https://github.com/BlindForwardInverse/BlindForwardInverseAnonymous"
