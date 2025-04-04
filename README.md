# Installing OpenCL on windows with Intel Processors and GPUs
## Git  
1. Download git 
## Intel OpenCL runtime
1. Download latets Intel OpenCL runtime [here](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-cpu-runtime-for-opencl-applications-with-sycl-support.html). Scroll down to see here the libraries are installed. 
2. Add OpenCL runtime bin folder to path,  To know more about windows  `PATH` variable watch [this](https://www.youtube.com/watch?v=P8zMeCY2qtc) video.
## chocolatey
1. Install chocolatey using the guide provided [here](https://www.liquidweb.com/blog/how-to-install-chocolatey-on-windows/)
2. We will use chocolatey to install our C/C++ compiler. To do so open a terminal or command prompt as administrator and type `choco install mingw`, and the follow the prompts.

## Getting OpenCL headers
1. Intel OpenCL runtime only give us libraries but we also need OpenCL headers which are avialable at Khronos group github. To get them clone this [repo](https://github.com/KhronosGroup/OpenCL-Headers)
2. Then OpenCL header files are in OpenCL-Headers/CL and you can copy CL folder to whereever its covenient for you.

With this you can start with basic examples, ask AI about linking the OpenCL static libray and dll, also remember to provide OpenCL include path during compilation.