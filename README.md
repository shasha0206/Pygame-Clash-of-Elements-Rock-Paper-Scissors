Project Name - Pygame-Clash-of-Elements-Rock-Paper-Scissors

Initialization	- The code initializes the pygame module and sets up the game window with specified dimensions and loads background and images for rock, paper, and scissor.

Game Loop -	A while loop runs until the user exits the game. It handles events, updates object positions, checks for collisions, displays objects, updates scores, and checks for a winner.

Object Creation - Functions	Functions are defined to create rocks, papers, and scissors with random positions and velocities.

Collision Detection	- The collision function detects collisions between rocks, papers, and scissors. If a collision occurs, objects are removed from their respective lists, and their count is updated.

Rendering	- Objects are rendered onto the game window at their current positions.

Score - Display	The current counts of rocks, papers, and scissors are displayed on the screen.

Winner Declaration -	If one type of object has a count of zero, it declares the other two types as the winners accordingly (e.g., if rock count is zero, it declares scissors as the winner).

Exiting the Game	- The game can be exited by either closing the window or pressing the 'q' key.
