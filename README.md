# N-Dimensional Prisoner's Dilemma
We trained multiple agents by playing N-player prisoners dilemma game against each other using deep reinforcement learning method. 
The agent looks at previous 15 actions of each player and decides the current move. State is defined by the previous 15 moves combined. Each episode consists of T rounds where the agent learns, and changes its weights according the reward provided after each round. M episodes are played, and the state is refreshed after each game.
