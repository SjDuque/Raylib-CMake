# Raylib-CMake-Template

A simple template for using Raylib on any platform with CMake. 

*Although I recommend installing Raylib through a package manager, this project doesn't require you to have raylib installed at all. In the event that CMake cannot find Raylib, it'll automatically install everything you need into the project's build directory.*

## Downloading

You can either use `git`, `curl`, or `wget` to download the repository.

(Recommended) Using git:

```
git clone --depth=1 https://github.com/SjDuque/Raylib-CMake-Template
rm -rf Raylib-CMake-Template/.git
```

Using curl:

```
curl -L https://github.com/SjDuque/Raylib-CMake-Template/archive/main.zip -o raylib_template.zip
unzip raylib_template.zip
rm -rf raylib_template.zip
```

Using wget:

```
wget https://github.com/SjDuque/Raylib-CMake-Template/archive/main.zip -O raylib_template.zip
unzip raylib_template.zip
rm -rf raylib_template.zip
```

## Building

```
cd Raylib-CMake-Template
mkdir build
cd build
cmake ..
cmake --build .
```

## Acknowledgement Stuff

The main.cpp file is from an example from www.raylib.com
The CMakeLists.txt is modified from https://github.com/raysan5/raylib/blob/master/projects/CMake/CMakeLists.txt

FEEL FREE TO DELETE THE README and LICENSE. IT'S ONLY THERE AS A PLACE HOLDER. I DO NOT CARE ABOUT ANY MODIFICATION OR COPYING OF THIS REPOSITORY.
