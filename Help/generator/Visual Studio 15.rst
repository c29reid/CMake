Visual Studio 15
----------------

Generates Visual Studio 15 project files.

The :variable:`CMAKE_GENERATOR_PLATFORM` variable may be set
to specify a target platform name (architecture).

For compatibility with CMake versions prior to 3.1, one may specify
a target platform name optionally at the end of this generator name:

``Visual Studio 15 Win64``
  Specify target platform ``x64``.

``Visual Studio 15 ARM``
  Specify target platform ``ARM``.
