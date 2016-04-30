# caveGeneration
Module to randomly generate "caves" on a 2D plane

HOW TO USE

set a list variable to start(resolution)

EXAMPLE

resolution = 32
listVariable = []
listVariable = start(resolution)

listVariable will be a list of lists, containing values of 0 or 1 (0 to 9 in the color version)
listVariable is formatted in X,Y coordinates. ex. listVariable[x][y] will be 0 or 1 (0 to 9 in the color version)

Funky stuff happens when the resolution is too low, I wouldn't recommend having a resolution under 20

This program uses random.randint() to generate branches, meaning it is possible, but extrememly unlikely to reach maximum recursion depth with a high enough resolution.
