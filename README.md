# Ludo Board Generator 🎲

A Python turtle graphics implementation that draws a complete Ludo game board with all the classic elements.

## Overview

This project uses Python's turtle graphics library to create a visual representation of a traditional Ludo board game. The board includes all four player zones (Red, Blue, Green, Yellow), the central home area, safe zones, and starting positions.

## Features

- **Complete Ludo Board Layout**: Full-sized board with proper dimensions
- **Four Player Zones**: Color-coded quadrants for Red, Blue, Green, and Yellow players
- **Home Paths**: Colored pathways leading to the center for each player
- **Safe Zones**: White squares in each corner with player token positions
- **Starting Circles**: Visual markers for initial token placement
- **Center Triangular Home**: Traditional pyramid-shaped home area

## Requirements

- Python 3.x
- turtle (included in Python standard library)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/ludo-board.git
cd ludo-board
```

2. No additional dependencies needed! The turtle module comes with Python.

## Usage

Simply run the Python script:

```bash
python ludo_board.py
```

The program will open a window and automatically draw the complete Ludo board.

## Board Components

- **Outer Border**: 450x450 unit square frame
- **Corner Quadrants**: 180x180 unit colored squares (Red, Blue, Green, Yellow)
- **Safe Zones**: 120x120 unit white squares with token circles
- **Home Paths**: Color-coded pathways with 6 squares leading to center
- **Center Area**: Triangular home zones for each player
- **Token Markers**: Colored circles indicating starting positions

## Customization

You can modify the following in the code:
- Board size by adjusting the forward distances
- Colors by changing the `fillcolor()` parameters
- Pen thickness via `t.pensize()`
- Drawing speed with `t.speed()`

## Code Structure

- `circle_place(x, y)`: Positions the turtle at specific coordinates
- `circle_redgreen()`: Draws token circles for Red and Blue players
- `circle_blueyellow()`: Draws token circles for Green and Yellow players
- Main drawing logic: Sequential construction of board elements

## Contributing

Feel free to fork this project and submit pull requests for any improvements:
- Add animation features
- Implement token movement
- Add dice rolling functionality
- Create a playable game interface

## License

This project is open source and available under the MIT License.

## Author

Created using Python turtle graphics

## Acknowledgments

- Inspired by the classic Ludo board game
- Built with Python's turtle graphics module

---

**Note**: Close the turtle graphics window to exit the program.
