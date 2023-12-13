# 11-785-Project

MCTS.ipynb:
This is the notebook used for final inference using a combination of trained value and policy networks for optimal image reassembly. The MCTS allows inference beyond the greedy solution presented in the policy network.

Policy_Network.ipynb:
Trained neural network using policy gradient reinforcment learning. The goal of this model is to output an aciton for which a series of actions completes the puzzle.

Value_Network.ipynb:
This code is used to train the value network that is used in the MCTS search. The goal of the value network is to score how close a given puzzle reassmebly is to the correct reassembly.

MNIST_Data.zip:
MNIST Data in CSV form

Baseline_Implementation.ipynb:
Baseline implementation of two feature network supervised model

#Instructions to Run the Code

1. Run the Policy_Network.ipynb using the input dataset to train the policy network and produce the policy network model
2. Run the Value_Network.ipynb using the input dataset to train the value network and produce the value network model
3. Use the input dataset along with the trained value and policy network to reassemble the puzzles
