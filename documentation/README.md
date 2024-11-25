# Below the Surface Documentation

Welcome to the development documentation for **Below the Surface**! This project is a collaborative effort to create an exceptional game for the **Arcade Machine**. This guide provides an overview of the core files, level management, and setup instructions to help you contribute effectively to the game.

---

## Project Structure

### Header Files

Below are the key header files you’ll encounter while developing **Below the Surface**:

- **`player.h`**: Defines the `Player` class, along with its attributes, functions, and states.
- **`map.h`**: Manages game content display, including backgrounds and map elements.
- **`level.h`**: Responsible for scene management, such as level transitions and collision checks.
- **`enemy.h`**: Contains the enemy classes with their attributes and behaviors.
- **`behaviour.h`**: Manages AI behavior for different enemy types.
- **`block.h`**: Defines the behavior of individual blocks in the game.
- **`camera.h`**: Tracks the player’s movements across the level.
- **`cellsheet.h`**: Defines the cell structure used for game elements.
- **`collision.h`**: Handles collision detection and responses throughout the game.
- **`get_level.h`**: Loads and renders a level on the screen.
- **`hud.h`**: Manages the player’s HUD (Heads-Up Display) for displaying health, score, etc.
- **`screen.h`**: Handles rendering of the game on the screen.
- **`testing.h`**: Provides functions for testing various components during development.

---

## Level Management

### Level Text Files

The **`levels`** folder contains text files that represent different game levels. Each file uses block IDs to define the layout of the levels, which can be created or edited in the **Level Editor**.

**Important**: **Do not manually change the values inside these text files** to avoid unintended modifications. Use the Level Editor to create or edit levels instead.

### Testing a Level

To test a custom level, run the following command in the terminal:

#### Format

```bash
./test -l {number of layers} levels/{layer0.txt} levels/{layer1.txt} {level name}
```

#### Example

```bash
./test -l 2 levels/layer0.txt levels/layer1.txt test
```

### Loading a Level in the Level Editor

To edit an existing level, load it in the Level Editor with this command:

#### Format

```bash
./test -load {number of layers} levels/{layer0.txt} levels/{layer1.txt}
```

#### Example

```bash
./test -load 1 levels/layer0.txt
```

Ensure you have the latest versions of both the game and the Level Editor for compatibility.

---

## Using the File Explorer

To manage files and folders, use the file explorer accessible from the left corner of the navigation bar in the development environment:

- **Create New File**: Click **New File** to add a new file within the current directory.
- **Create New Folder**: Click **New Folder** to organize files within folders.

---

## Compiling and Running the Game

### Compiling the Game

To compile the game, use the following command in your terminal. Ensure your terminal is in the correct directory where the repository is located.

```bash
skm clang++ -o test program.cpp
```

### Running the Game

Once compiled, you can run the game with the command:

```bash
./test
```

### Optimized Compilation

For an optimized build, use the `-O3` flag to improve performance:

```bash
skm clang++ -O3 -o test program.cpp
```

---

This documentation should provide all the information you need to work on **Below the Surface**, from managing files and levels to compiling and running the game. If you have further questions or encounter issues, please refer to the README in the main repository or reach out to the project maintainers.
