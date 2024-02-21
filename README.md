# TicTacToe Game

A classic TicTacToe game that supports multiplayer gameplay as well as playing against a computer AI. Players take turns placing their marks (crosses and circles) on a 3x3 grid, aiming to align three of their marks vertically, horizontally, or diagonally.

## Features

- Multiplayer gameplay.
- Play against a sophisticated AI.
- Simple and intuitive GUI.


## Screenshots

![Game Start](https://github.com/beyuneek/Tic--tac--toe-Game-/assets/113319598/7d8e0ec1-453a-4516-b33a-d985214d128a)
*The game board at the start.*

![Gameplay](https://github.com/beyuneek/Tic--tac--toe-Game-/assets/113319598/7903fd2d-51fb-4a8a-997a-3f8e5f4d20d3)
*Gameplay with some moves made.*


## How It Works

### The `Block` Class

The `Block` class represents each cell in the TicTacToe grid. It holds the value (`None`, `"x"`, or `"o"`) and its position.

```python
class Block():
    def __init__(self, i, j):
        self.value = None
        self.pos = (i, j)

    def setValue(self, value):
        self.value = value
