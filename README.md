# Makefile vs CMake

# Makefile

Makefile is a kind of recipe to tell the compiler how the source code is compiled to generate a resulting file such as an executable.
The "recipe" file is generally named `Makefile`.
When you manually use Makefile, you will run a command `make`.

In this repository, you can find an example.
```
cd makefile
make
./hello
```

# CMake

CMake is the software to generate Makefiles. CMake follows instructions given in a file named `CMakeLists.txt`.
When you manually use CMake, you will run a command `cmake`, followed by `make` command.

In this repository, you can find an example.
```
cd cmake
mkdir build
cd build
cmake ..
make
./hello
```
See the last two steps are the same. In the directory `build`, you can find the generated Makefile.

