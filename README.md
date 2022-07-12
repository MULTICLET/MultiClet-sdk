
# MULTICLET C Compiler

This is a beta version of a MULTICLET C compiler, based on LLVM 13.0.0.

This release allows only to compile separate files into assembly text:

* Without optimizations: ``clang -S main.c``

* With optimizations: ``clang -S -O3 main.c``

The rest of the binaries needed for building and running programs will be available in later releases.



