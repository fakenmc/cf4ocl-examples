### Summary

This repository contains examples and experiments using the [cf4ocl][]
library for OpenCL.

### Examples

| Example      | Specific dependencies | Description                                                 |
| ------------ | --------------------- | ----------------------------------------------------------- |
| matmult      | [OpenMP][], [GLib][]  | Comparison of matrix multiplication with OpenCL and OpenMP  |
| bankconf     | [GLib][]              | Example of GPU bank conflicts                               |
| ca_mt        | [GLib][]              | Game of Life, multithreaded                                 |
| prng         | pthread               | Massive pseudo-random number generator, multithreaded       |

### Global dependencies

* [cf4ocl][]
* [OpenCL][] ([any implementation][oclimpl])

### Build tools

* [CMake][]
* A C99 compiler

### License

These examples are licensed under [GPLv3][].

[GLib]: https://developer.gnome.org/glib/ "GLib"
[OpenCL]: http://www.khronos.org/opencl/ "OpenCL"
[oclimpl]: https://github.com/FakenMC/cf4ocl/wiki/OpenCL-implementations "OpenCL implementations"
[GPLv3]: http://www.gnu.org/licenses/gpl.html "GPLv3"
[CMake]: http://www.cmake.org/
[cf4ocl]: https://github.com/FakenMC/cf4ocl "cf4ocl"
[OpenMP]: http://openmp.org/

