
# Flappy Bird Game App (Java)

This is a simple implementation of the **Flappy Bird** game using **Java Swing**. The game features basic mechanics where the player controls a bird that must navigate through pipes by jumping. The objective is to keep the bird in the air and achieve the highest possible score without colliding with obstacles.

## Features

- **Bird Control**: The bird falls due to gravity, and the player can make it jump by pressing the spacebar.
- **Dynamic Pipes**: Pipes appear at random heights and move from right to left.
- **Score System**: The player earns points by passing through the gaps between pipes.
- **Game Over**: The game ends when the bird collides with a pipe or falls to the ground.

## Requirements

- Java 8 or higher is required to run the game.
- The following images should be available in the project directory:
  - `flappybirdbg.png` (background image)
  - `flappybird.png` (bird image)
  - `toppipe.png` (top pipe image)
  - `bottompipe.png` (bottom pipe image)

## How to Run

1. **Compile the code**: 
   Ensure that you have the `FlappyBird.java` and `App.java` files. Compile the files using the following command:
   ```bash
   javac FlappyBird.java App.java
   ```

2. **Run the game**: 
   Execute the program using the following command:
   ```bash
   java App
   ```

Enjoy the game!

