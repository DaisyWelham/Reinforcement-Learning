The template is a bare-bones structure for building your own RL environments around.

The "Testting Environment" implements the "absent supervisor" environment from AI Safety Gridworlds ( https://arxiv.org/abs/1711.09883 ) and random and actor-critic agentss to test on it.

Each new agent is tested on absent supervisor, in a file with the name of the agent. Any other environments will be in a file named after the environment, with actor-critic and random agents tio test in it.
