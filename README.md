# Tuple Out Dice Game

## Overview
"Tuple Out" is a simple dice game where players roll dice to score points. The goal is to be the first to reach a target score (default: 50 points) without "tupling out."

## Rules
1. Players take turns rolling three dice.
2. If all three dice show the same number, the player **"tuples out"** and scores **0 points** for that turn.
3. If two dice match, they are **fixed** and cannot be re-rolled.
4. Players can continue re-rolling any **unfixed dice** until they choose to stop or tuple out.
5. When a player stops, they score the **sum of the three dice**.

## Features
- Multiplayer support.
- Dynamic score display after each turn.
- Automatic detection of winners.
- Configurable target score.

## How to Run
1. Ensure you have Python installed on your system.
2. Save the game code in a file named `tuple_out_game.py` in the same folder as this README.
3. Run the game from the terminal using:
   ```bash
   python tuple_out_game.py
