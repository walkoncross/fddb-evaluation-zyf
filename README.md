# FDDB EVALUATION

## Content:
```
.
|-- README.md
|-- evaluation_linux        # FDDB official evalution code, only support Linux
|-- evaluation_windows_vs   # evalutaion code for Windows Visual Studio, adding getopt.h and getopt.c
`-- vs_projs                # VS projects
```

## Required Libraries
OpenCV 1.0 (http://sourceforge.net/projects/opencvlibrary/)

## Compile
### Linux

Please refer to [evaluation_linux/README.txt](evaluation_linux/README.txt).

### Windoes Visual Studio
1. Replace "$(OPENCV100)" in [vs_projs/opencv_props/opencv100.props](vs_projs/opencv_props/opencv100.props) by the correct path of OpenCV 1.0 root-dir on your computer. 
1. Open vs-projs/vs201x_poroj/*.sln.

or
Just open the .sln file, and manually set opencv include/lib directories.

## Usage
Please refer to [evaluation_linux/README.txt](evaluation_linux/README.txt).

