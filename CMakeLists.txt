cmake_minimum_required(VERSION 3.1)
project(name_project)
set(CMAKE_CXX_STANDARD 17)
# .hpp and .h files
include_directories(include_folder)# include folder is the folder that contains all include files
# to make execute file
add_executable(name_project src/test.cpp) # the project name is variable, src is the folder that contains all cpp files,test.cpp is the specific file to execute
target_link_libraries(name_project) #this aims to link header and cpp files all together