cmake_minimum_required(VERSION 3.25)
project(MyCppApplication)

set(CMAKE_CXX_STANDARD 20)

add_executable(MyCppApplication main.cpp thread/threading.cpp stl/stlvariables.cpp stackandhap/stackandhap.cpp testclass/testclass.cpp testlink/testlink.cpp testpointer/testpointer.cpp testvariables/testvariables.cpp)
