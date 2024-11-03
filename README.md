<p align="left">
    <img width="150px" src="https://github.com/thoth-tech/.github/blob/main/images/splashkit.png"/>
</p>

# Below The Surface

**Below The Surface** is an action-adventure game developed using the SplashKit SDK. Dive deep into a thrilling, underwater world filled with challenges, enemies, and interactive elements. Designed for compatibility with the **Arcade Machine**, this game provides an engaging experience for one or two players.

## Overview

In **Below The Surface**, players navigate through underwater terrain, overcome obstacles, and engage in combat with various creatures. The game is designed to challenge both solo players and teams, with optimized controls for the Arcade Machine to ensure smooth gameplay.

## How to Install

Follow these steps to download, build, and run **Below The Surface** on your computer:

### Step 1: Install SplashKit

Ensure you have the SplashKit SDK installed on your computer. You can download it from the [SplashKit website](https://www.splashkit.io/installation).

### Step 2: Clone the Repository

Open your terminal and clone the arcade-games repository, which includes **Below The Surface**:

```bash
git clone https://github.com/thoth-tech/arcade-games
```

### Step 3: Navigate to the Game Directory

Move into the game’s directory within the repository:

```bash
cd arcade-games/games/BelowTheSurface
```

### Step 4: Build the Game

Compile the game using SKM (SplashKit Manager) with the following command:

```bash
skm g++ program.cpp -o game
```

For optimized performance, you can use the `-O3` flag for an optimized build:

```bash
skm g++ -O3 program.cpp -o game
```

### Step 5: Play the Game

Run the game by entering the following command:

```bash
./game
```

## Controls

The controls for **Below The Surface** have been adapted to work seamlessly with the Arcade Machine setup. Here are the mappings for each player:

### Player 1

| Input                | Action             |
|----------------------|--------------------|
| Up Arrow / Left Alt  | Jump               |
| Left Arrow           | Move Left          |
| Right Arrow          | Move Right         |
| Down Arrow           | Crouch             |
| Left Ctrl            | Attack/Interact    |

### Player 2

| Input                | Action             |
|----------------------|--------------------|
| R Key / S Key        | Jump               |
| D Key                | Move Left          |
| G Key                | Move Right         |
| F Key                | Crouch             |
| A Key                | Attack/Interact    |

### Other Controls

| Input               | Action             |
|---------------------|--------------------|
| Enter / P Key       | Pause              |
| Enter / Left Ctrl   | Selection          |

## Game Features

- **Multiplayer Support**: Play solo or team up with a friend in a two-player mode, with distinct control setups for each player.
- **Interactive Environment**: Explore underwater environments with obstacles, hidden treasures, and interactive objects.
- **Combat and Interactions**: Engage with various underwater creatures and interact with the environment to uncover new areas and items.

## Optimizations & Modifications

To ensure the game runs smoothly on the Arcade Machine, several adjustments and optimizations have been made:

- **Optimized Build**: Use `skm g++ -O3 program.cpp -o game` for an optimized version, which improves performance by reducing execution time and memory usage.
- **Resolution Adjustments**: The game resolution and asset quality have been adjusted for compatibility with the Arcade Machine, ensuring smoother gameplay and faster load times.
- **Control Customization**: Controls have been reconfigured to align with the Arcade Machine’s setup, making gameplay intuitive for both single and dual-player modes.

## Contributing

We welcome contributions from the community to enhance and expand **Below The Surface**. If you have ideas for new features, improvements, or optimizations, feel free to submit a pull request or open an issue on the repository.
