# AI advanced topic presentation outline

## Presentation 1

* Topic 1: History of AI in Video Games
	* Early Computer Game AI (traditional game recreations)
		* Nim
		* Strachey Checkers and Prinz Chess
		* Arthur Samuel's Checkers
		* IBM Deep Blue continuing the legacy
	* 1970s: Early Video Game AI (as we think of it)
		* Text-based games (e.g., Hunt the Wumpus, Daglow's Star Trek)
	* AI in the Golden Age of Arcade Games
		* Space Invaders
		* Pac-Man (maze games)
		* Karate Champ (fighting games)
	* Home Console/PC Video Game AI
		* Dragon Quest IV (tactics system)
		* Sports Games (e.g., Madden Football)
		* RTS Games
		* use of Finite State Machines
	* Common Uses of AI in Modern Video Games
		* Pathfinding
		* Combat AI
			* Halo, DOOM
		* Player experience modeling
		* Procedural generation
		* General adversarial networks
* Topic 2: Fighting Game AI and Implementation
	* Basics of fighting games
		* How fighting games work
		* Purpose of enemy design
		* Overview of AI in fighting games
	* How AI works in fighting games
		* AI logic and techniques in combat games
			* Decision making
				* Collision tables
				* Pattern Recognition
				* Case based reasoning
			* Finite State Machines
			* Behavior Trees
			* Implementation of AI in our project
		* Research on other AI techniques
			* Neural networks
			* Reinforcement learning
			* Clustering
	* Recent trends in combat games
		* Making human-like fighting games
			* Adapting to changes in player strategy
			* Ghost AI

## Presentation 2

* Topic 1 General Talk on Machine Learning
	* Machine Learning
		* Supervised vs unsupervised vs reinforcement learning
	* Reinforcement Learning
		* What is it used for
		* Where is it used
		* Markov Decision Process
		* Monte carlo
* Topic 2 Q - Learning
	* What makes q-learning different from other reinforcement learning techniques
		* Advantages of it versus other techniques
		* Where is it used and why
		* why we choose q learning
		* Limitations
* Topic 3 Algorithm & Important Variables
	* Math
		* learning rate
		* reward
		* discount factor
		* initial conditions
		* values
	* How do these factors affect the agent
* Topic 4 Implementation 	
	* Agents
		* The enemy AI will be the agent
	* Traits
	* What is the result of the process
	* How does it learn through this process
	* Game mechanics and how they relate to machine learning
		* Multiple movesets
		* How to implement reward system
		* How token system applies
		* Where are rewards given in our combat system

etails

## Presentation 3

* Topic 1 Line of Sight
	* Bresenham's Algorithm
		* What is it / pseudocode
		* Why we didn’t use it
	* Line Segment intersection algorithm
		* Introduction (What the algorithm does)
  		* How the algorithm works --> breakdown pseudocode
  		* Usage in our code & interaction with nodes
* Topic 2 Pathfinding
	* A* and Dijkstra’s algorithms
		* Pseudocode for Dijkstra’s
		* Benefits and drawbacks for Dijkstra’s
		* Examples of Dijkstra's algorithm
		* Pseudocode for A*
		* Benefits and drawbacks for A*
		* Examples of A* algorithm
		* Comparison between Dijkstras and A*
	* Implementations (Currently using Dijkstras, will move to A*)
		* Our code for Dijkstras & pseudocode comparison
		* Performance and demonstration
		* Our code for A* & pseudocode comparison
		* Performance and demonstration
	* Challenges and overcoming them
		* Problems with Dijkstra’s
		* Nodes within the map
		* Problems with A*
* Topic 3 Decision Making
	* How the path is interpreted by enemies
	* When the path is updated
	* Different types of motion for the enemy
	* How the enemy knows to reach player (active player on static graph)
	* Node Mesh Map
		* Implementation
	* Decision Making Process
		* Implementation
	

