# A set of tools for c language.

clangtools is made with python3. It has no dependency other than python 3.2
or higher.

## clanggen

Generate c files, Convert text files to cstring or binary files to c
`unsigned char[]`.

```
Example usage

$ ./clanggen txt2cstr -o ../src/programs *.glsl

output files are programs.h and programs.c

```