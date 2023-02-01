# Part 1

## Video Demo



## Minimum Requirements

### Completed

    game board
    alien spawn
    multiple zombie random spawn
    game setting(row, column and number of zombie)
    display help
    quit option

### To Do
    
1. attributes
2. alien's movement(game control)
3. game objects(health packet, pod, rock, and arrow)
4. alien interaction with other objects
5. zombie's movement
6. alien attacking zombie
7. game flow
8. alien need to kill zombie to win(condition to win)
9. saving and loading game file

## Additional Features

## Contributions

### Kasyfi

1. game setting
2. multiple zombie random spawn
3. command function - display help and quit

### Yuvan

1. generating game board
2. game settings for number of rows and columns
3. attribute display

### Arnalin

1. Alien class
2. Board class

## Problems Encountered & Solutions

1. Using the If Else statement will end the program when an invalid input was given by the user at the number of rows and columns. So, while statement was used instead.
2. zombie only spawn with "z" symbol, not 1, 2, 3. Changed int i to char but didn't work. Fixed it by adding array.
3. count wasnt declared in test1_1 function. So, we put int count = 0. But then, zombie not spawning. So, it changed to int count = 1.
