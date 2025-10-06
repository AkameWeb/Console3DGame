# Console 3D Game

A simple 3D console-based game written in C# that uses ray casting to render a 3D environment in the console window.

## Description

This project is a basic implementation of a 3D game that runs in the console. It features:
- A 3D world rendered using ASCII characters
- Player movement (forward, backward, and rotation)
- Collision detection with walls
- A simple map defined by a string of characters

## Requirements

- .NET Framework (the code is written in C# and should work with .NET Core or .NET 5/6 as well)
- Windows OS (if using `SoundPlayer` for audio, which is currently commented out)

## How to Run

1. Ensure you have the .NET SDK installed.
2. Clone the repository or copy the code into a new C# console application project.
3. Compile and run the program.

## Controls

- `W` - Move forward
- `S` - Move backward
- `A` - Rotate left
- `D` - Rotate right
- `Esc` - Exit the game

## Gameplay

- When you start the game, you will be presented with a menu. Press `Enter` to start the game or `Esc` to exit.
- The game world is a maze made of walls (`#`) and empty spaces (`.`).
- The player is represented by a point in the map and can move and rotate.
- The 3D view is rendered in the console using different shades of characters to represent walls at different distances.

## Code Structure

- The main game loop is in the `Start` method.
- The ray casting algorithm is used to determine the distance to walls and render them accordingly.
- The map is stored as a string and is 32x32 in size.

## Current Version: 0.1

### Features in v0.1:
- Basic ray casting rendering
- Player movement and rotation
- Collision detection with walls
- Simple menu and story text

### Known Issues and Limitations
- The game does not have textures, only shaded walls.
- The map is hardcoded.
- The performance might be limited due to the console rendering.

## Future Improvements

- Improve the rendering performance.
- Add more features like enemies, items, and objectives.
- Implement a more advanced sound system.
- Allow for different maps.

## License

This project is open source and available under the [MIT License](LICENSE).
