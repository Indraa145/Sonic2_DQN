# Playing Sonic the Hedgehog 2 using Deep Q-Learning (DQN)

This code implementation is based on this repository by deepanshut041:
https://github.com/deepanshut041/Reinforcement-Learning/tree/master/cgames/06_sonic2

# How to Run
These are the steps to run the program:
1. Download the ROM for Sonic the Hedgehog 2 for SEGA Genesis.
2. Import the ROM by running ```python3 -m retro.import /path/to/your/ROMs/directory/``` in your terminal.
3. If you want to train the agent, run the following command ```python sonic_dqn.py --train_mode True``` in your terminal.
4. If you want to test the agent, run the following command ```python sonic_dqn.py --train_mode False --load_model True --model_name your-model-name``` in your terminal. For the ```--model_name``` argument, you have to provide both the policy and target network. Separate them with comma (,) and no spaces, for example ```python sonic_dqn.py --train_mode False --load_model True --model_name my-policy-net,my-target-net```.

# Results
The results can be seen in the report file ..., or for a more visual results, refer to the accompanying video here: ...
