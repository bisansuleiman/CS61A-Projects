# CS61A

## Project 1: Hog
Developed a simulator and multiple startegies for the game Hog.

In Hog, two players altenate trying to be the first to end a turn with at least 100 points. Every turn the player chooses a number between 0-10, and the sum of the dice outcomes will be the player's score.

Special rules:

- Sow Sad: If any of the dice outcomes is 1, the player's current score for that turn will be 1.
- Pig Tail: If a player chooses to roll 0 dice, their turn's score will be 2 * abs(tens - ones) + 1 points, where tens, ones are tens and ones digits of the opponent's score.
- Square Swine: If a player's resulting score is a perfect sqquare, then increase their score to the next higher perfect square.

## Project 2: Cats (Typing Speed Measuring Program, Inspired by typeracer)

Wrote a program that measures typing speed and implements autocorrect.

## Project 3: Ants VS SomeBees (Inspired by PopCap's Plants Vs. Zombies)

Created a tower defense game called Ants vs. SomeBees. Used an object-oriented programming paradigm, and understood, extended, and tested a large program.

The game consists of a series of turns, in each turn: 

- New bees can enter the ant colony. New ants are placed to defend their colony.
- Bees either move to the end of tunnel, or try to sting ants in their way.
- Ants perform different actions depending on their types, such as:
    - HarvesterAnt: has a food_cost of 0
    - ThrowerAnt: throws a leaf at the nearest bee to cause it damage 
    - FireAnt: does damage all bees in its place when it recieves damage
    - HungryAnt: does damage to a bee by eating it whole
The game ends either when a bee reaches the end of a tunnel (you win), or the bees destroy a QueenAnt (you lose).




