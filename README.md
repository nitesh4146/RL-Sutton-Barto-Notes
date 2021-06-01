# RL-Sutton-Barto-Notes

- The terms supervised and unsupervised learning would seem to exhaustively classify machine learning paradigms, except they do not. 
- Policy: A policy is a mapping from perceived states of the environment to actions to be taken when in those states. 
- Reward: A reward signal defines the goal of a reinforcement learning problem. 
- Reward: The reward signal is the primary basis for altering the policy 
- Value function: The value of a state is the total amount of reward an agent can expect to accumulate over the future, starting from that state. 
- Reward vs Value: Rewards are in a sense primary, whereas values, as predictions of rewards, are secondary.
- History: The history is a sequence of observation, actions, rewards

![rl-problem](./images/agent-env-model.png)

- State: Formally, a state is a function of history
- The environment state is the environment's private state and is usually not visible to the agent
- The agent state is the agent's internal representation
