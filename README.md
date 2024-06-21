# ARTIFICIAL-INTELLIGENCE-Minimax-Alpha-beta-pruning

Q1: Game playing is an essential part of AI and is the basis for many search techniques.
Adversarial search refers to problems in which the agents’ goals are in conflicts and may times
refer to zero sum games where the win for one is the loss for the other. Minimax algorithm tries
to find the optimal moves assuming that both the players play optimally.

Consider a scenario where tic-tac-toe is being played and the optimal move is found using
minimax algorithm.

Q2: Note, for each of the following:
1) Assume a random starting position.
2) Perform 3 runs of the code.

Perform the following evaluations, using the code in the previous question:
1) Calculate the average number of nodes that would be evaluated using the minimax

algorithm without pruning and compare it to the number of nodes evaluated with alpha-
beta pruning.

2) Implement a parallel version (2 threads) of alpha-beta pruning and compare its
performance with sequential version.

3) Develop a heuristic for non-terminal states that would assist in reducing the search
space (enhanced alpha-beta pruning) and compare it to the standard alpha-beta pruning
algorithm.
Hint: During the search process, when evaluating non-terminal states, use the heuristic to
estimate the desirability of each state. Instead of exploring all possible moves to determine the
exact value of a state, use the heuristic to prioritize which branches of the search tree are more
promising. This involves comparing heuristic values and using them to guide the selection of
moves and pruning of branches.


4) Develop a tic-tac-toe game, where the AI is a “weak” player. Modify the game in the
following manner:
a) The “weak” player does not choose the best decision nor the worst decision but
instead relies on randomization.
b) Randomly pick a tile at the start of the game, which the “weak” player will not use
during the game.
c) Use a heuristic to define the desirability of a state.
