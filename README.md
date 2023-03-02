# A comparison of controller architectures and learning mechanisms for arbitrary robot morphologies

The main research question: What combination of a robot controller and a learning method should be used, if the morphology of the learning robot is not known in advance? 

We perform an experimental comparison of three controller-and-learner combinations: one approach where controllers are based on modelling animal locomotion (Central Pattern Generators, CPG) and the learner is an evolutionary algorithm, a completely different method using Reinforcement Learning (RL) with a neural network controller architecture, and a combination `in-between' where controllers are neural networks and the learner is an evolutionary algorithm. 

We apply these three combinations to a test suite of modular robots and compare their efficacy, efficiency, and robustness. Surprisingly, the usual CPG-based and RL-based options are outperformed by the in-between combination that is more robust and efficient than the other two setups. 


## Installation 
``` 
1. git clone https://github.com/onerachel/revolve2  [note: The release version of Revolve2 used in this project is v0.3.1-beta1 (https://github.com/ci-group/revolve2/releases/tag/v0.3.1-beta1).]
2. cd revolve2/
   git clone https://github.com/onerachel/Controllers_Learners
3. cd ..
   virtualenv -p python3.8 .venv
   source .venv/bin/activate
4. pip install ~/isaacgym/python/
5. ./dev_requirements.sh
``` 
## Partial results


## Documentation 

[ci-group.github.io/revolve2](https://ci-group.github.io/revolve2/) 
