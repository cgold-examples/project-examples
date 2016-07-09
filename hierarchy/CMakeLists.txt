# Top level CMakeLists.txt

cmake_minimum_required(VERSION 2.8)
project(foo)

message("From top level:")
message("  Source (general): ${PROJECT_SOURCE_DIR}")
message("  Source (foo): ${foo_SOURCE_DIR}")

add_subdirectory(boo)
