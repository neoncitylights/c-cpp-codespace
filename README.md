# Codespaces for C/C++

Make sure you're in the same file as your C/C++ code by entering the src directory, via:
```
cd src
```

Compiling C code with GCC:
```bash
# syntax
# - first parameter is c file
# - second parameter is output flag (-o) which is the name
#   of the executable file to run
gcc <program-file-name>.c -o <executable-file>
./<executable>

# example
cd src
gcc main.c -o my-cool-program
./my-cool-program
```

Compiling C++ code with G++:
```bash
g++ main.cpp hello-world
./hello-world
```
