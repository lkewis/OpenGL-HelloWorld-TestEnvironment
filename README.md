# OpenGL-HelloWorld-TestEnvironment
 Basic implementation of OpenGL in C++ with a test environment and menu system.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This uses the GLFW and GLEW win32 includes and libraries.

```
- Visual Studio 2017
- GLFW (included in /Dependencies)
- GLEW (included in /Dependencies)
- GLM (included in /OpenGL/src/vendor)
- stb_image (included in /OpenGL/src/vendor)
- imgui (included in /OpenGL/src/vendor)
```

### Installing

A step by step series of examples that tell you how to get a development env running

Opening in Visual Studio

```
Load the 'OpenGL.sln' project file in Visual Studio 2017
```

Link the Dependencies

```
Right click the project title, go to 'Properties' and make sure all includes and libraries from /Dependencies are linked correctly
```

## Running the project

Either run the 'OpenGL.exe' file in (/Debug) or compile and run the project file in Visual Studio 2017.

## Built With

* [GLFW 3.3](https://www.glfw.org/) - The OpenGL Library
* [GLEW 2.1.0](http://glew.sourceforge.net/) - The OpenGL Extension Wrangler Library
* [GLM 0.9.9.5](https://glm.g-truc.net/0.9.9/index.html) - OpenGL Mathematics Library
* [stb_image.h](https://github.com/nothings/stb/blob/master/stb_image.h) - stb single-file public domain libraries for C/C++ 
* [imgui 1.60](https://github.com/ocornut/imgui/releases/tag/v1.60) - Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies

## Authors

* **Lewis Hackett** - *Followed Tutorial* - [lkewis](https://github.com/lkewis)
* **Yan Chernikov** - *Original Author* - [TheCherno] (https://github.com/TheCherno)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Made possible thanks to the fantastic OpenGL tutorial series by TheChernoProject: (https://www.youtube.com/playlist?list=PLlrATfBNZ98foTJPJ_Ev03o2oq3-GGOS2)
