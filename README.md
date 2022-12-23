# Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [Makefile Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools)
- [SDL2-devel-latest-mingw.tar.gz](https://github.com/libsdl-org/SDL/releases)
- A gzip and tar extracter, e.g. [7-zip](https://www.7-zip.org/)

# Setup

1. Extract the SDL dev files.
2. For 64-Bit versions, navigate to the `x86_64-w64-mingw32` folder, for 32-Bit versions to the `i686-w64-mingw32` folder.
3. In your project directory, create a new folder `src`.
4. Copy `include` and `lib` to the `src` directory.
5. Copy `bin/SDL2.dll` to your project directory.
6. To compile, open a new terminal in your project directory and type in `mingw32-make`.

# Source

[https://youtu.be/jUZZC9UXyFs](https://youtu.be/jUZZC9UXyFs)
