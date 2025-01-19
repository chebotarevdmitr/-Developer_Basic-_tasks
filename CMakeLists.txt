cmake_minimum_required(VERSION 3.30)
project(HelloWorld CXX)

# Указываем, что мы создаем исполняемый файл из файла main.cpp
add_executable(hello main.cpp)

#target_compile_features( hello PUBLIC cxx_std_17)
#if (MSVC)
 #target_compile_options( hello PUBLIC /W4 /WX)
 #else()
  #target_compile_options( hello PUBLIC -Wall -Wextra -Werror -pedantic)
  #endif()