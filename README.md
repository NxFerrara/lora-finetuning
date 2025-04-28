# LoRA Fine-tuning for AGNEWS Text Classification

This repository contains code for LoRA-based fine-tuning of a RoBERTa model for text classification on the AGNEWS dataset, with a trainable parameter constraint of 1 million parameters.

## Project Overview

This project was developed for the Deep Learning Spring 2025 Project 2 [here](https://www.kaggle.com/competitions/deep-learning-spring-2025-project-2/overview). The goal is to apply LoRA fine-tuning to a pre-trained RoBERTa model to achieve high accuracy on the AGNEWS text classification task while keeping the number of trainable parameters under 1 million.

## Environment Setup

This project was developed and tested on Kaggle. Follow these steps to reproduce the setup:

1. Import the notebook from this repository.
2. Add the corresponding input data source:
   - Competition: "deep-learning-spring-2025-project-2"
   - Available at `kaggle/input/deep-learning-spring-2025-project-2/`

## Repository Structure

- `deep-learning-project-2.ipynb`: Main notebook containing the code for model definition (RoBERTa + LoRA), training, and evaluation.
- `README.md`: This file, containing setup instructions.
- `Project_2_Report.pdf`: Project report detailing the methodology and results.
- `inference_output.csv`: Submission file for the competition.

## Running the Code

1. Open the main notebook (e.g., `deep-learning-project-2.ipynb`) in Kaggle.
2. Run all cells in the notebook to:
   - Load and preprocess the AGNEWS data.
   - Define the RoBERTa model and apply LoRA modifications.
   - Train the LoRA adapters.
   - Evaluate on the test set.
   - Generate predictions for submission.