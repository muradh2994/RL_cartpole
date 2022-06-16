# CartPole-v0

This is a solution to solve the OpenAI gym CartPole-v0 environment.

# Q learning

Q learning is a model-free reinforcement learning algorithm. It will learn a policy which will tell it what to do given a certain situation. Over the course of training, the Q learning will update its policy to find the optimal (or the closest it can get) action given a state.

On every run the Q table is updated with a new Q value. This is defined in the above equation. This takes the existing value and multiplies it by the learned value. The learned value is a compibation of the reward from the latest move and the maximum Q value from the new state
