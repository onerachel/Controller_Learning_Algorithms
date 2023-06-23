# A comparison of controller architectures and learning mechanisms for arbitrary robot morphologies

The main research question: What combination of a robot controller and a learning method should be used, if the morphology of the learning robot is not known in advance? 

We perform an experimental comparison of three controller-and-learner combinations: one approach where controllers are based on modelling animal locomotion (Central Pattern Generators, CPG) and the learner is an evolutionary algorithm, a completely different method using Reinforcement Learning (RL) with a neural network controller architecture, and a combination `in-between' where controllers are neural networks and the learner is an evolutionary algorithm. 

We apply these three combinations to a test suite of modular robots and compare their efficacy, efficiency, and robustness. Surprisingly, the usual CPG-based and RL-based options are outperformed by the in-between combination that is more robust and efficient than the other two setups. 

[note: The release version of Revolve2 used in this project is v0.3.1-beta1 (https://github.com/ci-group/revolve2/releases/tag/v0.3.1-beta1).]


## Installation 
``` 
1. git clone https://github.com/ci-group/revolve2 --branch v0.3.1-beta1
   or git clone https://github.com/onerachel/revolve2
2. cd revolve2/
   git clone https://github.com/onerachel/Controllers_Learners
3. virtualenv -p python3.8 .venv
   source .venv/bin/activate
4. pip install ~/isaacgym/python/
5. ./dev_requirements.sh
``` 
## Highlighted results
![ANN+RevDE](https://user-images.githubusercontent.com/75667244/222464951-180528d9-477c-46f3-9609-01bef6424df2.png)
![CPG+RevDE](https://user-images.githubusercontent.com/75667244/222464997-a95cbe31-cbff-4d23-b27c-8bd8c6e84ace.png)
![DRL+PPO](https://user-images.githubusercontent.com/75667244/222465037-a672ddc0-3b7f-414f-b47b-d5e500cab6b9.png)
<img width="520" alt="fitness_avg_max_lineplot" src="https://user-images.githubusercontent.com/75667244/222466564-36d89743-69d8-4e71-8d99-ae491a0c3891.png">
<img width="540" alt="fitness_MBF_params" src="https://user-images.githubusercontent.com/75667244/222467913-9dbb828a-1a23-4610-8980-54abd28020cb.png">
![fitness_MBF_params_subplots](https://user-images.githubusercontent.com/75667244/222467956-33a28478-02b7-492e-bcf4-271992ef4fbe.png)


## Documentation 

[ci-group.github.io/revolve2](https://ci-group.github.io/revolve2/) 
