
# Visualistaion of crazyflie going to goal point through obstacles.
<h2>About this Project <h2>

This project is about Visualistaion and implementation of crazyflie going to goal point through obstacles using isaac sim virtual environment.

<h3>1. prerequisites<h3>

Download the Essential program
Download the NVIDIA isaac sim and Nucleus.
Setting up all the environment

1.1 change the file

In .local/share/ov/pkg/isaac_sim-2022.2.0 folder, put this file inside.

<h3>2. Run the Model training<h3> 
Use this command to train program ./python.sh ./Crazyflie/train.py
Make sure connected with nucleus.
If not it will gives you an error.

<h3>3. Continuing train<h3>

Check the number of step saved in CNN policy folder.
Change the file name in train.py file.
Use this command to train program ./python.sh ./Crazyflie/train.py to retrain.

<h3>4.Evaluation and Run demo<h3>

check the number of step saved in CNN policy folder.
Put proper number of step you want to evaluate in eval.py file
Use this command to evaluate and visualise the program ./python.sh ./Crazyflie/eval.py

5.Reference

NVIDIA ISAAC SIM https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/tutorial_advanced_rl_stable_baselines.html

Isaacgym
https://github.com/NVIDIA-Omniverse/OmniIsaacGymEnvs




