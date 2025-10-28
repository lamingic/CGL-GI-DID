# CGL-GI-DID
This repository is the official implementation of the paper "Generative Method for Solving Interactive Dynamic Influence Diagram".

This repository is the official implementation of the paper **"Generative Method for Solving Interactive Dynamic Influence Diagram"**.

We introduce the **GI-DID (Generative Interactive Dynamic Influence Diagram)** framework, an innovative extension of the [Ev-IDID](https://github.com/lamingic/Ev-IDID) toolkit. GI-DID addresses the core challenge of modeling other agents' unpredictable behaviors in multi-agent systems by integrating generative AI.

## Core Methodology

Our main contribution is the **CGL(WGAN-div)** method, which:
*   Leverages generative models (specifically WGAN-div) to synthesize a diverse and representative set of potential agent behaviors.
*   Employs a constrained generative learning process to select high-quality behavioral models.
*   Enhances the subject agent's decision-making quality in complex interactions.

## Repository Contents

This repository provides:
*   A complete implementation of the **GI-DID framework**.
*   Source code for **CGL(WGAN-div)** and other baseline algorithms (GAN, VAE, AAE, etc.).
*   Scripts and resources to run experiments in two classic domains: **Multiagent Tiger** and **UAV**.
*   Guidelines for reproducing the experimental results.

Empirical results demonstrate that our CGL(WGAN-div) method outperforms other baselines in generating diverse and representative behaviors, leading to a higher average reward for the subject agent.
