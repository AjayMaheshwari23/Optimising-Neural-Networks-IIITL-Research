# Optimizing Neural Networks for Mobile Devices

## Overview
This repository contains the code and experiments for our research paper on optimizing neural networks for mobile devices using a novel pipeline. Our pipeline combines pruning, knowledge distillation, weight clustering, and quantization to significantly reduce model size and computations while maintaining accuracy.

## Pipeline Steps
1. **Pruning**: Removing unnecessary connections to reduce model complexity.
2. **Knowledge Distillation**: Using a teacher-student framework to fine-tune the pruned model.
3. **Weight Clustering**: Grouping similar weights to further compress the model.
4. **Quantization**: Reducing the precision of weights for additional size reduction.

## Repository Structure
- `code/`: Contains all the scripts and modules for model processing.
  - `models/`: Model definitions for each stage of the pipeline.
  - `utils/`: Utility functions for pruning, distillation, clustering, and quantization.
  - `data/`: Scripts and datasets used in the experiments.

  - `experiments/`: Scripts to run experiments and store results.
  - `requirements.txt`: Python dependencies.
  - `main.py`: Main script to run the entire pipeline.

- `paper/`: Resources related to the research paper.
  - `figures/`: Figures used in the paper.
  - `references.bib`: Bibliography file.
  - `draft.pdf`: Draft of the research paper.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/optimizing-neural-networks.git
   cd optimizing-neural-networks
