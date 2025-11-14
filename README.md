Bordered Snake Game in x86 Assembly

A classic Snake game implemented entirely in x86 Assembly (MASM) using the Irvine32 library. This project runs in a standard console window and was developed as a practical application of low-level programming and computer organization concepts.

Project Authors

Masoom Khan (24k0001)

Dev Kumar (24k0028)

Sagbatullah

🎮 Game Demo (ASCII)

The game runs entirely in the console, using ASCII characters to represent the game elements.

✨ Features

Classic Gameplay: Control a snake to eat food and grow longer.

Enclosed Border: The game is played within a bordered area (#). Hitting the border ends the game.

Food Generation: Food (@) randomly appears on the screen after the previous piece is eaten.

Score Tracking: The score is displayed at the top of the screen and increases by 10 for each piece of food eaten.

Snake Growth: The snake (O) grows by one segment for each piece of food eaten.

Collision Detection: The game ends if the snake hits the border or its own body.

Responsive Controls: Uses arrow keys for movement and prevents illegal 180-degree turns.

🛠️ Built With

Language: x86 Assembly Language (MASM)

Library: Irvine32 Library

Environment: Visual Studio 2022 (with MASM integration)

🚀 Getting Started

To run this project, you must have a Windows environment configured for MASM and the Irvine32 library.

Prerequisites

Visual Studio: 2019 or 2022 is recommended.

MASM: The MASM assembler (comes with Visual Studio's C++ workloads).

Irvine32 Library: You must have the Irvine32 library set up and linked in your project.

Installation & Running

Clone the repository:

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)


Set up the Irvine32 Project:

Open Visual Studio.

Create a new Empty Project.

Follow the instructions from Kip Irvine's "Assembly Language for x86 Processors" textbook to link the Irvine32 library and set up the project properties for MASM.
Similarly you can also do this via following the method provided in Coal Lab 1 by Sir Jahanzaib on GCR.
 
Add the Code:

Add the snake_game.asm (or your file's name) to the project's "Source Files".

Build and Run:

Build the solution (F7).

Run the project without debugging (Ctrl + F5).

🕹️ How to Play

Start: The game begins immediately.

Movement: Use the Arrow Keys (Up, Down, Left, Right) to change the snake's direction.

Objective: Eat the food (@) to score points and grow longer.

Game Over: The game ends if you run into the border (#) or into your own body (O).

Exit: After a "Game Over", press any key to close the console.

Acknowledgements

This project was inspired by the classic Snake game.

Special thanks to Kip Irvine for the invaluable Irvine32 library, which makes console I/O and screen manipulation in Assembly accessible.
