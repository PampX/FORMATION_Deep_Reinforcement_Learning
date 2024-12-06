# Two types of Value based methods

## State Value Function V(s)
It evaluates “how good the condition is” in a given policy.

Useful if you simply want to evaluate the condition, for example to understand whether a condition is “good” or “bad”.

## Action Value Function Q(s,a)
It evaluates “how good this action is in this state”, taking into account future consequences.

Useful for deciding which action to take, as it distinguishes between the various possible actions.

## Monte Carlo: learning at the end of the episode
update the value function from a complete episode, and so we use the actual accurate discounted return of this episode.

## Temporal Difference Learning: learning at each step
update the value function from a step, and we replace
Gt, which we don’t know, with an estimated return called the TD target