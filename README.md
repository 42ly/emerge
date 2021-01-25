# Morph (abandoned until I have time to learn complex analysis more completely)
Currently all that's implemented is the animation of a julia fractal and the static generation of a mandelbrot fractal. The animation of the julia fractal shows an occurence of biomorphic mitosis. Meaning that the animation of this julia fractal resembles/models cellular mitosis when iterated over a constant on the julia set function. The colors are randomly selected.


## Dependencies:
SDL2, SDL2_image, g++


Ubuntu 20.04.1: `sudo apt-get install libsdl2-dev libsdl2-image-dev g++ git && git clone https://github.com/foogolplex/Morph`


## Compile:
`g++ -o main main.cpp emerge.cpp -lSDL2 -lSDL2_image`


![Alt text](morph_screenshot.png?raw=true)
