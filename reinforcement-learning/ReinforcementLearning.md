# Reinforcement Learning
[link to lesson](https://learning.oreilly.com/learning-paths/learning-path-python/9781789533408/9781789533408-part1)

### Basic pattern for reinforcement learning

1. Actions

2. Positive Rewards

3. Reinforced

4. More Likely to be repeated in the future

---

## High-Level Algorithm for Reinforcement Learning
| **Define all possible matches** | ----> | **Define state attributes that can be observed** | ----> | **Start a simulation of task** | ----> | **Try some random action, record the resulting state and reward** | ----> | **If episode terminates, start a new one** | ----> | **Start to prefer actions that are more likely to produce good rewards** |

---

"The critical issue in reinforcement learning, is how to identify the appropriate action for a given situation, based on what has been tried and succeeded in the past."

---

### Q-Learning
![Let's Get Technical](https://i.imgur.com/CufTPbI.png)
![Learning Q](https://i.imgur.com/EgFjVxh.png)
![Q Equation](https://i.imgur.com/3YBtS2C.png)

---

Some of the libraries in Python built for Reinforcement Learning are:
* [**rllab**](github.com/rll/rllab)
* [**TensorLayer** (deep neural net RL)](github.com/tensorlayer/tensorlayer)
* [**Keras-RL**](github.com/matthiasplappert/keras-rl)

Other Implementations:

[link](github.com/dennybritz/reinforcement-learning)
