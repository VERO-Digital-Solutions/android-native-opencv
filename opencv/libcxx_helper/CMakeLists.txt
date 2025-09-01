cmake_minimum_required(VERSION 3.10.2)


project(AndroidNativeOpenCV)

# dummy target to bring libc++_shared.so into packages
add_library(opencv_jni_shared STATIC dummy.cpp)
