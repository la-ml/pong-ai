# Pong AI

This is the final project for CSCI 379 (Intro to AI & CogSci, Spring 2017).

## Team Reveries:

-   Yash Bhutwala
-   Matt McNally
-   Kenny Rader
-   John Simmons

## Problem Statement

Given a set a pixels from a game of Pong, a mechanism for measuring wins and losses,
and a hard-coded opponent agent, could we create an agent that could potentially
beat a human opponent, and what would be the best way to do that?

Our approach tests Deep Q-Learning Networks (DQN) against Policy Gradient (PG) learning in
order to see which algorithm and architecture learns the best.

## How to run the programs:

### Deep Q-Learning (DQN)

Our DQN agent can be ran from the ./dqn directory. You can run it by using the command:

```bash
python main.py --env_name=Pong-v0 --is_train=True --display=True
```

This will run the program on the Pong environment with Training Mode and Rendering
turned on.

### Policy Gradient (PG)

Our PG agent can be ran from the ./pg directory. You can run it by using the command:

`python3 yashPong.py`

This will run the agent in Training Mode and Rendering turned on by default, though
this can be changed in code.

## Acknowledgements:

The code for our DQN approach is modified from existing code from devsisters.
The original repository can be found [here](https://github.com/devsisters/DQN-tensorflow)

Likewise, the code for our PG approach is modified from existing code from Dr. Andrej
Karpathy. The original code can be found [here](https://gist.github.com/karpathy/a4166c7fe253700972fcbc77e4ea32c5)
