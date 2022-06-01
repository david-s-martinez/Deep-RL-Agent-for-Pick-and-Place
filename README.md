Deep reinforcement learning agent to allow a robot to pick and place a moving packet. It is trained using a DQN made with pytorch and a pygame environment.
# Environment
The environment is composed of the tool center point of the gripper (red square) and the moving packet (brown rectangle).
![alt text](https://github.com/davidmartinez13/Deep-RL-Agent-for-Pick-and-Place/blob/main/images/real_robot.png)
![alt text](https://github.com/davidmartinez13/Deep-RL-Agent-for-Pick-and-Place/blob/main/images/rl_agent_demo_1.png)
# Goal of game
The goal of the game is for the RL agent to land the gripper on the center of the packet.
![alt text](https://github.com/davidmartinez13/Deep-RL-Agent-for-Pick-and-Place/blob/main/images/rl_agent_demo_2.png)