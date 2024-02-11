# proc-design-Lab-1
## Make Note:
What version of `cmake` is running in your environment?
* The version of `cmake` running in my environment is version 3.28.3

Targets for `make help`
* `all`
* `clean`
* `depend`
* `edit_cache`
* `rebuild_cache`
* `hello_world`
* `hello.o`
* `hello.i`
* `hello.s`

The `all` argument does the entire compilation and creates the exceutblae for the targetifed files in the CMakeLists.txt file. This is also the default argument if no target is specified.

The `hello.o` argument is the object code for *hello.cpp*

The `hello.i` argument is the expanded code file for *hello.cpp*

The `hello.s` argument is the assembly file for *hello.cpp*

## End of Lab Questions
* The paths used by `target_sources` and `target_include_directories` are relative to the parent directory of *include/* and *src/* which in my lab 1 Folder set up would be *proc-design-Lab-1/*
* Cmake is a metabuild system, which is what is used to produce `ninja` and `make` which in turn creates an excecutable file.
* It is important to run `cmake` in its own directory because it creates a lot of files when ran. The separate folder is used to contain the files produces as to not clutter the main working directory.