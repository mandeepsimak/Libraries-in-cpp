Libraries-in-cpp
================

Library for simple add function of two integer numbers.<br>

Download this library and place it where you want to use it.<br>

How to use.<br>
1) Include it as another header file (#include "lib.h")<br>

2) Compiling a program<br>

    $ g++ program_name.cpp -o main -L/path/to/library -llib
    
3) Execute your program<br>

    $ ./main

If you got following error:<br>

    ./main: error while loading shared libraries: liblib.so: 
    cannot open shared object file: No such file or directory
    
Then create symbolic link of library:

    $ ln -s /path/to/library/liblib.so /usr/lib/liblib.so
    
<i>lib_main.cpp</i> is a example of using this library.
    
    
