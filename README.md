# Connect-4 Game with AI Agent
## Project Overview
This repository contains the implementation of a Connect-4 game with an AI agent using the Minimax algorithm and Alpha-Beta pruning. It showcases AI techniques in game theory by building an agent that can play against a computer, another AI, or a human.

## Features
### Minimax Algorithm: 
The AI agent uses the Minimax algorithm to determine optimal moves for the Connect-4 game.
### Alpha-Beta Pruning: 
Optimizes the Minimax algorithm by reducing the number of nodes evaluated.
### Game Modes:
#### AI Agent vs AI Agent: Two AI agents compete using the Minimax algorithm.
#### AI Agent vs Computer (Random Choices): The AI agent plays against a random-move computer opponent.
#### AI Agent vs Human: A human player competes against the AI agent.
### Difficulty Levels:
Easy, Medium, Hard: The difficulty level of the AI can be selected.
### Python-based Implementation: 
The project is implemented in Python for ease of use and development.

## Algorithms Used
### Minimax Algorithm
The AI evaluates all possible game states and chooses the move that maximizes its advantage while minimizing the advantage of its opponent.

### Alpha-Beta Pruning
Alpha-Beta pruning enhances Minimax by "pruning" branches in the game tree that do not need to be evaluated, improving the efficiency of the algorithm.
