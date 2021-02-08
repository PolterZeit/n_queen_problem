![UiO Logo](https://www.uio.no/om/designmanual/images/1-2-3-logo-universitetet-i-oslo.jpg "UiO Logo")

# The N-Queens Puzzle
by Marius Aasan (mariuaas$(\alpha)$math$\cdot$uio$\cdot$no) - IN3050/4050 Group 3 - 08.02.2021 1015-1200

The [8-queens puzzle](https://en.wikipedia.org/wiki/Eight_queens_puzzle) is a combinatorial optimization problem where one tries to place 8 queens on a chessboard without any of the queens being in a position to capture one another. In principle, a candidate solution can be obtained by placing the queens randomly over the board. However, this would create a very large solution space. Instead, we represent the genotypes as permutations, such that each queen can occupy a single rank and file. This leaves only the diagonals to be checked. Let us solve this problem with a genetic algorithm and generalize to an $N \times N$ grid.

#### Note:
Some of the code in this notebook as to not crash with the mandatory assignment, but can be filled out as an exercise.

Firstly we define the 'magic' function to plot directly in the Notebook.
