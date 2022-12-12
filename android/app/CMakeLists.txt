cmake_minimum_required(VERSION 3.4.1)  # for example
project(hello_library VERSION 1.0.0 LANGUAGES C)

add_library( native_add

             # Sets the library as a shared library.
             SHARED

             # Provides a relative path to your source file(s).
             /home/mvasion/Документы/work/projects/C/flutter_map_c/src/main.c )