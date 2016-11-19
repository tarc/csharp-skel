This is a skeleton project of a simple C# hello world application together with CMake modules to carry on the build and NuGet package management. This project features a library consumed by the main application.

All CMake modules present in the [cmake-submodules](/cmake-submodules) directory are from the [SimpleITK project](https://github.com/SimpleITK/SimpleITK.git).


## Clonning

    git clone https://github.com/tarc/csharp-skel.git &&\


## Dependencies

### CMake

The latest release can be found in [CMake's official site](https://cmake.org/).

### Mono

Follow the instructions from the official website [Install Mono on Linux](http://www.mono-project.com/docs/getting-started/install/linux/) to get the latest release version running on a Linux machine.

### NuGet

Download the latest windows x86 commandline version from [the official website](http://dist.nuget.org/index.html) and save it in the root directory of this project.


## Building 

    cd csharp-skel
    mkdir build
    cd build
    cmake ..
    cmake --build .
