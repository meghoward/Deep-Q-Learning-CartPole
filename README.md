# Reinforcement Learning Coursework 2

## Overview
This project focuses on implementing and optimizing a Deep Q-Network (DQN) to solve the CartPole problem using the OpenAI Gym environment. The coursework involves:

- Tuning the hyperparameters of a provided DQN to balance a pole on a cart.
- Visualizing the learned policy and Q-values of the optimized DQN.
- Generating clear and well-documented results through code and report submission.

## Requirements
To run the code, ensure you have the following installed:

- Python 3.8+
- PyTorch 1.11+
- OpenAI Gym (latest version compatible with the provided code)
- Matplotlib

To install the dependencies, run:

```bash
pip install -r requirements.txt
```

## File Structure

- `coursework2.ipynb`: The Jupyter Notebook containing the primary implementation, experiments, and visualization.
- `utils.py`: Additional utility functions and classes for the DQN and environment interactions.
- `coursework2_report.pdf`: The written report describing the methodology, results, and analysis of the experiments.

## Usage

### Running the Experiments
1. Open the `coursework2.ipynb` file in Jupyter Notebook or a compatible IDE.
2. Follow the notebook to:
   - Train and optimize the DQN.
   - Replicate experiments to generate learning curves.
   - Visualize the policy and Q-values.
3. Modify hyperparameters and model architecture in the code cells as needed to optimize performance.

### Visualizing Results
The notebook includes sections to:
- Generate learning curves for the DQN.
- Visualize 2D slices of the greedy policy and Q-values.
- Plot results using the `Cividis` colormap with appropriate annotations.

### Submission Guidelines
Ensure the following are included:
- `coursework2_report.pdf`: Contains your written analysis and results. Must adhere to the format specified in the coursework.
- `coursework2.ipynb`: Your Python notebook with the final implementation.
- `utils.py`: Contains any additional classes or functions used.

## Notes on Tuning

Key hyperparameters to tune:
- Learning rate
- Discount factor (gamma)
- Replay buffer size
- Batch size
- Exploration parameters (epsilon decay)

Reference the `Hyperparameters` section in the notebook and report for values and justifications.

## Visualization Standards
- Ensure all axes are labeled and include units where applicable.
- Use consistent and interpretable color schemes (e.g., `Cividis` colormap).
- Include legends and captions for all plots.
- Use appropriate error bars to indicate variability (e.g., standard deviation).

## Example Commands
To run the notebook:

```bash
jupyter notebook coursework2.ipynb
```

To execute the utility functions standalone for testing:

```bash
python utils.py
```

## Troubleshooting
- Ensure that the `env.reset()` and `env.step()` methods are compatible with the version of Gym you are using.
- Use the Lab Assignment 3 notebook as a reference for adapting environment calls if using Google Colab.

## Authors
This coursework was designed by Prof. Aldo Faisal, Filippo Valdettaro, and Charles Pert, under the guidance of Prof. Aldo Faisal & Dr. Nicole Salomons.
