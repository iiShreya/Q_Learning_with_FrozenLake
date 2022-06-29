# Q_Learning_with_FrozenLake

[Click here for the Huggingface link with a video of the implementation](https://huggingface.co/iiShreya/frozenLake_4x4_nonSlippery)

![Alt Text](https://raw.githubusercontent.com/iiShreya/Q_Learning_with_FrozenLake/master/video/frozenLake.gif)


# Q Learning Algorithm
Q = "the Quality" of that action at that state.
Q-learning is a model-free, value based, off-policy Reinforcement Learning algorithm which uses the Temporal Difference approach of updating the action-value function at each step instead of at the end of the episode, to learn the value of an action in a particular state. 

- Definition Keypoints:
1. Model-Free
2. Off-Policy
3. Uese TD Approach
4. Value Based Method

## Model-Free Algorithm
These algorithms seek to learn the consequences of their actions through experience. Such an algorithm will carry out an action multiple times, learn from its actions and will adjust the policy (the strategy behind its actions) for optimal rewards, based on the outcomes. 

Eg, Self-Driving Cars. 

## Model-Based Algorithm
In such an algorithm, an agent tries to understand its environment and creates a model for it based on its interactions with this environment. In such a system, preferences take priority over the consequences of the actions i.e. the greedy agent will always try to perform an action that will get the maximum reward irrespective of what that action may cause.

Eg, Playing Chess


## Off-Policy Algorithm
Such an algorithm uses a diffrent policy for Acting and Updating. 

Eg, In Q-Learning Algorithm:
Acting Policy: Epsilon Greedy Policy 
Updating Policy: Greedy Policy for selecting the best next-state action value to update the Q-value. 

## On-Policy Algorithm
Such an algorithm uses the same policy for Acting and Updating. 


# Q-Learning Algorithm Pseudocode

