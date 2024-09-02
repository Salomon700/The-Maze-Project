# The-Maze-Project

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 24.04 - gcc

#Prerequisites

Run install_SDL2.sh prior to install SDL2

#compilation

gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;

#usage
- Execute ./maze
- Use up and down arrow keys to move forward and backward
- Use right and left arrow keys to turn the camera around
