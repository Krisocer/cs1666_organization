# CS1666 Team Fourtnite Management weeks

1. 09/14 - 09/20
	* Manager: NAME
	* Goals:
		1. Setup game repo
		2. Add team description
2. 09/28 - 10/04
	* Manager: Gavin Heinrichs-Majetich
	* Goals:
		1. Create game credits
2. 10/05 - 10/11
	* Manager: NAME
	* Goals:
		1. ...
		1. ...
		1. ...
2. 10/12 - 10/18
	* Manager: Dan Li
	* Goals:
		1. Create a start menu
		2. Add character sprite to scene. Allow movements in up, down, left, and right directions with the approriate speed. 
		3. Allow scrolling in all directions of a non-generated map, 5000*3000px in size.
2. 10/19 - 10/25
	* Manager: Camryn Simons
	* Goals:
		1. Optimize the current working recursive WFC algorithm and begin to transform it into an iterative algorithm
		2. Develop basic prototype battle UI that displays monster’s stats and health
		3. Trigger battle screen through “hitting” monster
		4. Finalize RPS Demo to ensure fully working demo 
2. 10/26 - 11/01
	* Manager: Chase Bradley
	* Goals:
		1. Tile generation improvements: Allow seeding chunk generation. This means allowing us to pass predetermined tiles to the generation algorithm which will always have their concrete type regardless of the surrounding generation. An Additional factor, take tile frequency into account for chunk generation.  The distribution of tile types within a generated chunk should be approximately equal to the distribution of those types within the input chunk
		2. Infinite world generation: The player should be allowed to walk infinitely far in any direction, with chunks being generated as before they walk off the edge of any given chunk. These chunks edges should abide by adjaceny rules
		3. Setup a connection between players, be able to hit and detect signal
2. 11/02 - 11/08
	* Manager: Nathan Myers
	* Goals:
		1. Implement combat logic (attack, defend, heal, etc.) for battles. Battles should end when one player's health is depleted.
		2. Properly manage turn based actions between a host and a client.
		3. Correct seeding issue caused by entropy or adjacency miscalculation.
2. 11/09 - 11/15
	* Manager: Prateek Jukalkar
	* Goals:
		1. Reworking battle logic to decouple the player from the player's monsters
		1. Implement typing into the monster system
		1. Allow for communication between main game thread and player thread
2. 11/16 - 11/29
	* Manager: NAME
	* Goals:
		1. ...
		1. ...
		1. ...
2. 11/30 - 12/06
	* Manager: Caela Go
	* Goals:
		1. Implement advanced movesets
		2. Make enemies take their own turns outside of counterattacks 
		3. Exchange and update battle stats upon player's turn
 		4. Display some sort of message indicating winner of battle
		5. Add graceful exit to start menu after battle is completed
		6. Handle player quitting mid-game
		7. Handle dropped packets		
