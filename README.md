<h1> Artificial Intelligence Implementation CEN 352 - Artificial Intelligence<br/>2022 - 2023 Spring Semester</h1><br/><br/>



<h2> Description </h2>
In this implementation, I have created an AI which can solve a 7-Puzzle and a Jewels Maze game.</br></br>

The 7-puzzle is played in a 3x3 board, containing 7 tiles numbered 1 to 7 and two empty cells. Unlike the original 8-puzzle, the 7-puzzle that we are dealing with in this problem, can have tiles of different weights, so the cost of the move is equal to the wight of the tile that is being moved.<br>
I have written a Python program which automatically reads the weights from the file weights.txt, then reads as input (from the user) the name of the file containing the initial state of the board. Note: if the weights.txt file is not available, then the program should automatically assign the weight 1 to each tile. The program should generate as a result three output files (<inputfilename>BFS.txt, <inputfilename>UCS.txt and <inputfilename>AStar.txt) which contain the complete solutions using:<br>
a. Breadh-first search (notice that optimality is not guaranteed in this case).<br>
b. Uniform-cost search<br>
c. A* with heuristic function the sum of products of the form (weight × Manhattan distance from its goal position) for each tile<br>
The file weights.txt contains just 7 numbers delimited by whitespaces (representing the weights of tiles 1, 2, 3, 4, 5, 6, 7 respectively). The input file contains three lines representing the initial state of the board.<br>
The output file will show in the first three lines the number of explored states, the length of the solution path (i.e. number of moves) and the cost of the solution path. Then all steps of the solution will be shown giving the move and the resulting state.


In the Jewels Maze, there are three types of jewels: red, green and blue. Our agent is initially positioned at location denoted with letter A. The goal of the agent is to collect at least one jewel for each type. As usual whitespaces represents cells that the agent can walk through, while the # symbol represents the walls.<br>
Here, I have implemented the following methods:<br>
a. Depth first search<br>
b. Breadth first search<br>
c. A* search (where I have adapted an appropriate heuristic)<br>
d. A method which will generate a drawing depicting the solution path (in light green), all the jewels in their respective colors (R,G,B), the explored nodes in dark grey and unexplored nodes in white.</br>

This project has been implemented in Python, using Google Colaboratory.<br/>
