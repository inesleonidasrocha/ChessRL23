# Chess Reinforcement learning

This was a project developed by Inês Rocha, Isabel Dias, Joana Sousa and Rafael Dinis. This project was developed within the scope of the Reinforcement Learning class at Nova IMS.

**Introduction**
The primary objective of this project is to develop an **RL agent that can play chess at a high level of proficiency**. The agent should be capable of evaluating chess positions and making strategic decisions. However, chess is a complex task to solve, as it has a very high number of potential states, and each state is associated to specific legal actions.
Overall, three distinct approaches were tried to tackle this problem: **Monte Carlo Tree Search (MCTS)**, **Deep SARSA** and **Deep Q-Learning** in combination with **Imitation Learning**. MCTS has a strong theoretical foundation and has been proven to work well in chess. Deep SARSA and Deep Q-Learning allow to handle the computational complexity of the problem, and Imitation Learning allows to leverage knowledge from experts to enhance the agent’s decision-making. This allowed for the exploration of different types of reinforcement learning models, on and off policy, and models with and without value function approximation. It was also taken into consideration the complexity and high dimensionality of the space, which would incapacitate the use of certain models without value function approximations.

![Alt Text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.chess.com%2Fgifs&psig=AOvVaw38G-u8X_WT4daJ3H9bBaex&ust=1687733707909000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCKDQ5ZOA3f8CFQAAAAAdAAAAABAR)

**Future Works**
* Tune our 3 models, in order to get more wins against the Stockfish engine (with various degrees of Elo rating).
* Implement other visualizations to analyse the performance of our models and get more insights on how to improve it.
* Make a gui that makes possible for a user to play with our models.
