Conway's Game of Life
=======================

Description
------------

Conway's game of Life (an example of a cellular automaton) is played on an infinite two-dimensional rectangular grid of cells. Each cell can beeither alive or dead. The status of each cell changes each turn of the game (also called a generation) depending on the statuses of that cell's8 neighbors. Neighbors of a cell are cells that touch that cell, either horizontal, vertical, or diagonal from that cell.

The initial pattern is the first generation. The second generation evolves from applying the rules simultaneously to every cell on the game board, i.e. births and deaths happen simultaneously. Afterwards, the rules are iteratively applied to create future generations. For each generation of the game, a cell's status in the next generation is determined by a set of rules. These simple rules are as follows:

* If the cell is alive, then it stays alive if it has either 2 or 3 live neighbors

* If the cell is dead, then it springs to life only in the case that it has 3 live neighbors

