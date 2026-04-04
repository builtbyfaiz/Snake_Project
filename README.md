## Snake-Game-Cpp-Raylib

A simple Snake game built with C++ and Raylib 5.5.
Includes score tracking, high score persistence, and WASD controls.

## Status

Basic playable version (in development / extendable).

## Controls

| Input         | Action                              |
| ------------- | ----------------------------------- |
| W / A / S / D | Move snake up / left / down / right |

## Features

* Real-time snake movement
* Score system
* High score tracking

## Building

### Prerequisites

* MinGW-W64 or Visual Studio 2022
* Git

---

### Windows (MinGW)

```
build-MinGW-W64.bat
make
```

---

### Windows (Visual Studio)

```
build-VisualStudio2022.bat
```

Then open the generated `.sln` file.

---

### Linux

```
cd build
./premake5 gmake
cd ..
make
```

---

### MacOS

```
cd build
./premake5.osx gmake
cd ..
make
```

---

## Output

Built binary will be in `bin/`.
