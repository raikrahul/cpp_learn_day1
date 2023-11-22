# CMakeList.txt : CMake project for day1, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (day1 "day1.cpp" "day1.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET day1 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
