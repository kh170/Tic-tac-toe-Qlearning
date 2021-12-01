To run the code for tic tac toe using Q learning. Please take the following steps:

1. Open terminal and type Jupyter Notebook. The code is in .ipynb file so it must be run using Jupyter Notebook.

2. Install the necessary libraries mentioned in the first cell of the code using the following command in the terminal or jupyter notebook:

pip install numpy tk pickle-mixin matplotlib seaborn (also commented out in cell 2)

3. In the cell 4  initialize the variables:
	grid_size = 3 (3by3 board) or 4 (4by4 board)
	N_episodes = Number of iterations or games
	decay = 0 (for greedy epsilon strategy) or 1 (for epsilon decay)
	epsilon = any number between 0 and 1 for decay = 1 
	epsilon_init = initial epsilon 
	epsilon_end = final epsilon
	sym = 1 (for including symmetry) 
	epsilon/epsilon_init = 1 for complete random move
	epsilon/epsilon_end = 0 for complete greedy move

4. Run cell 4 to initialize the game, board, and the different player classes

5. Run cell 5 to train agent and save the trained Q table in a .p file:
	
	
6. Run cell 6 to extract the Q values from .p file and play the game with the learned Q player. If the game doesn't work in the first go, please press 'reset' and play.
