# cryptopp
Crypto++ with CMake build system
This is git repository is currently based on Crypto++ 7.0 and will be
updated from time to time to track the most recent release. The only
modification is the addition of a CMake-based build system.

This is convenient for other projects that use CMake and Crypto++ because Crypto++ can be
easily incorporated into their build process using git submodules and a simple
``add_subdirectory`` command.

Currently, the CMake-based build can create shared and static versions of
`cryptopp` for the Intel `i386` and
`x86_64` architectures on Windows (Visual Studio, MinGW), MacOS (Clang) and
Linux (GCC & Clang). The `armv7` and `armv8` architectures are supported on
Linux (GCC & Clang). Other combinations may work but have not been tested.
