# CMake_needed_patch
Some needed patch for standart cmake modules, for build my project on Windows (MinGW-w64)

1 way: Try use patch on git bash
For Example: 
patch /c/Program\ Files/CMake/share/cmake-3.31/Modules/FindOpenSSL.cmake /c/Users/User/CMake_needed_patch/FindOpenSSL.patch
patch /c/Program\ Files/CMake/share/cmake-3.31/Modules/FindPkgConfig.cmake /c/Users/User/CMake_needed_patch/FindPkgConfig.patch

2 way: Just Raplace File
For Example:
cp /c/Users/User/CMake_needed_patch/FindOpenSSL.cmake /c/Program\ Files/CMake/share/cmake-3.31/Modules/
cp /c/Users/User/CMake_needed_patch/FindPkgConfig.cmake /c/Program\ Files/CMake/share/cmake-3.31/Modules/
