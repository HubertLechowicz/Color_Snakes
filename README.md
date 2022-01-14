# Color_Snakes

### Computer Systems Modelling Project 3  "Multiagent AI"


## Introduction:

Color_Snakes is a remake of the original Tron light cycles game in python. In Color_Snakes your goal
is to survive the longest as you travel at a constant speed leaving a trail behind you.
If you crash into your own trail, your opponent's trail or a wall you will instantly lose.
This version of the game implements multiple game modes including 1 Red bot vs 1 Green bot, 1 Red bot vs 2 Green bots
games and 2 Red bots vs 2 Green bots games. The game also includes win/lose stats for each game mode.

##### There are always 2 AI

## Installation instructions:

After Cloning or downloading this repo, with pygame already installed use a terminal or command prompt to navigate to the main directory of this project.
Then type “python3 Color_Snakes.py” to start the game. Use the arrow keys to navigate the main menu.



## A.I. Explanation:

The AI for Color_Snakes is fairly simple. We have two AIs, one random AI and one that considers 'controlled territory'
(default). The random AI will for every tick simply have a 10% chance to chose a new direction. The territory
based AI is slightly more sophisticated and calculates the total number of reachable squares that a player can reach
before all other players for a given direction. For every tick, the territory based AI will consider all possible moves
that it can make assuming the opponent picks a random direction for the next move. The direction which maximizes the
amount of territory is then selected for the next move.


## Acknowledgments:

- This project was inspired by minigame by eyesniper2 and nwlieb

## Authors:
- [HubertLechowicz](https://github.com/HubertLechowicz)

