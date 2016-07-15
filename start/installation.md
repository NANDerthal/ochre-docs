# Installation

## Dependencies

External dependencies are listed below, and the installation instructions for these can be found on the respective libraries' websites. Note that if your machine's version of OpenGL is insufficient, you can usually solve this by updating your graphics drivers and/or installing [Mesa](http://www.mesa3d.org/).

* OpenGL 3.3 or higher
* [SDL2](www.libsdl.org)
* [GLEW 1.1](http://glew.sourceforge.net)
* [SOIL](http://www.lonesock.net/soil.html)

## Downloading ochre

To download the source, go to the location in which you want to save your game and clone the repo using [git](https://git-scm.com/). (The git repository can be viewed on GitHub [here](https://github.com/NANDerthal/ochre).)

```bash
git clone https://github.com/NANDerthal/ochre.git
```
The ochre engine does not have a GUI and is intended to be used in its source form, so no further installation is required.

To test that your environment is configured correctly with the dependencies listed above, go to the ochre folder and make the test as follows:

```bash
cd ochre/
make
./main.out -t
```

If all went well, you should see a window with nothing in it. It will close itself after two seconds.

[//]: # (TODO: update expected test outcome and add screenshot)

