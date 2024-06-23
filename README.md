HappyBird for Commodore 64

Welcome to HappyBird for the Commodore 64! This project is a nostalgic recreation of the classic Flappy Bird game, written in 6502 assembly language specifically for the C64 platform. Dive into the past with this retro gaming experience that combines modern gameplay with classic hardware.

Features

Classic Gameplay: Navigate the bird through a series of obstacles by controlling its jumps.
Smooth Animations: Simple yet effective graphics that capture the essence of the original Flappy Bird.
Sound Effects: Enjoy sound effects for jumps and collisions, adding to the immersive experience.
Scoring System: Keep track of your score as you successfully navigate through obstacles.
Game Over and Reset: Includes a start screen, game-over message, and the ability to restart the game.

Getting Started

Prerequisites

Commodore 64: The game is designed to run on original C64 hardware or a C64 emulator.
Assembler: You will need a 6502 assembler to compile the source code. Tools like Turbo Macro Pro or CBM Prg Studio are recommended.
Emulator: If you don't have access to C64 hardware, you can use an emulator like VICE.

Installation

Clone the Repository:

bash
Copy code
git clone https://github.com/KingHavok/happybird.git
cd happybird

Assemble the Source Code:
Use your preferred assembler to compile the happybird.asm source file.

Load and Run:

On real hardware: Transfer the compiled binary to a floppy disk or cartridge.

On an emulator: Load the compiled binary file into the emulator and run it.

Code Overview

The main components of the game include:

Initialization: Setting up the screen, loading graphics, and initializing game variables.
Main Game Loop: Handling user input, updating the game state, and rendering graphics.
Bird Movement: Logic for bird's movement and jump mechanics.
Obstacle Handling: Generating and moving obstacles with collision detection.
Sound Effects: Simple sound routines for jump and collision effects.
Scoring and Display: Keeping track of and displaying the player's score.
Game Over and Reset: Managing game-over conditions and restarting the game.

Contributing

Contributions are welcome! If you have ideas for improvements or have found bugs, feel free to open an issue or submit a pull request. Please ensure your code follows the project’s coding standards and is well-documented.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Original Flappy Bird: Inspired by the original Flappy Bird game developed by Dong Nguyen.
C64 Community: Thanks to the Commodore 64 community for their continuous support and resources.
