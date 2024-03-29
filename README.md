# CS 2.2 Graph Modeling Project - League of Legends Team Fight Tactics Item System

![TFT Items](imgs/item-guide.png)

## Project Description
I will be modeling a Graph ADT (Abstract Data Structure) to take in data of all the items in TFT(Team Fight Tactics). With it, I will be introducing a set of problems and solve them using graph theory in python. The input data will be small but the project will be able to scope and scale to a real world problem.

## Project Problems
- The most versatile item in the game.
- Based on an item you have, outputs which campions can you give it to.
- Which champion has an item that is the least shared recommendation to any other champion.

# Usage
## Run
```
python3 main.py graph-data.txt
```

## Input (example)
```
Which Item are you trying to pair to a Champion? Dragon's Claw
```

## Output (example)
```
Most Versatile Item: (15, 'Morellonomicon')
Least Shared Item: (1, 'Redemption')

Which Item are you trying to pair to a Champion? Dragon's Claw
Champions that can use this item are: ['Darius', 'Garen', 'Braum', 'Kassadin', 'Shen', 'Aatrox', 'Poppy', 'Akali', 'Sejuani']
```