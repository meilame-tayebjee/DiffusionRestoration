# Diffusion & Restoration Repository Overview

This repository explores image restoration processes using Diffusion models, particularly focusing on solving noisy Linear Inverse problems that degrade image quality. At the heart of our work are the Denoising Diffusion Restoration Models (DDRM) and Diffusion Posterior Sampling (DPS).

## Repository Structure

- `ddrm/`: Contains the official implementation of DDRM, which is central to our experiments and theoretical analyses.
- `dps/`: Hosts the official implementation of DPS, another crucial component of our comparative studies.
- `notebooks/`: Features our homemade derived implementations of DDRM and DPS models, along with a series of experiments designed to evaluate their effectiveness in various restoration scenarios.

## Research Focus

Our research revolves around the utilization of Diffusion models to address and rectify degraded images caused by linear inverse problems. The main objectives and components of our work include:

1. **Theoretical Comparison**: We delve into a theoretical comparison between DDRM and DPS, aiming to understand the fundamental differences and potential advantages of each approach in the context of image inpainting and Gaussian deblurring tasks.

2. **Experimental Comparison**: We compare DDRM and DPS in practical scenarios, assessing their performance in image restoration tasks.

3. **Stochastic Sampling Evaluation**: We evaluate the stochastic aspect of the sampling process in DDRM.

4. **Extension to Non-linear Problems**: Exploration of extending the DDRM framework to tackle non-linear inverse problems.
   
## Contribution and Future Work

For detailed insights, methodologies, and results, please refer to our extensive report, which includes theoretical frameworks, experimental setups, results, discussions, and appendices for in-depth information.
