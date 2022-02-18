# C++ Tutorial Samples

This repository contains C++ sample codes that I adopted from various sources to help instruct programming. These samples try to help newcomers quickly find an appropriate pattern for solving their programming problems. Also they can quickly find out how a certain language construct, or a popular function is generally used.

## Running the Samples

Each sample has a separate folder of its own, and is usually in a file named `Prog.cpp`. If you want to build a sample with Microsoft Visual Studio, then you need to create a project and copy the sample into that project by your own.

However there's a `Makefile` in each directory, which makes the process of building and running the samples easier in *Linux/Unix* and *Cygwin*. In order to build each sample, simply `cd` to its directory and run `make` to build the required executable. Run `make clean` to clean-up your directory. Also `make full`, first cleans and then rebuilds each sample. 

## References

Beside several Internet sources, the following are the main references that I used during the course of creating these samples. Most of the samples are adopted from the first reference. Even many of the comments are quoted from it. I strongly recommend studying the first reference, if you are learning C++ as a *first* programming language.

[1] H. Deitel and P. Deitel, *C++ How to Program*, 5th ed. Prentice Hall, Jan. 2005.

[2] B. Stroustrup, *The C++ Programming Language*, 3rd ed. Addison-Wesley Professional, Jun. 1997.


