This repository hosts an advanced implementation of the DIAMOND Simulation—a dynamic, interactive model that demonstrates how agents navigate, learn, and adapt within a complex and ever-changing environment. Built with HTML5 and JavaScript, the simulation leverages modern web technologies for an engaging visualization and interactive experience.

Key Features:
Grid-Based Environment:

A 2D grid representing the world state where each cell holds a reward value.
Static Obstacles: Fixed barriers that agents cannot pass through, adding complexity to navigation.
Dynamic Obstacles:
Moving Obstacles: Obstacles that change their positions over time, requiring agents to adapt their paths dynamically.
Random Obstacles: Obstacles that appear and disappear randomly during the simulation, simulating an unpredictable environment.
Traps: Special cells that reduce the agent's reward when visited, encouraging agents to learn to avoid them.
Terrain Types: Cells with different terrain (normal, slow, fast) affecting agent movement speed and strategy.
Advanced Agent Modeling:

Multiple Agents: Support for simulating multiple agents (up to 10), each with unique identifiers and colors for differentiation.
Agent Strategies:
Random Movement: Agents move in random directions.
Greedy Search: Agents move towards neighboring cells with the highest predicted rewards.
Q-Learning: Implementation of a basic Q-learning algorithm allowing agents to learn optimal policies through experience.
Learning Algorithms:

Q-Learning Implementation: Agents use Q-learning to update their policy based on rewards received, balancing exploration and exploitation.
Prediction State: Agents maintain an internal prediction of the environment, updating it based on observations and learning rate.
Diffusion Process:

Dynamic Environment: Cell values diffuse to neighboring cells over time, simulating processes like heat distribution or scent dispersion.
Adjustable Diffusion Steps: Users can control how rapidly the diffusion process occurs.
Interactive Visualization:

World Canvas: Displays the current state of the environment with color-coded cells indicating reward levels, terrain types, and obstacles.
Dynamic Obstacles Visualization: Moving obstacles are animated, and traps are visually distinct, enhancing the simulation's realism.
Prediction Canvas: Shows each agent's internal prediction of the environment.
Agent Representation: Agents are visualized as colored dots with trails showing their movement paths.
Real-Time Updates: The simulation updates in real-time, reflecting changes in agent positions and environment dynamics.
User Controls:

Simulation Controls: Start, stop, reset, and step-through functionalities.
Parameter Adjustments: Real-time control over diffusion steps, learning rate, agent speed, agent strategies, and the number of agents.
Information Panel: Displays detailed statistics for each agent, including position, accumulated reward, steps taken, and prediction accuracy.
Data Logging and Analysis:

Simulation Data Log: Records agent data at each time step for post-simulation analysis.
Performance Metrics: Calculation of average prediction accuracy across agents.
Accessibility of Data: Logged data can be accessed via the browser console for further examination.
Educational Value:
This simulation serves as a powerful educational and experimental tool for:

Understanding Agent-Based Modeling: Observe how individual agents make decisions based on different strategies and how these decisions affect their performance in a dynamic environment.
Learning Reinforcement Learning Concepts: Explore the basics of Q-learning and how agents learn from interactions with their environment, especially when facing dynamic obstacles and traps.
Visualizing Diffusion Processes: See how values propagate through a grid over time, influenced by obstacles, terrain, and environmental changes.
Experimenting with AI and ML Algorithms: Modify parameters and strategies to see firsthand how changes impact agent behavior and learning outcomes in complex settings.
Getting Started:
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/advanced-diamond-simulation.git
Open the Simulation:

Navigate to the cloned directory.
Open the enhanced_simulation.html file in a modern web browser (e.g., Chrome, Firefox).
Interact with the Simulation:

Use the on-screen controls to adjust parameters.
Click Run to start the simulation or Step to advance one step at a time.
Observe how agents interact with the environment, navigate dynamic obstacles, and learn over time.
Future Enhancements:
Advanced Pathfinding Algorithms: Implementing algorithms like A* for more sophisticated agent navigation.
Enhanced Learning Models: Incorporating more complex reinforcement learning models like Deep Q-Networks (DQNs).
Multi-Agent Interactions: Introducing cooperation or competition between agents to study emergent behaviors.
User Interface Improvements: Adding graphs and charts for better visualization of agent performance and learning curves.
Data Export Options: Allowing users to download simulation data for external analysis.
Contributing:
Contributions are welcome! If you're interested in improving the simulation or adding new features:

Fork the repository.
Create a new branch for your feature or bug fix.
Submit a pull request with a detailed description of your changes.
License:
This project is licensed under the MIT License. See the LICENSE file for details.

