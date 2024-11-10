---
title: "Personalized Preference Optimization for Text-to-Image Generation using Large Language Models"
collection: papers
permalink: /papers/2024-6-16-paper-title-number-4
excerpt: 'Developed a framework for optimizing personal preferences through in-context learning, utilizing the PIAA method, introducing multi-prompt optimization, integrating comprehensive feedback, and demonstrating training-free, real-world applications.'
# date: 2024-6-16
status: Arxiv
# venue: 'Under review'
paperurl: 'https://openreview.net/forum?id=4VzHv5s0Hp'
---

Preference optimization is a crucial aspect of generative models, ensuring that the generated content aligns with users' preferences. While previous research has focused on optimizing for average preferences, text-to-image tasks require a personalized approach due to the diversity of individual preferences. In this study, we propose a two-stage framework for personalized preference optimization in text-to-image generation. The first stage, personalized image aesthetic assessment (PIAA), learns user preferences from a small amount of user image rating data. The second stage, prompt optimization, optimizes the text-to-image model's prompt to generate images that receive high scores from the learned preference model. We employ Large Language Models (LLMs) for the prompt optimization process. Through extensive experimentation with various configurations in the PIAA and prompt optimization stages, we demonstrate that our approach can generate novel images that align with individual user preferences, even with limited user data. Our research lays the foundation for future work on personalized content generation.