This is a skeleton project of a simple C# hello world application together with CMake modules to carry on the the build and NuGet package management. This project features a library consumed by the main application.

## Dependencies

### CMake

The last release can be found in https://cmake.org/

### Mono

Follow the instructions from the official website [Install Mono on Linux](http://www.mono-project.com/docs/getting-started/install/linux/).

### NuGet

Download the latest Windows x86 Commandline version from http://dist.nuget.org/index.html and save it in the root directory of this project.


## Clonning

    git clone https://github.com/tarc/csharp-skel.git &&\
    cd csharp-skel


## Building 

    mkdir build &&\
    cd build &&\
    cmake .. &&\
    make
