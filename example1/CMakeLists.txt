 cmake_minimum_required(VERSION 3.0)
include_directories(
 ${PROJECT_SOURCE_DIR}/abc
 /usr/include
 )
include_directories(/usr/include)
include_directories(/usr/include2)
#set(SRC_LIST main.cpp)
aux_source_directory(. source)
add_executable(example1 ${source})
#	find_library(LIB_GEN NAMES xml PATHS ../../../lib NO_DEFAULT_PATH)
#	target_link_libraries(test ${LIB_GEN})
