# Unity_SRS_simulation
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This is a simulation of controlling multi-agents with deep learning in Unity3D. 

The purpose is to enable the agents spontaniously finish the foraging task, where the agents need to collaboratively to collect the yellow stuffs and transform them to the green area.

The controlling method utilized here is Deep Neuroevolution(DNE), a method similar to the Evolutionary Strategy, based on the Genetic Algorithm and DCNNs. It performs well on the complex tasks like foraging behavior and chainformation. When compared it to the Reinforcement Learning like DQN or DDPG, DNE can finish tasks better, especially with more disturbing items like the obstacles set in the playground or the continuous low-dimensional outputs of agents.

Design of the robot:
![](https://raw.githubusercontent.com/Louisasdjinn/Unity_SRS_research/master/robot1.jpg)
![](https://raw.githubusercontent.com/Louisasdjinn/Unity_SRS_research/master/robot2.jpg)
Scene of the task with obstacles:
![](https://raw.githubusercontent.com/Louisasdjinn/Unity_SRS_research/master/robot4.jpg)
Screenshots of the performance in playground with obstacles:
![](https://raw.githubusercontent.com/Louisasdjinn/Unity_SRS_research/master/robot3.jpg)

