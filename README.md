# YAPL

Yet Another Programming Language (YAPL) is a language with syntax inspired from Lua written for my compilers class. It does NOT compile Lua. Only the syntax is derived from Lua.

The grammar is taken from the [Lua Manual](http://www.lua.org/manual/5.1/manual.html).

To compile the compiler:
```
make
```

This will generate a debug version of the compiler that has assertions enabled and some other debugging enabled. The executable is output into `bin/`

To remove all object files and the generated flex and bison files, run:
```
make clean
```

To disable the debugging symbols:
```
make release
```

To run the compiler, call the executable with the input file as a command line argument. You can optionally specify the output file with the -o option.
