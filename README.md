# Non-conventional Value Function Approximation methods in Reinforcement Learning

This project evaluates and compares different value function approximation methods in Reinforcement Learning.

### Function approximation models evaluated
  1. Neural Network
  2. Linear Model
  3. Decision Tree
  4. Random Forest
  5. Support Vector Regression
  6. K-Nearest Neighbours Regression
  7. Gaussian Processes
  8. Online Gaussian Processes

### Environments
  1. SimpleGridworld
  2. WindyGridworld
  3. CartPole
  4. LunarLander

### Evaluation Criteria
  1. Performance
  2. Reliability
  3. Sample efficiency
  4. Training time
  5. Interpretability
<br/>

## Getting started

Create and activate virtual environment:
```
python3 -m venv [name_of_venv]
source [name_of_venv]/bin/activate
```

Clone repository:
```
git clone https://github.com/atsiakkas/rl_vfa.git
```

Install requirements:
```
cd rl_vfa
pip install -e .
```
<br/>



## Project

https://github.com/atsiakkas/non_conventional_value_function_approximation<br/>
<br/>


## Contents

**agents**: Defines the classes of the RL agents: DQNAgent, LinearAgent, FQIAgent, OnlineGaussianProcessAgent

**custom_envs**: Defines the classes of the custom environments: SimpleGridworld, Windygridworld

**function_approximators**: Defines the classes of the function approximation models and of the replay buffer: ParametricModel, NeuralNetwork, LinearModel, NonParametricModel, DecisionTree, RandomForest, ExtraTrees, GradientBoostingTrees, SupportVectorRegressor, KNeighboursRegressor, GaussianProcess, eGaussianProcess, OnlineGaussianProcess

**plots**: Scripts (jupyter notebooks) for producing the plots used in the report and saved plots.

**results**: Saved output of runs (csv files).

**train**: Scripts (jupyter notebooks and .py files) for training and evaluation.

**utils**: Defines the training and plotting utility functions.<br/>
<br/>


## Key references

Reinforcement Learning algorithms: Richard S. Sutton and Andrew G. Barto. 2018. Reinforcement learning: An introduction. MIT press.

Fitted-Q Iteration: Damien Ernst, Pierre Geurts, and Louis Wehenkel. 2005. Tree-based batch mode
reinforcement learning. Journal of Machine Learning Research 6 (2005).

Online Gaussian Process: Lehel Csató and Manfred Opper. 2002. Sparse on-line Gaussian processes. Neural
computation 14, 3 (2002), 641–668.

Deep Q-Network: Volodymyr Mnih, Koray Kavukcuoglu, David Silver, Andrei A. Rusu, Joel Veness,
Marc G. Bellemare, Alex Graves, Martin Riedmiller, Andreas K. Fidjeland, Georg
Ostrovski, Stig Petersen, Charles Beattie, Amir Sadik, Ioannis Antonoglou, Helen
King, Dharshan Kumaran, Daan Wierstra, Shane Legg, and Demis Hassabis. 2015.
Human-level control through deep reinforcement learning. Nature 518, 7540
(2015). https://doi.org/10.1038/nature14236
