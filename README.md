# Enhancing Data Efficiency in Reinforcement Learning: A Novel Imagination Mechanism Based on Mesh Information Propagation
Expected for further updation, we will update this pretty soon...


Openreview-Link:[comments](https://openreview.net/forum?id=H8RgPl5OQX)

* [📦 Install ](#install) -- Install relevant dependencies and the project
* [🔧 Usage ](#usage) -- Commands to run different experiments from the paper

## Install 
To install the requirements, follow these steps:
```bash
# PyTorch
conda install pytorch torchvision -c pytorch
export LC_ALL=C.UTF-8
export LANG=C.UTF-8

# clone the Jueru RL lib and install.
git clone https://github.com/lmd123123/Rl_lib

python setup.py install

# Install requirements
pip install -r requirements.txt

# Finally, clone the project
git clone https://github.com/lmd123123/MI_code_imagination_mechanism
```

## Usage:
```bash
# Train the IM+SAC
python sac_imagination.py

# monitor the result by tensorboard
tensorboard --logdir SAC_tensorboard/.
```
update pretty soon...

## What does each file do? 

Update pretty soon...

## Contact

If you have any questions, feel free to contact us or post github issues. Pull requests are highly welcomed!



## Acknowledgements

Thank you all for your attention to our work!

This code uses (DQN, DDPG, PPO, SAC) as baseline methods for comparison and further improvement.

We appreciate the following github repos a lot for their valuable code base or datasets:

https://github.com/haarnoja/sac

https://github.com/mila-iqia/spr

https://github.com/MishaLaskin/curl

https://www.github.com/MishaLaskin/rad

https://github.com/mila-iqia/SGI

https://github.com/nikhilbarhate99/PPO-PyTorch

https://github.com/openai/gym

https://github.com/google-deepmind/mujoco

Thank you for your attention.
