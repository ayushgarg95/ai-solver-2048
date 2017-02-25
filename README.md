# AI-Solver-2048
This program uses expectimax optimization as the basic AI algorithm, along with a highly-efficient 64-bit representation of the playing board. This allows it to search upwards of 10 million moves per second. The AI performs a maximize operation over all possible moves, followed by calculation of expectation values over all possible tile spawns. Additionally, it uses heuristics like bonuses for empty squares and for placing large values near edges and corners.

# To run in Linux:

$ gcc 2048.cpp
$ ./a.out

# To run on Windows:

A C++ compiler is required. Install Codeblocks IDE or Microsoft Visual C++ and run in the respective IDE.
