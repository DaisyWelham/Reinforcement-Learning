The template is a bare-bones structure for building your own RL environments around.

The "Testing Environment" implements the "absent supervisor" environment from AI Safety Gridworlds ( https://arxiv.org/abs/1711.09883 ) and random and actor-critic agents to test on it.

Each new agent is tested on absent supervisor, in a file with the name of the agent. Any other environments will be in a file named after the environment, with actor-critic and random agents to test in it.

Actor-critic is our standard policy-based reinforcement learning agent which picks actions directly. DeepQ is value-based, learning the value of taking a particular action from a particular state and requiring an optimization algorithm to actually pick actions. Check out the evolutionary computation repo for options here: https://github.com/DaisyWelham/Optimization-Evolutionary-Computation

Imitation learning is really cool, we can train agents to copy an "expert" policy, with the option of either copying directly or further fine-tuning the agents in an attempt to gain improved performance.
