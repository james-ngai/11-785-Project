# 11-785-Project

MCTS.ipynb
This is the notebook used for final inference using a combination of trained value and policy networks for optimal image reassembly. The MCTS allows inference beyond the greedy solution presented in the policy network.

PolicyNetwork.ipynb
Trained neural network using policy gradient reinforcment learning. The goal of this model is to output an aciton for which a series of actions completes the puzzle.

ValueNetwork.ipynb
Model outputs a value between [0,1] used for value in MCTS

MNIST_Data.zip
MNIST Data in CSV form
