# EPFL course CS456 (Artificial Neural Networks): Reinforcement learning with Pong

you will need to install Pygame, Pillow, and the PyGame Learning Environment. To do so, the easiest workflow to follow is:

pip3 install Pillow
pip3 install pygame
git clone https://github.com/ntasfi/PyGame-Learning-Environment
cd PyGame-Learning-Environment
pip3 install -e .

The project consits of implementing a Policy Gradient algorithm that learns to play Pong.
We achieved that through learning a policy function π(a|s) which selects the best action a to pick given a state s and a Value function V(s) 
that predicts the total expected discounted reward starting at state s. 
