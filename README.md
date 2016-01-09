# Game-of-Life
Conway's Game of Life

@author Adrienne Bergh
@author PJ Titterton

# Program Components
- Simulation that models the life cycle of bacteria
- Rules: A location that has one or fewer neighbors will be empty in the next generation. A location with two neighbors remains stable. A location with three neighbors will contain a cell in the next generation. A location with four or more neighbors will be empty in the next generation due to overcrowding. The births and deaths that take place one generation to the next must all take place simultaneously.
- Ask the user if they would like a random assignment for the initial population, or provide a map file. If a random assignment is chosen, randomly generate initial cell configuration using dimension and density inputs from user.
- Prompts users to decide which mode they wish to play in, which affects how neighbors are calculated. Classic mode: All locations off the grid are considered to be empty. Mirror Mode: References off the grid are bounced back as though the wall were a mirror. Doughnut mode: The grid is wrapped around itself horizontally and vertically, resulting in a torus (doughnut) shape.
- If no births or deaths occur from one generation to the next, the game is considered to be "stable" and the program will quit.
 
