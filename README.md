# <img src="https://github.com/haeriamin/files/blob/master/erl1.gif">

# Emotion-Based Reinforcement Learning using Unity ML-Agents and TensorFlow

## Python Setup

To install, run:

`python3 -m venv ./venv`

`source ./venv/bin/activate`

`pip install --upgrade pip`

`pip install -r requirements.txt`

## Training PPO directly

To train using PPO, run:

`python3 ppo.py <env_name> --train`

Where `<env_name>` corresponds to the name of the built Unity environment.

For a list of additional hyperparameters, run: `python3 ppo.py --help`

## Training on AWS

See this related [blog post](https://medium.com/towards-data-science/how-to-run-unity-on-amazon-cloud-or-without-monitor-3c10ce022639) for a description of how to run Unity Environments on AWS EC2 instances with the GPU.
