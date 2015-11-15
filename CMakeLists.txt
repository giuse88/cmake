cmake_minimum_required(VERSION 3.0.1)

project (Math)
set(CMAKE_BUILD_TYPE Release)

set(MAKE_INCLUDE_CURRENT_DIR ON)

ADD_SUBDIRECTORY(shared_lib)
ADD_SUBDIRECTORY(main)
