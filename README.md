###OpenCL-OpenGL Interop Examples

####Requirements

* CMake (>= 3.0.2)
* OpenCL Libraries (should be located by CMake automatically if they are installed using package
  managers)
* GLFW, GLEW - Both should be automatically found by CMake.

More examples will be added progressively. Current list of examples is given below.

* Julia Sets - Julia fractal images are generated using OpenCL and then rendered onto a OpenGL window using texture(the texture is shared between the OCL and OGL contexts).
* Particle Simulation - This is a work in progress, currently it is just random noise changing every
  frame. This example uses intermediate buffer to copy data from OpenCL buffer to OpenGL vertex
buffer object.

####Note
All examples are by default built for 64-bit machines. If you have need 32-bit executables, please modify the necessary options and rebuild the source files.
