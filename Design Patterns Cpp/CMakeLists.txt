# CMakeList.txt : CMake project for Design Patterns Cpp, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (CMakeTarget "Design Patterns Cpp.cpp" "Design Patterns Cpp.h" "Creational Patterns/Factory Method.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET CMakeTarget PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
