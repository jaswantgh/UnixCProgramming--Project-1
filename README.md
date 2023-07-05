# UnixCProgramming--Project-1

In my second year, I was given my first assignment for the Unix and C Programming unit. The assignment required me to design and implement a simple game playable on a Linux terminal. The game was a basic box terminal maze, and all the specifications were provided in detail.

We were directed to watch supplementary videos available on the Blackboard assignment link. These videos demonstrated the desired functionality of the final program. The objective was clear - to code an executable game following specific parameters and requirements.

The executable was to be named "box", accepting six command-line parameters: map_row, map_col, player_row, player_col, goal_row, and goal_col. The first two defined the size of the playable map area, excluding the borders, and the next four represented the location coordinates of the player and the goal respectively. While the user inputs were assumed to be proper integers, it was crucial to reject negative numbers and ensure the minimum numbers for row_map and col_map were at least five.

The challenge didn't end there. If the number of arguments was either too many or too few, the program had to display a message on the terminal and end accordingly without using the exit() function. Similarly, if an argument fell out of the correct range, the program needed to terminate in the same manner.

Given that the player could enter any number for the map size, I had to properly use the malloc() function to allocate sufficient memory for the 2D array for the map. In accordance with C89 coding standards, I couldn't allocate the size of stack-based array with a variable. 

The experience was not only rewarding but also immensely enriching as I honed my Unix and C Programming skills.
