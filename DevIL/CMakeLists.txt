cmake_minimum_required(VERSION 2.6)

set(ZLIB_INCLUDE_DIR "${CMAKE_SOURCE_DIR}/thirdparty/zlib-1.2.11/")
set(ZLIB_LIBRARY "${CMAKE_SOURCE_DIR}/thirdparty/lib/x86/Release/zlibstatic.lib")

set(PNG_PNG_INCLUDE_DIR "${CMAKE_SOURCE_DIR}/thirdparty/lpng1637/")
set(PNG_LIBRARY "${CMAKE_SOURCE_DIR}/thirdparty/lib/x86/Release/libpng16_static.lib")

set(JPEG_INCLUDE_DIR "${CMAKE_SOURCE_DIR}/thirdparty/libjpeg/")
set(JPEG_LIBRARY "${CMAKE_SOURCE_DIR}/thirdparty/lib/x86/Release/libjpeg.lib")

project(ImageLib)

add_subdirectory(src-IL)
add_subdirectory(src-ILU)
add_subdirectory(src-ILUT)

