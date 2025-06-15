# sqlcipher-fetch-and-build-inside-cmake-project

This sample demontrates how to fetch and build sqlcipher inside cmake project under Windows (Visual Studio 2022).
Sample uses vcpkg to get and build sqlcipher dependencies. Why can't you use sqlcipher from vcpkg? You can, but vcpkg's version can`t be built for windows static (static-md) triplets.
In the sample I'm using x64-windows-static-md triplet

Note. If you need dynamic version of sqlcipher, just use vcpkg

Prerequisites
Download and install Tcl (recommended link)
Add tcl tools to PATH. You can skip this step, but make sure you made SET "PATH=%PATH%;c:\path\to\tcl\tools" in Visual Studio Command Prompt
