# Python Snake Game

A classic Snake Game implemented in Python using the Pygame library. This game features a simple interface and smooth controls.

## Features

- Control snake movement with arrow keys
- Real-time score display
- Collision detection (game resets when snake hits itself)
- Wall wrapping (snake can pass through screen boundaries)
- Random food generation
- Food collection system (snake grows longer and score increases)

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Make sure you have Python 3.x installed
2. Install Pygame:

```
pip install pygame
```

## How to Run

After downloading `snake_game.py`, run in terminal:
```
python snake_game.py
```

## Controls

- ↑ (Up Arrow): Move Up
- ↓ (Down Arrow): Move Down
- ← (Left Arrow): Move Left
- → (Right Arrow): Move Right

## Game Rules

1. Control the snake to collect red food
2. Each food collected adds 1 point and increases snake length
3. Game resets if snake collides with itself
4. Snake can wrap around screen edges

## Customization

You can customize the game by modifying these parameters in the code:

- `WINDOW_WIDTH` and `WINDOW_HEIGHT`: Adjust window size
- `GRID_SIZE`: Change grid size
- `clock.tick(10)`: Modify game speed (higher value = faster)

## Contributing

Issues and Pull Requests are welcome to improve the game!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Junhua Bai

## Acknowledgments

Thanks to the Pygame community for providing an excellent game development framework.