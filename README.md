# $n$-step TD Learning

This repository contains implementations of Temporal Difference (TD) learning algorithms applied to the OpenAI Gym Taxi-v3 environment. The project is composed of three algorithms, each of these methods is explored and experimented to analyze their performance in the discrete decision-making domain.



## Agents

### QLearning

QLearning is a model-free RL algorithm that learns the value of an action in a particular state. It does not require a model of the environment.

$Q(s, a) \leftarrow Q(s, a) + \alpha \left[r + \gamma \max_{a'} Q(s', a') - Q(s, a)\right]$

### N-Step SARSA
N-step SARSA is an extension of the standard SARSA (State-Action-Reward-State-Action) learning algorithm, using the idea of looking n-steps ahead in the action-value updating rule. This approach helps in accelerating the learning process by leveraging more future information.

### N-Step QLearning
N-step QLearning is again a variant of QLearning that also looks n-steps ahead before updating the value estimates.


## Results
Results from our experiments indicate how each algorithm performs in terms of cummulative reward across various episodes.

![cumm_reward](https://github.com/Bortrex/TD_learning/assets/24497590/286a1b95-8b2d-4f9b-b4fd-41faeba4b759)

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Authors

- Your Name – [@Bortrex](https://github.com/Bortrex)


