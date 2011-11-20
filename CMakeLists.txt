cmake_minimum_required (VERSION 2.6)
project (LibTouchMouseGestureFramework)

# include files
include_directories("./include")

# static library output
add_library(touchmousegestures_static STATIC src/libtouchmousegestures.c)

# shared library output
add_library(touchmousegestures SHARED src/libtouchmousegestures.c)
