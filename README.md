# PigBalanceGame
A simple 2D arcade game inspired by agricultural field. Will be related on some country animals who don't know where to go ;-D Player must keep the board balanced!

# The elements on the stage

- a balance board where the animals will be dropped
  - length will be random between the length limits
  - a balance limit where the board will fall out (too many animals at the one side of the board)
  - stoppers at the both corners where the animals will be turn around
- zero or some max number of pigs/cows/sheeps/chickens...
  - random animal size between the limits
  - random animal speed (could be correlated on the size)
  - random animal weight between the limits
  - random animal outfit :-)
- *the gravity properties here*

# The basic scenario

1. random amount of a differend animals are dropped to the board
2. animals will be walking on the board instantly after landing (left or right, obviously :-)). Moving speed depends on animal properties (weight etc.)
3. player tries to hold the board balanced by dragging and dropping the animals to the better position.
4. game ends when the balance board falls out

# Difficulty level properties

1. animal properties
2. balance board size and balance limit
3. gravity
