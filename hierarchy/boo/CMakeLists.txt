# CMakeLists.txt from 'boo' directory

cmake_minimum_required(VERSION 2.8)
project(boo)

message("From subdirectory 'boo':")
message("  Source (general): ${PROJECT_SOURCE_DIR}")
message("  Source (foo): ${foo_SOURCE_DIR}")
message("  Source (boo): ${boo_SOURCE_DIR}")
