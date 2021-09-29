# CMake Tutorial
## Prerequisite
Install on Ubuntu
```
sudo apt-get update
sudo apt-get install cmake
```
## Required Files Before Build
```
.
├── CMakeLists.txt
└── main.cpp

0 directories, 2 files
```

## Build Procedures
1. prepare [CMakeLists.txt](CMakeLists.txt) and [source cpp file](main.cpp)
2. <code>mkdir build</code>, make "build" directory in root project 
3. run <code>cmake ..</code> in directory "build" and files will generate inside build
4. run <code>make</code> in directory "build" to compile and link related files, [executable file](main.o)(specified in [CMakeLists.txt](CMakeLists.txt)) will appear in directory "build"
## Reference
[Official Document](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)<br>
[Chinese Tutorial](https://zh.wikibooks.org/wiki/CMake_%E5%85%A5%E9%96%80)