#### CMSC828I
Project CMSC 828I (Fall 2020)

Topic: GAN Based Top-Down View Synthesis in Reinforcement Learning Environments

Aim is to generate (predict) the top-down view of an environment using the first-person view observations of the agent 
with a generative adversarial network (GAN).The agent can only see a partial observation and only a partial top-down 
view is generated by the agent initially. As the agent explores the environment through a set of actions, the generated 
top-down view will become complete. As a result, the agent learns a representation of the environment from experience. 
The baseline will be training a PGAN with the state transitions sampled from the agent’s memory.
