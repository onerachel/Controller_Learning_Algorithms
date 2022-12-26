# Robot Controllers + Learners 

Combination of 3 different types of controllers (CPG, DRL-Policy controller and NN) and 3 different types of learning algorithms (RevDE, PPO and NES) for robot locomotion using Mujoco and Isaacgym based wrapper Revolve2. Mujoco enviroment is preferred by the author. The release version of Revolve2 used in this project is v0.3.1-beta1 (https://github.com/ci-group/revolve2/releases/tag/v0.3.1-beta1).

## Installation 
``` 
1. Download isaacgym from https://developer.nvidia.com/isaac-gym
2. git clone https://github.com/onerachel/revolve2
3. cd revolve2/
   git clone https://github.com/onerachel/Controllers_Learners
4. cd ..
   virtualenv -p python3.8 .venv
   source .venv/bin/activate
5. pip install ~/isaacgym/python/
6. ./dev_requirements.sh
``` 
## Partial results
![fitness_avg_max_lineplot](https://user-images.githubusercontent.com/75667244/209528586-7d6b0864-0ce3-463c-bed3-1452296d4de9.png)


## Documentation 

[ci-group.github.io/revolve2](https://ci-group.github.io/revolve2/) 
