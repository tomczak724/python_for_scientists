# Cython

Writing code in Python is fast. But the code you write isn't as fast as, say, C code. Wouldn't it be nice if Python were faster? Enter Cython. Cython allows you to easily wrap C and C++ code in Python. It also allows you to use C-like static typing syntax directly in your Python code. Cython also provides parallel processing options that are not available in normal Python code.

Cython is two things:

* a way to add types to Python code, to make it faster
* a way to interface between C/C++/Cython and Python


## Installation

Consider installing [Anaconda](http://docs.continuum.io/anaconda/install.html). It will come packaged with Cython, but also a ton of other really great Python libraries.

However, Anaconda is not the only way to install Cython. For instance, on any Debian-based Linux computer, a simple `apt-get` should work fine:

    $ pip install cython
    ...
    $ python setup.py install
    $ cython -V
    Cython version 0.20.2


## Compiling and Running Cython

TODO


## Cython Syntax

TODO


## Extension Types

TODO


## Organizing Cython Code

TODO


## Wrapping C in Cython

TODO


## Wrapping C++ in Cython

TODO


## Profiling Cython

TODO


## NumPy and MemoryViews

TODO


## Parallel Programming

TODO


## Further Reading

 * [Cython - O'Reilly textbook](https://www.amazon.com/Cython-Programmers-Kurt-W-Smith/dp/1491901551/ref=sr_1_1?ie=UTF8&qid=1523792400&sr=8-1&keywords=cython+o%27reilly) - A good intro text
 

[Back to Syllabus](../../README.md)