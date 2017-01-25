cmake_minimum_required (VERSION 3.5 FATAL_ERROR)
project (hello-cmake)

add_executable (hello hello.cpp)

# find_package (sqlite3 REQUIRED)
# target_link_libraries (hello PRIVATE sqlite3)

install (TARGETS hello DESTINATION hello/bin)
