# Auto-regressive Models - Advanced Course on Deep Generative Models

## Overview
This repository contains the solution for **Exercise 4: Auto-regressive models** from the Advanced Course on Deep Generative Models, Spring 2024. The assignment focuses on implementing and experimenting with auto-regressive models using masked convolutions, as well as exploring the effects of causal and non-causal convolutions on image generation.

## Assignment Details

- **Instructor**: Dan Rosenbaum
- **Due Date**: 16 June 2024
- **Main File**: `main.ipynb`

### Key Tasks
1. **Masked Convolutions**: Implement a version of the model using masked convolutions with vertical/horizontal stacks. Train and log the negative log likelihoods for both training and validation/test.
2. **Non-causal Convolutions**: Investigate the effect of non-causal convolutions on the predictions. Log the same metrics and generate samples.
3. **Probability Estimations**: Compute or approximate several marginal and conditional probabilities for different pixels in the image.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/autoregressive-assignment.git
   cd autoregressive-assignment
2. Open the main.ipynb notebook in Google Colab or Jupyter Notebook.

3. Run all cells to:
  * Train the model with masked convolutions.
  * Explore the effect of non-causal convolutions.
  * Compute probabilities and generate image samples.
