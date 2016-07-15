# Library Structure

Within the `ochre` folder, the library is organized as follows:

* [`backend/`](#backend): functionality which users of ochre should not need to access. These generally are layers of abstraction between underlying libraries (such as OpenGL and SDL) and the ochre API.
* [`game/`](#game): the `Game` class definition and any user-defined functionality, as well as testing functionality in the sample `Game.h` and `Game.cpp` files. In general, actual ochre library functionality should not go here.
* [`include/`](#include): header files for functionality which is part of the ochre API, and which the user can and should interact with. All underlying library functions and types should be abstracted away from API-interactable functionality here (return and input types of public members).
* [`lib/`](#lib): cpp files defining the declarations given in `include/`. No new functionality should be defined here.
* [`src/`](#src): files which include a `main()` function. Most importantly, contains `main.cpp`, which runs all the code the user defined in `game/`. It should not be necessary to modify `main.cpp`.

## Backend

## Game

## Include

## Lib

## Src


