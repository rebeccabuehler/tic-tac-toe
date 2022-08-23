# tic-tac-toe

## Description
Creating a react app of the game tic tac toe. There is the parent component the board, and the child component the square. The state od the square will be updated once a player clicks on it. There are two players and they will be X or O. It will flip back and forth once a square is clicked on for the spot. There is an array with all the possible combos for a win and there is a function that checks if X or O fulfill one of those combos. If they do they will be announced the winner of the game. 

## Future Iprovements

features: 

One feature that I would like to change is the styling of the game, make it more pleasing to the eye, and more fun for the user. Another feature I would like to implement is where you make it more game like. Once a winner is declared the board would be disabled, and two buttons would appear to start a new game. One thing I noticed was that even after the game is finished you can still click anywhere even if a square had been filled, so fixing that and making it more game like would be another feature I hope to implement.

How I plan to implement these features:

For the styling just changing it from the html file and adding better colors and maybe some cool bootstrap features.

I think for the second one, adding a better state for the square to determine if it is marked or not and then going from there. Once the winner is announced adding a disabled tag with another button to start the game over, and it would just re-render.