# POSTAL WASM

a port of POSTAL 1 to WebAssembly using Emscripten.

## Building:

- Download POSTAL 1 from Steam
- View the game files
- Copy `res`, `title`, and `POSTAL.INI` to the repo
- Run `embuilder build sdl2` to install the Emscripten port of SDL2
- Run `emmake make` in the respository
- The resulting build will be stored in the web folder