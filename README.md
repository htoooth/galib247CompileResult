# GALIB win
`GALIB` in windows.

## How to use
You can copy all files from `result\vs2015` to `your/path`. Then configure your `library path` and `incloude path` in `visual studio IDE`.

## Plean Note
Current This library is compiled using `visual studio 2015`. I can not sure the result can be used in other visual studio, such as `vs2010`,`vs2012`. If you find the result is not effect, follow below steps to compile yourself library.

## How to compile

### Step 1
Find your `VS IDE`'s `Developer Command Prompt for VS2015` tool. This tool is console tool.

### Step 2
Then change your work directory to `GALIB` root directory.

### Step 3
Type `nmake /f makefile.vcpp lib` and start to compile this library.

### Step 4
When above step are completed, type `nmake /f makefile.vcpp install`. This command will install this library in your computer at `c:\temp` path.

### Step 5
Nothing And just enjoy yourself.


## Licenses
[Creative Commons Public Licenses](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

## About Me

* Github: <https://github.com/htoooth>
* Email: [htoooth](mailto:ht.anglenx#google.com)



