# Archery Game 

## General Information
1.The game area coordinates are -10 to 10 grid in x and y.

## Game Initialization
1. The first archer (A) represents the user. User enters the coordinates of his/her character. The program should control the validity of the location.
2. The second and third archers are placed in random locations in the game area. The archers should be shown on the coordinate plane.
3. Each archer has different health state (60, 80 or 100), initiated randomly at the beginning of the game.

## Game Playing Rules
1. There are two rounds of attacks in each game. Each attack contains only 2 archers. In the first round, the closest two archers shoot at each other. After that, the winner and the other archer shoot at each other.   
2. An arrow can travel max. 15 units. Otherwise, there is no attack.
3. Each attack decreases 25 health points from the winner. The health point of the loser becomes zero.  
