Reinforcement learning is a framework for solving control tasks (also called decision problems) 
by building agents that learn from the environment by interacting with it through trial and error 
and receiving rewards (positive or negative) as unique feedback.


# Observation Space :
State : complete description of the state of the world (no hidden information)
Observation : partial description of state of the world 

# Action Space : 
Discrete : finite number of possible actions
Continuous : infinite number of possible actions

# Discount rate (gamma)
between 0 and 1 
The larger the gamma, the smaller the discount. This means our agent cares more about the long-term reward.

# Type of tasks 
Episodic : starting point and ending point
Continuing : task that continue forever

# Exploration / Exploitation trade-off
Exploration : trying random actions in order to find  more information about the environment 
Exploitation : using known information to maximize the reward 

# Policy-Based Methods (policy === brain of agent)
Deterministic : a policy at a given state will always return the same action. 
Stochastic : output a probability distribution over actions

# Value-Based  Methods 
The value of a state is the expected discounted return the agent can get if it starts in that state. 
value function defined values for each possible state.

