# Physarum-Polycephalum-Network-Simulation
The simulation:
https://samjsnn.github.io/Physarum-Transport-Network/

Physarum Polycephalum is a unicellular organism that exhibits swarm like intelligence in it's ability to form efficient food networks. The goal of this project is to demonstrate how interactions at a micro level lead to the complex emergent behaviours observed in real slime molds.

![gif4b](https://github.com/samjsnn/Physarum-Transport-Network/assets/106383967/42d7bdcf-e737-4ca0-853b-f51c92bf18d1)


The core functionality of the simulation is mimicking the protoplasmic trails of Physarum Polycephalum. Agents within the simulation represent parts of the slime mold moving and interacting to form networks. The behaviour of these agents is regulated by three key parameters:

- Sensory Angle: Determines the breadth of each agent's sensory perception, influencing its ability to detect environmental stimuli and trail pheromones.

- Sensory Offset: Defines the distance ahead of each agent where it senses its environment. This parameter plays a crucial role in the direction and movement of the agent.

- Turn Angle: Influences the agent's ability to turn and change direction in response to the detected stimuli, allowing for dynamic navigation and network formation.

In addition to agent parameters the simulation environment is controlled by two main factors:

- Diffusion Rate: Affects the spread of pheromone trails left by agents. Higher diffusion rates lead to wider and more dispersed trails, influencing the likelihood of other agents encountering and following these trails.

- Evaporation Rate: Determines the longevity of the pheromone trails. Faster evaporation rates result in shorter-lived trails, requiring agents to constantly explore and adapt to new paths, avoiding reliance on outdated information.

![secondgif](https://github.com/samjsnn/Physarum-Transport-Network/assets/106383967/438f8634-fa03-451c-906d-6e659446b175) ![smallgif](https://github.com/samjsnn/Physarum-Transport-Network/assets/106383967/7a91039a-fd7f-4c50-a81f-8adc7669e661) ![gif3](https://github.com/samjsnn/Physarum-Transport-Network/assets/106383967/972d3591-9165-4115-a475-13438400871e)


You can interact with the simulation in real time to see how changes in parameters affect network formation. 

The controls are:

- A/S: Adjust Sensory Angle

- O/P: Adjust Sensory Offset

- T/Y: Adjust Turn Angle

- D/F: Adjust Diffusion Rate

- E/R: Adjust Evaporation Rate

The sensors are quite straightforward and work as such:

![sage jenson](https://github.com/samjsnn/Physarum-Transport-Network/assets/106383967/7dbc71d3-dad0-498e-a745-bd714136a298)

*(illustration by Sage Jenson)*



