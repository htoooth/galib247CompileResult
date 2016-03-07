# GALIB win
[GALIB](http://lancet.mit.edu/ga/) is a c++ library of genetic algorithm components. GAlib contains a set of C++ genetic algorithm objects. The library includes tools for using genetic algorithms to do optimization in any C++ program using any representation and genetic operators. The documentation includes an extensive overview of how to implement a genetic algorithm as well as examples illustrating customizations to the GAlib classes.

----

## What I do
I compile it into library under `VS 2015` at `win7 64`.

## Download
[Link](https://codeload.github.com/htoooth/galib247CompileResult/zip/master)

## How to use
You can copy all files from `result\vs2015` to `your\path`. Then configure your `library path` and `include path` in `visual studio IDE`.

## Please note
Currently this library is compiled using `visual studio 2015`. I can not sure the compiled result can be used in other visual studio, such as `vs2010`, `vs2012`, etc. If find the result is not effect, you should be follow below steps in order to get the library by yourself.

## How to compile

### Step 1
Download this [repository](https://codeload.github.com/htoooth/galib247CompileResult/zip/master) and extract it to `your\path`.

### Step 2
Find your `VS IDE`'s `Developer Command Prompt Tool` and open it. Usually this tool locates in `Visual Studio Tools` folder. Note it's a console tool. When you open it, your can see a black windows.

### Step 3
Use above window and change your work directory to `GALIB` root directory. You can use `cd /d your\GALIB\path` command.

### Step 4
Type `nmake /f makefile.vcpp lib` and start to compile this library.

### Step 5
When above steps are completed, type `nmake /f makefile.vcpp install`. This command will install this library in your computer at `c:\temp` path.

### Step 6
Congratulations！There is nothing step else. And just enjoy yourself.

## Licenses
[Creative Commons Public Licenses](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

## About Me

* Github: <https://github.com/htoooth>
* Email: [htoooth](mailto:ht.anglenx#google.com)



