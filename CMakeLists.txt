PROJECT(COOLPROP)  
  
cmake_minimum_required(VERSION 2.6)  

enable_language (CXX)
  
SET(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g -Wall -O2")  
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -Wall -O2")  
  
add_subdirectory(src bin)

install(DIRECTORY   include
	DESTINATION . )

