# CS61A

## Hog
Developed a simular and multiple startegies for the game Hog.

In Hog, two players altenate trying to be the first to end a turn with at least 100 points. Every turn the player chooses a number between 0-10, and the sum of the dice outcomes will be the player's score.
Special rules:
- Sow Sad: If any of the dice outcomes is 1, the player's current score for that turn will be 1.
- Pig Tail: If a player chooses to roll 0 dice, their turn's score will be 2 * abs(tens - ones) + 1 points, where tens, ones are tens and ones digits of the opponent's score.
- Square Swine: If a player's resulting score is a perfect sqquare, then increase their score to the next higher perfect square.