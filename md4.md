https://huggingface.co/learn/deep-rl-course/unit4/what-are-policy-based-methods

### Policy Gradient

Policy Gradient is a reinforcement learning method in which the agent learns an optimal policy (action strategy) directly, without having to estimate values as in Q-learning.

The idea is to adjust action probabilities to maximize total reward over the long term. Instead of saying “this action is worth X points”, the agent learns which action is most likely to be good and performs it more often.

Example: A robot learning to walk will gradually adjust the way it moves to maximize its stability and speed, favoring the gestures that work best for it.