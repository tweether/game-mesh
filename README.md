
# Game Mesh [![build](https://github.com/tweether/game-mesh/workflows/build/badge.svg)](https://github.com/tweether/game-mesh/actions?query=workflow%3Abuild) [![Build Status](https://travis-ci.com/tweether/game-mesh.svg?branch=master)](https://travis-ci.com/tweether/game-mesh) [![codecov](https://codecov.io/gh/tweether/game-mesh/branch/master/graph/badge.svg)](https://codecov.io/gh/tweether/game-mesh) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/14e8cb11e6cb4b8897e8939cce256dac)](https://www.codacy.com/gh/tweether/game-mesh?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=tweether/game-mesh&amp;utm_campaign=Badge_Grade) [![Documentation Status](https://readthedocs.org/projects/game-mesh/badge/?version=latest)](https://game-mesh.readthedocs.io/en/latest/?badge=latest)

!!! This project is in a rapid iteration period, please do not use. !!!

## Usage

### Building

Build by making a build directory (i.e. `build/`), run cmake in that dir, and then use make to build the desired target.

```shell
$ mkdir build && cd build
$ cmake ..
$ cmake --build .
```

## Learning

GameMesh has the most extensive and thorough [documentation](https://game-mesh.readthedocs.io/en/latest/), making it a breeze to get started with the framework.

#### Built-in server

A quick documention to install [mkdocs](https://www.mkdocs.org/#installation).

```shell
$ mkdocs serve
```

Open up `http://127.0.0.1:8000/` in your browser, and you'll see the document home page being displayed.

## Requirements

**Required:**
- [conan](https://conan.io/) (>= 1.0)
- [cmake](https://cmake.org/) (>= 3.8)
- [gcc](https://gcc.gnu.org/) (>= 7.5)

**Options:**
- [cpplint](https://github.com/cpplint/cpplint)
- [cppcheck](http://cppcheck.sourceforge.net/)
- [lcov](http://ltp.sourceforge.net/coverage/lcov.php)

