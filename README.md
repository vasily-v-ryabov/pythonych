# Experimental Python compiler written in MLIR

This is a typed subset of Python which produces MLIR IR instead of a bytecode.

## Requirements and environment setup

 1. First you need MLIR (on Linux you can get MLIR 19.x from Ubuntu/Debian apt repositories).
 2. Python 3.9 is also required since it contains AST parser functions in C API (in Python 3.10+ these functions are hidden).
 3. (Windows only) Visual Sttudio 2022 (Community Edition is enough minimum).

On Ubuntu MLIR 19.x can be installed by this Shell script:
```sh
./install-req.sh
```
On Windows MLIR can be built from source code by this batch script (VS 2022 needs to be installed manually):
```
./install-req.bat
```
