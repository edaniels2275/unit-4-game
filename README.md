# unit-4-game

1. The goal of the game is to get the current total to be exactly equal to the number that the user has 
to guess, which is randomly assigned between 19 and 120.

2. Each of the four crystals is assigned to an index in an array that generates four random numbers
between zero and twelve each time the game starts.

3. When the user clicks a crystal, the random value (between 0 and 12) that that crystal was assigned gets added to the user's total.

4. If the user's total exceeds the number to be guessed, the user loses and losses increases by 1.

5. If the user's total is exactly the same as the number to be guessed, the user wins and wins increases by 1.