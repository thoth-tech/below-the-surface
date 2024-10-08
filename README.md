# Below The Surface

1. Requires a [SplashKit installation](https://splashkit.io/installation/).
2. Build using `skm clang++ *.cpp -o below-the-surface` while in the project folder.
3. Run using `./below-the-surface` while in the project folder.

_See also: usage documentation for [SplashKit](https://splashkit.io/guides/using-splashkit/0-overview/) and [skm](https://github.com/splashkit/skm/blob/master/README.MD)._

## Technical overview

- **Language:** C++
- **Current scope:** Large
- **Code quality:** Poor
- **Gameplay implementation:** Complete

## Gameplay overview

A puzzle-platformer supporting 1-2 players. Players have to redirect the flow of water through pipes while avoiding or eliminating enemies in order to reach the portal at the end of each level.

### Player 1 Controls

| Action        | Key                  |
|---------------|----------------------|
| Move Left     | Left arrow           |
| Move Right    | Right arrow          |
| Jump / Climb  | Up arrow / Right ALT |
| Crouch        | Down arrow           |
| Use/Attack    | Right CTRL           |
| Dance (both)  | Z                    |

### Player 2 Controls

| Action        | Key                  |
|---------------|----------------------|
| Move Left     | D                    |
| Move Right    | G                    |
| Jump / Climb  | R / Left ALT         |
| Crouch        | F                    |
| Use/Attack    | Left CTRL            |
| Dance (both)  | Z                    |

## Other

- This game has an associated GUI level editor: [Splashkit-LevelEditor](https://github.com/thoth-tech/Splashkit-LevelEditor).
- Some miscellaneous documentation from the original authors is in `/docs/`, alongside additional documentation related to level editing.
- Relevant resources to use the 3rd-party Tiled level editor are in `/levels/tiled/`.
- The game was originally designed to run at a resolution of 1600x896, but this was lowered to 800x446 for performance reasons on the arcade machines. The change has several implications for gameplay, level design, and screen layout.
- [Morgaine Barter](https://github.com/MorgaineBarter) has offered to be a point of contact for future students who have need to get in touch from someone on the original team. She can be contacted via e.g., MS Teams via her staff account (not her student account).

## Screenshots

![](/documentation/screenshot-01.png)

![](/documentation/screenshot-02.png)

## Credits

Originally created by 2022-T2 team:

- Morgaine Barter
- Daniel Agbay
- Lily Lan
- Robert Osborne
- Jiahao Zheng
- Roy Chen
- Lachlan Morgan
